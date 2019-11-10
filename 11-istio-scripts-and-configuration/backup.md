<!---
Current Directory : /in28Minutes/git/kubernetes-crash-course/11-istio-scripts-and-configuration
-->

## Complete Code Example


### /06-helloworld-canary.yaml

```
apiVersion: networking.istio.io/v1alpha3
kind: VirtualService
metadata:
  name: helloworld-virtual-services
spec:
  hosts:
    - "*"
  gateways:
    - http-gateway
  http:
    - match:
        - uri:
            exact: /hello-world
      route:
        - destination:
            host: hello-world-rest-api
            subset: v1
          weight: 10
        - destination:
            host: hello-world-rest-api
            subset: v2
          weight: 90
---
apiVersion: networking.istio.io/v1alpha3
kind: DestinationRule
metadata:
  name: hello-world-rest-api
spec:
  host: hello-world-rest-api
  subsets:
    - name: v1
      labels:
        version: v1
    - name: v2
      labels:
        version: v2
```
---

### /05-helloworld-mirroring.yaml

```
apiVersion: networking.istio.io/v1alpha3
kind: VirtualService
metadata:
  name: helloworld-virtual-services
spec:
  hosts:
    - "*"
  gateways:
    - http-gateway
  http:
    - match:
        - uri:
            exact: /hello-world
      route:
        - destination:
            host: hello-world-rest-api
            subset: v1
          weight: 100
      mirror:
        host: hello-world-rest-api
        subset: v2
---
apiVersion: networking.istio.io/v1alpha3
kind: DestinationRule
metadata:
  name: hello-world-rest-api
spec:
  host: hello-world-rest-api
  subsets:
    - name: v1
      labels:
        version: v1
    - name: v2
      labels:
        version: v2
```
---

### /03-creating-virtualservice-external.yaml

```
apiVersion: networking.istio.io/v1alpha3
kind: VirtualService
metadata:
  name: helloworld-virtual-services
spec:
  hosts:
  - "*"
  gateways:
  - http-gateway                      # 1
  http:
  - match:
    - uri:
        prefix: /hello-world
    route:
    - destination:
        host: hello-world-rest-api             # 2
        port:
          number: 8080
```
---

### /02-creating-http-gateway.yaml

```
apiVersion: networking.istio.io/v1alpha3
kind: Gateway
metadata:
  name: http-gateway
spec:
  selector:
    istio: ingressgateway
  servers:
  - port:
      number: 80
      name: http
      protocol: HTTP
    hosts:
    - "*"
```
---

### /01-helloworld-deployment.yaml

```
apiVersion: apps/v1
kind: Deployment
metadata:
  labels:
    app: hello-world-rest-api
  name: hello-world-rest-api
  namespace: default
spec:
  replicas: 1
  selector:
    matchLabels:
      app: hello-world-rest-api
  template:
    metadata:
      labels:
        app: hello-world-rest-api
    spec:
      containers:
      - image: in28min/hello-world-rest-api:0.0.1-RELEASE
        imagePullPolicy: IfNotPresent
        name: hello-world-rest-api
        ports:
        - name: liveness-port
          containerPort: 8080
          hostPort: 8080
        resources:
          requests:
            cpu: 200m
            memory: 512Mi
          limits:
            cpu: 400m
            memory: 1024Mi #256Mi 
        readinessProbe:
          httpGet:
            path: /
            port: liveness-port
          failureThreshold: 1
          periodSeconds: 10
          initialDelaySeconds: 30
        livenessProbe:
          httpGet:
            path: /
            port: liveness-port
          failureThreshold: 3
          periodSeconds: 10
          initialDelaySeconds: 30
---
apiVersion: v1
kind: Service
metadata:
  labels:
    app: hello-world-rest-api
  name: hello-world-rest-api
  namespace: default
spec:
  #type: LoadBalancer
  ports:
  - port: 8080
    protocol: TCP
  selector:
    app: hello-world-rest-api
```
---

### /07-hw-virtualservice-all-services.yaml

```
apiVersion: networking.istio.io/v1alpha3
kind: VirtualService
metadata:
  name: helloworld-virtual-services
spec:
  hosts:
  - "*"
  gateways:
  - http-gateway                      # 1
  http:
    - match:
        - uri:
            exact: /hello-world
      route:
        - destination:
            host: hello-world-rest-api
            port:
              number: 8080
    - match:
        - uri:
            prefix: /currency-exchange
      route:
        - destination:
            host: currency-exchange
            port:
              number: 8000
    - match:
        - uri:
            prefix: /currency-conversion
      route:
        - destination:
            host: currency-conversion
            port:
              number: 8100
```
---

### /04-helloworld-multiple-deployments.yaml

```
apiVersion: v1
kind: Service
metadata:
  name: hello-world-rest-api
  labels:
    app: hello-world-rest-api
spec:
  ports:
    - port: 8080
      name: http
  selector:
    app: hello-world-rest-api
---
apiVersion: apps/v1
kind: Deployment
metadata:
  name: hello-world-rest-api-v1
  labels:
    version: v1
spec:
  replicas: 1
  selector:
    matchLabels:
      app: hello-world-rest-api
      version: v1
  template:
    metadata:
      labels:
        app: hello-world-rest-api
        version: v1
    spec:
      containers:
        - name: hello-world-rest-api
          image: in28min/hello-world-rest-api:0.0.1-RELEASE
          imagePullPolicy: IfNotPresent #Always
          ports:
            - containerPort: 8080
---
apiVersion: apps/v1
kind: Deployment
metadata:
  name: hello-world-rest-api-v2
  labels:
    version: v2
spec:
  replicas: 1
  selector:
    matchLabels:
      app: hello-world-rest-api
      version: v2
  template:
    metadata:
      labels:
        app: hello-world-rest-api
        version: v2
    spec:
      containers:
        - name: hello-world-rest-api
          image: in28min/hello-world-rest-api:0.0.2-RELEASE
          imagePullPolicy: IfNotPresent #Always
          ports:
            - containerPort: 8080
```
---
