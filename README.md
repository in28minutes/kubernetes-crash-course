# Kubernetes Crash Course for Java Developers on Google Cloud

## Learn Kubernetes and Docker with Google Kubernetes Engine deploying Spring Boot Microservices

Learn Kubernetes? Yes.   Learn Docker, Istio and Helm? Yes.
Deploy Spring Boot and Spring Cloud Microservices to Kubernetes? Yes. Of Course.

Do you have ZERO experience with Docker and Kubernetes? No Problem.

Do you want to learn Kubernetes and deploy Spring Boot Microservices to Kubernetes with an easy to learn, step by step approach?

Do you want to join 300,000+ learners having Amazing Learning Experiences with in28Minutes?

Look No Further!

## First Commands

```
kubectl create deployment hello-world-rest-api --image=in28min/hello-world-rest-api:0.0.1.RELEASE
kubectl expose deployment hello-world-rest-api --type=LoadBalancer --port=8080
```

## Getting Started
- [Video - Docker in 5 Steps](https://youtu.be/Rt5G5Gj7RP0)
- [Video - Spring in 10 Steps](https://www.youtube.com/watch?v=edgZo2g-LTM)
- [Video - Spring Boot in 10 Steps](https://www.youtube.com/watch?v=pcdpk3Yd1EA)
- [Video - JPA/Hibernate in 10 Steps](https://www.youtube.com/watch?v=MaI0_XdpdP8)

## Installation Guides

#### Required Tools

- Java 8+
- Eclipse - Recent Version 
- Maven
- Git
- Docker
- Kubernetes
- ELB CLI
- Google Cloud Account

#### Installing Guides

- [Playlist - Installing Java, Eclipse & Embedded Maven](https://www.youtube.com/playlist?list=PLBBog2r6uMCSmMVTW_QmDLyASBvovyAO3)

#### Troubleshooting Installations

- Eclipse and Embedded Maven
  - Troubleshooting Guide : https://github.com/in28minutes/in28minutes-initiatives/tree/master/The-in28Minutes-TroubleshootingGuide-And-FAQ#tip--troubleshooting-embedded-maven-in-eclipse
  - PDF : https://github.com/in28minutes/SpringIn28Minutes/blob/master/InstallationGuide-JavaEclipseAndMaven_v2.pdf
  - GIT Repository For Installation : https://github.com/in28minutes/getting-started-in-5-steps


#### Troubleshooting Docker

- Problem - Caused by: com.spotify.Docker.client.shaded.javax.ws.rs.ProcessingException: java.io.IOException: No such file or directory
- Solution - Check if Docker is up and running!
- Problem - Error creating the Docker image on MacOS - java.io.IOException: Cannot run program docker-credential-osxkeychain”: error=2, No such file or directory
- Solution - https://medium.com/@dakshika/error-creating-the-docker-image-on-macos-wso2-enterprise-integrator-tooling-dfb5b537b44e

Removed subprocess.CalledProcessError: Command '['/usr/local/bin/docker-credential-desktop', 'get']' returned non-zero exit status 1
I had this:
`cat ~/.docker/config.json`
`{"auths":{},"credsStore":"", "credsStore":"desktop","stackOrchestrator":"swarm"}`
I updated to this:
`{"auths":{},"credsStore":"","stackOrchestrator":"swarm"}`

## Course Overview

******* Course Overview *******

Architectures are moving towards Microservices and Cloud. Docker makes it easy to containerize microservices. Kubernetes makes it easy to manage clusters with 1000's of containers running 1000's of microservices. Google Kubernetes Engine (GKE) makes it super easy to create Kubernetes Clusters. 

How about getting them all together and deploying Spring Boot Microservices to Kubernetes Clusters created on Google Cloud Platform using Google Kubernetes Engine (GKE)?

In this handson course, we will use Docker and Kubernetes to deploy a variety of Spring Boot Applications on Google Cloud using Google Kubernetes Engine:
- REST APIs - Hello World
- Todo Web Application War
- CCS and CES Microservices

You will implement Service Discovery, Centralized Configuration, Distributed Tracing and Load Balancing for Spring Boot Microservices deployed in Kubernetes Clusters.

You will learn to use Helm Charts, Istio Service Mesh, Google Stackdriver and Spring Cloud Kubernetes to play with Java Microservices on Kubernetes.

This course would be a perfect first step as an introduction to Kubernetes.

You will be using containerizing (using Docker) and deploying a variety of projects to Kubernetes Clusters. These projects are created with  Spring Boot (REST API Framework), Spring (Dependency Management), Spring Security (Authentication and Authorization - Basic and JWT), BootStrap (Styling Pages), Maven (dependencies management), Eclipse (Java IDE) and Tomcat Embedded Web Server. We will help you set up each one of these.

## What you'll learn
- You will Learn the Fundamentals of Kubernetes from Zero, no previous experience required
- You will learn to deploy Spring Boot Microservices to Kubernetes Clusters on Google Cloud.
- You will learn the Basic Kubernetes Concepts - Pods, Replica Sets and Deployment
- You will learn the Basics of Docker - Images, Repository and Containers
- You will learn the important Kubernetes commands 
- You will understand the Kubernetes Architecture
- You will learn to use Kubernetes to Manage Your Clusters
- You will learn the basics of Microservices
- You will use Kubernetes Declaratively with YAML Configuration
- You will learn to expose your Kubernetes Deployments with Services and Ingress
- You will learn to use Kubernetes Config Maps and Secrets
- You will make Zero Downtime Releases with Kubernetes
- You will learn to Create Kubernetes clusters with Master Node and Nodes
- You will learn to deploy Spring Boot Web Applications and Rest API to Kubernetes
- You will become an expert on the Kubernetes command line tool - kubectl
- You will play with Docker, Docker Compose and Kubernetes
- You will use Persistent Storage with Kubernetes - PV and PVC
- You will implement Service Discovery, Centralized Configuration, Distributed Tracing and Load Balancing for microservices deployed in Kubernetes
- You will implement different Auto Scaling approaches with Kubernetes
- You will use Google Stackdriver for Tracing, Error Reporting and Logging
- You will integrate Spring Boot Microservices on Kubernetes with Istio
- You will perform Blue Green Deployments and Canary Deployments with Istio
- You will integrate Kiali, Graphana and Prometheus with Istio and Kubernetes
- You will implement Distributed Tracing for Spring Boot Microsevices with Istio and Jaegar
- You will use Helm to Automate Microservices Deployment on Kubernetes
- You will Join 300,000 Learners having AMAZING LEARNING Experiences with in28Minutes

## Requirements
- You have an attitude to learn while having fun :)
- You have some programming experience with Java, Spring and Spring Boot
- You DO NOT need to have any experience with Kubernetes or Docker
- We will help you install Eclipse, Git client and Docker Desktop

## Who is this course for
- You are a Java Spring Boot developer getting started with the Cloud
- You want to deploy your Java applications with Kubernetes
- You want to deploy your Spring Boot applications with Kubernetes
- You are a Java Developer and You are curious about Kubernetes
- You want to learn to play with Docker, Kubernetes and Spring Boot Microservices

## Step By Step Details

### Introduction to the Course
- 00 Step 01 - Kubernetes Crash Course for Java Developers - Promo
- 00 Step 02 - Kubernetes Crash Course for Java Developers - Course Overview

### Getting Started with Kubernetes and Google Kubernete Engine (GKE)
- 01 Step 01 - Getting Started with Docker, Kubernetes and Google Kubernetes Engine
- 01 Step 02 - Creating Google Cloud Account
- 01 Step 03 - Creating Kubernetes Cluster with Google Kubernete Engine (GKE)
- 01 Step 04 - Review Kubernetes Cluster and Learn Few Fun Facts about Kubernetes
- 01 Step 05 - Deploy Your First Spring Boot Application to Kubernetes Cluster
- 01 Step 06 - Quick Look at Kubernetes Concepts - Pods, Replica Sets and Deployment
- 01 Step 07 - Understanding Pods in Kubernetes
- 01 Step 08 - Understanding ReplicaSets in Kubernetes
- 01 Step 09 - Understanding Deployment in Kubernetes
- 01 Step 10 - Quick Review of Kubernetes Concepts - Pods, Replica Sets and Deployment
- 01 Step 11 - Understanding Services in Kubernetes
- 01 Step 12 - Quick Review of GKE on Google Cloud Console 
- 01 Step 13 - Understanding Kubernetes Architecture - Master Node and Nodes
- 01 Step 14 - Understand Google Cloud Regions and Zones

### Deploying Spring Boot Hello World Rest API to Kubernetes
- 02 Step 01 - Importing First 3 Spring Boot Projects into Eclipse
- 02 Step 02 - Setting up 01 Spring Boot Hello World Rest API in Local
- 02 Step 03 - Build Docker Image and Push to Docker Hub for Hello World Rest API
- 02 Step 04 - Installing GCloud
- 02 Step 05 - Installing Kubectl
- 02 Step 06 - Deploy 01 Spring Boot Hello World Rest API to Kubernetes
- 02 Step 07 - Generate Kubernetes YAML Configuration for Deployment and Service 
- 02 Step 08 - Understand and Improve Kubernetes YAML Configuration

### Playing with Declarative Configuration for Kubernetes
- 03 Step 01 - Understanding Kubernetes YAML Configuration - Labels and Selectors
- 03 Step 02 - Quick Fix to reduce release downtime with minReadySeconds
- 03 Step 03 - Understanding Replica Sets in Depth - Using Kubernetes YAML Config
- 03 Step 04 - Configure Multiple Kubernetes Deployments with One Service

### Deploying Java Spring Boot Todo Web Application to Kubernetes
- 04 Step 01 - Setting up 02 Spring Boot Todo Web Application in Local
- 04 Step 02 - Pushing Docker Image to Docker Hub for Spring Boot Todo Web App
- 04 Step 03 - Using Kubernetes YAML Config to Deploy Spring Boot Todo Web App
- 04 Step 04 - Playing with Kubernetes Commands - Top Node and Pod

### Deploying Java Todo Web Application using MySQL to Kubernetes
- 05 Step 01 - Code Review of 03 Java Todo Web Application MySQL
- 05 Step 02 - Running MySQL as Docker Container on Local
- 05 Step 03 - Connect Spring Boot Java Todo Web App to MySQL on Local
- 05 Step 04 - Create Docker Image for 03 Todo Web Application and Use Link to connect
- 05 Step 05 - Playing with Docker Compose
- 05 Step 06 - Using Kompose to generate Kubernetes Deployment Configuration
- 05 Step 07 - Review Kubernetes YAML for MySQL and Java Web Application
- 05 Step 08 - Deploy MySQL Database to Kubernetes Cluster
- 05 Step 09 - Understanding Persistent Storage with Kubernetes - PV and PVC
- 05 Step 10 - Using Config Maps for Centralized Configuration with Kubernetes
- 05 Step 11 - Using Secrets with Kubernetes
- 05 Step 12 - Creating a ClusterIP Kubernetes Service for MySQL Database

### Deploying Basic Spring Boot Microservices to Kubernetes
- 06 Step 01 - Introduction to Microservices
- 06 Step 02 - Advantages of Microservices
- 06 Step 03 - Microservices - Challenges
- 06 Step 04 - Overview of CCS and CES Spring Boot Microservices
- 06 Step 05 - Push Docker Images and Create Kubernetes Config for Microservices
- 06 Step 06 - Deploying Spring Boot Microservices to Kubernetes Cluster
- 06 Step 07 - Microservices and Kubernetes Service Discovery - Part 1
- 06 Step 08 - Microservices and Kubernetes Service Discovery - Part 2 DNS
- 06 Step 09 - Microservice Discovery, Centralized Configuration and Load Balancing with Kubernetes
- 06 Step 10 - Using Kubernetes Ingress to Simplify Microservice Access
- 06 Step 11 - Review Google Cloud Load Balancer Backend and Frontends with Ingress

### Integrating Spring Cloud Kubernetes with Spring Boot Microservices
- 07 Step 01 - Using Spring Cloud Kubernetes with Microservices - Project Review
- 07 Step 02 - Deploying Spring Cloud Kubernetes Microservices
- 07 Step 03 - Using RBAC to allow Ribbon to access Service Discovery APIs
- 07 Step 04 - Using Spring Cloud Kubernetes Config to load ConfigMaps
- 07 Step 05 - Understanding Auto Scaling approaches with Kubernetes
- 07 Step 06 - Implementing Horizontal Pod Autoscaling with Kubernetes
- 07 Step 07 - Deleting Your Kubernetes Cluster

### Integrating Spring Boot Microservices on Kubernetes with Google Stackdriver
- 08 Step 01 - Creating New Cluster to Play With Google Stackdriver
- 08 Step 02 - Review Spring Boot Microservices integrated with Google Stackdriver
- 08 Step 03 - Enabling Stackdriver APIs for Your Google Cloud Account
- 08 Step 04 - Deploy Spring Boot Microservices and Explore Google Stackdriver Tracing
- 08 Step 05 - Exploring Google Stackdriver Error Reporting and Logging

### Integrating Spring Boot Microservices on Kubernetes with Istio
- 09 Step 01 - Creating new Kubernetes Cluster for Playing with Istio
- 09 Step 02 - Understanding Service Mesh, Istio and Sidecar Pattern
- 09 Step 03 - Installing Istio on Kubernetes Cluster - CRD and Istio Components
- 09 Step 04 - Review Istio Installation and Deploy Spring Boot App with Side Cars
- 09 Step 05 - Increasing Kubernetes Cluster Size to 3 Nodes
- 09 Step 06 - Understanding Gateways and Virtual Services for Istio
- 09 Step 07 - Basic Deployment Strategies - Rolling Updates and Recreate
- 09 Step 08 - Setting up Multiple Versions of Spring Boot Applications
- 09 Step 09 - Configure Destination Rules and Subsets to implement Mirroring
- 09 Step 10 - Executing Blue Green and Canary Deployments with Kubernetes
- 09 Step 11 - Review Spring Boot Microservices integration with Istio
- 09 Step 12 - Observing Istio Service Mesh with Kiali
- 09 Step 13 - Monitoring Istio Service Mesh with Graphana and Prometheus
- 09 Step 14 - Distribute Tracing for Spring Boot Microsevices with Istio and Jaegar
- 09 Step 15 - Delete Kubernetes Cluster for Playing with Istio

### Using Helm to Automate Microservices Deployment on Kubernetes
- 10 Step 01 - Understanding Helm Basics and Setting up Kubernetes Cluster
- 10 Step 02 - Using Helm Charts to deploy Spring Boot Microservice to Kubernetes
- 10 Step 03 - Using Helm Charts to manage Releases to Kubernetes Cluster

### Appendix - Introduction to Docker in 9 Steps
- 11 Step 01 - Installing Docker - Docker
- 11 Step 02 - Your First Docker Usecase - Deploy a Spring Boot Application
- 11 Step 03 - Important Docker Concepts - Registry, Repository, Tag, Image and Container
- 11 Step 04 - Playing with Docker Images and Containers
- 11 Step 05 - Understanding Docker Architecture - Docker Client, Docker Engine
- 11 Step 06 - Why is Docker Popular
- 11 Step 07 - Playing with Docker Images
- 11 Step 08 - Playing with Docker Containers
- 11 Step 09 - Playing with Docker Commands - stats, system


```sh
for file in *; do mv "${file}" "${file//-/ }"; done
for file in *; do mv "${file}" "${file//   / - }"; done
for file in *; do mv "${file}" "${file//01 Step/Step}"; done
```

### Commands Executed during the course

```

docker run -p 8080:8080 in28min/hello-world-rest-api:0.0.1.RELEASE

kubectl create deployment hello-world-rest-api --image=in28min/hello-world-rest-api:0.0.1.RELEASE
kubectl expose deployment hello-world-rest-api --type=LoadBalancer --port=8080
kubectl scale deployment hello-world-rest-api --replicas=3
kubectl delete pod hello-world-rest-api-58ff5dd898-62l9d
kubectl autoscale deployment hello-world-rest-api --max=10 --cpu-percent=70
kubectl edit deployment hello-world-rest-api #minReadySeconds: 15
kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.2.RELEASE

gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105
kubectl create deployment hello-world-rest-api --image=in28min/hello-world-rest-api:0.0.1.RELEASE
kubectl expose deployment hello-world-rest-api --type=LoadBalancer --port=8080
kubectl set image deployment hello-world-rest-api hello-world-rest-api=DUMMY_IMAGE:TEST
kubectl get events --sort-by=.metadata.creationTimestamp
kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.2.RELEASE
kubectl get events --sort-by=.metadata.creationTimestamp
kubectl get componentstatuses
kubectl get pods --all-namespaces

kubectl get events
kubectl get pods
kubectl get replicaset
kubectl get deployment
kubectl get service

kubectl get pods -o wide

kubectl explain pods
kubectl get pods -o wide

kubectl describe pod hello-world-rest-api-58ff5dd898-9trh2

kubectl get replicasets
kubectl get replicaset

kubectl scale deployment hello-world-rest-api --replicas=3
kubectl get pods
kubectl get replicaset
kubectl get events
kubectl get events --sort.by=.metadata.creationTimestamp

kubectl get rs
kubectl get rs -o wide
kubectl set image deployment hello-world-rest-api hello-world-rest-api=DUMMY_IMAGE:TEST
kubectl get rs -o wide
kubectl get pods
kubectl describe pod hello-world-rest-api-85995ddd5c-msjsm
kubectl get events --sort-by=.metadata.creationTimestamp

kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.2.RELEASE
kubectl get events --sort-by=.metadata.creationTimestamp
kubectl get pods -o wide
kubectl delete pod hello-world-rest-api-67c79fd44f-n6c7l
kubectl get pods -o wide
kubectl delete pod hello-world-rest-api-67c79fd44f-8bhdt

kubectl get componentstatuses
kubectl get pods --all-namespaces

gcloud auth login
kubectl version
gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105

kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.4-SNAPSHOT

kubectl rollout history deployment hello-world-rest-api
kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.4-SNAPSHOT --record

kubectl rollout history deployment hello-world-rest-api
kubectl rollout status deployment hello-world-rest-api
kubectl rollout undo deployment hello-world-rest-api --to-revision=3
kubectl rollout status deployment hello-world-rest-api
kubectl rollout undo deployment hello-world-rest-api --to-revision=3
kubectl rollout status deployment hello-world-rest-api
kubectl rollout history deployment hello-world-rest-api
kubectl get pods
kubectl logs hello-world-rest-api-67c79fd44f-d6q9z
kubectl logs hello-world-rest-api-67c79fd44f-d6q9z -f

kubectl get deployment hello-world-rest-api
kubectl get deployment hello-world-rest-api -o wide
kubectl get deployment hello-world-rest-api -o yaml
kubectl get deployment hello-world-rest-api -o yaml > deployment.yaml
kubectl get service hello-world-rest-api -o yaml
kubectl get service hello-world-rest-api -o yaml > service.yaml

kubectl delete all -l app=hello-world-rest-api
kubectl get all
kubectl apply -f deployment.yaml
kubectl get all

kubectl diff -f deployment.yaml 
kubectl apply -f deployment.yaml 
kubectl delete all -l app=hello-world-rest-api
kubectl get all -o wide

mvn clean install
docker push in28min/todo-web-application-h2:0.0.1-SNAPSHOT
kubectl delete all -l app=hello-world-rest-api

kubectl get pods
kubectl get pods --all-namespaces
kubectl get pods -l app=todo-web-application-h2
kubectl get pods -l app=todo-web-application-h2 --all-namespaces
kubectl get services --all-namespaces
kubectl get services --all-namespaces --sort-by=.spec.type
kubectl get services --all-namespaces --sort-by=.metadata.name
kubectl cluster-info
kubectl top node
kubectl top pod

kubectl get services
kubectl get svc
kubectl get ev
kubectl get rs

kubectl get ns
kubectl get nodes
kubectl get no
kubectl get po

docker run --detach --env MYSQL_ROOT_PASSWORD=dummypassword --env MYSQL_USER=todos-user --env MYSQL_PASSWORD=dummytodos --env MYSQL_DATABASE=todos --name mysql --publish 3306:3306 mysql:5.7
docker run -p 8080:8080 in28min/todo-web-application-mysql:0.0.1-SNAPSHOT
docker run -p 8080:8080 --link=mysql --env RDS_HOSTNAME=mysql in28min/todo-web-application-mysql:0.0.1-SNAPSHOT

docker-compose --version
docker-compose up

brew install kompose
kompose convert

kubectl delete all -l app=todo-web-application-h2

kubectl apply -f mysql-database-data-volume-persistentvolumeclaim.yaml,mysql-deployment.yaml,mysql-service.yaml
kubectl get svc
kubectl apply -f todo-web-application-deployment.yaml,todo-web-application-service.yaml
docker push in28min/todo-web-application-mysql:0.0.1-SNAPSHOT
kubectl logs todo-web-application-b65cc44d9-7h9pr -f

kubectl apply -f mysql-service.yaml
kubectl get pv
kubectl get pvc
kubectl describe pod/mysql-5ccbbbdcd8-5zjqg 

kubectl create configmap todo-web-application-config --from-literal=RDS_DB_NAME=todos
kubectl get configmap todo-web-application-config
kubectl describe configmap/todo-web-application-config

kubectl edit configmap/todo-web-application-config
kubectl scale deployment todo-web-application --replicas=0
kubectl scale deployment todo-web-application --replicas=1

kubectl edit configmap/todo-web-application-config
kubectl apply -f todo-web-application-deployment.yaml 
kubectl edit configmap todo-web-application-config
kubectl scale deployment todo-web-application --replicas=0
kubectl scale deployment todo-web-application --replicas=1

kubectl create secret generic todo-web-application-secrets --from-literal=RDS_PASSWORD=dummytodos
kubectl get secret/todo-web-application-secrets
kubectl describe secret/todo-web-application-secrets
kubectl apply -f todo-web-application-deployment.yaml 

kubectl delete -f mysql-database-data-volume-persistentvolumeclaim.yaml,mysql-deployment.yaml,mysql-service.yaml,todo-web-application-deployment.yaml,todo-web-application-service.yaml

apiVersion: v1
data:
  RDS_DB_NAME: todos
  RDS_HOSTNAME: mysql
  RDS_PORT: "3306"
  RDS_USERNAME: todos-user
kind: ConfigMap
metadata:
  name: todo-web-application-config
  namespace: default

cd /in28Minutes/git/kubernetes-crash-course/04-currency-exchange-microservice-basic 
mvn clean install
docker push in28min/currency-exchange:0.0.1-RELEASE
kubectl apply -f deployment.yaml
curl 34.67.103.178:8000/currency-exchange/from/USD/to/INR

kubectl create configmap currency-conversion --from-literal=YOUR_PROPERTY=value --from-literal=YOUR_PROPERTY_2=value2

kubectl autoscale deployment currency-exchange --min=1 --max=3 --cpu-percent=10 
kubectl get events
kubectl get hpa
kubectl get hpa -o yaml
kubectl get hpa -o yaml > 01-hpa.yaml
kubectl get hpa currency-exchange -o yaml > 01-hpa.yaml

kubectl set image deployment hello-world-rest-api --image=in28min/hello-world-rest-api:0.0.4-SNAPSHOT
kubectl apply -f ingress.yaml
kubectl get ingress
kubectl describe gateway-ingress
kubectl describe gateway gateway-ingress
kubectl describe ingress gateway-ingress
kubectl apply -f rbac.yml
 
docker push in28min/currency-conversion:0.0.5-RELEASE

kubectl create configmap currency-conversion --from-literal=YOUR_PROPERTY=value --from-literal=YOUR_PROPERTY_2=value2

kubectl describe configmap/currency-conversion


kubectl label namespace default istio-injection=enabled

kubectl get svc --namespace istio-system
kubectl apply -f 01-helloworld-deployment.yaml 
kubectl apply -f 02-creating-http-gateway.yaml 
kubectl apply -f 03-creating-virtualservice-external.yaml 
kubectl get svc --namespace istio-system
kubectl get svc istio-ingressgateway --namespace istio-system
kubectl scale deployment hello-world-rest-api --replicas=4
kubectl delete all -l app=hello-world-rest-api
kubectl apply -f 04-helloworld-multiple-deployments.yaml 
kubectl apply -f 05-helloworld-mirroring.yaml 
kubectl apply -f 06-helloworld-canary.yaml 
watch -n 0.1 curl 35.223.25.220/hello-world

gcloud container clusters get-credentials in28minutes-cluster-istio --zone us-central1-a --project solid-course-258105
kubectl create namespace istio-system
curl -L https://git.io/getLatestIstio | ISTIO_VERSION=1.2.2 sh -
ls istio-1.2.2
ls istio-1.2.2/install/kubernetes/helm/istio-init/files/crd*yaml
cd istio-1.2.2
for i in install/kubernetes/helm/istio-init/files/crd*yaml; do kubectl apply -f $i; done
helm template install/kubernetes/helm/istio --name istio --set global.mtls.enabled=false --set tracing.enabled=true --set kiali.enabled=true --set grafana.enabled=true --namespace istio-system > istio.yaml
kubectl apply -f istio.yaml
kubectl get pods --namespace istio-system
kubectl get services --namespace istio-system


docker push in28min/currency-exchange:3.0.0-RELEASE
kubectl apply -f deployment.yaml 
kubectl apply -f 11-istio-scripts-and-configuration/07-hw-virtualservice-all-services.yaml 
kubectl get secret -n istio-system kiali
kubectl create secret generic kiali -n istio-system --from-literal=username=admin --from-literal=passphrase=admin
kubectl get svc --namespace istio-system


gcloud container clusters get-credentials helm-cluster --zone us-central1-a --project solid-course-258105
helm init
kubectl get deploy,svc tiller-deploy -n kube-system
clear
unzip 12-helm.zip
ls helm-tiller.sh
chmod +x helm-tiller.sh

gcloud container clusters get-credentials helm-cluster --zone us-central1-a --project solid-course-258105
./helm-tiller.sh
cat helm-tiller.sh 
kubectl get deploy,svc tiller-deploy -n kube-system
helm install ./currency-exchange/ --name=currency-services
helm install ./currency-conversion/ --name=currency-services-1
helm install ./currency-conversion/ --name=currency-services-3 --debug --dry-run
helm history currency-services-1
helm upgrade currency-services-1 ./currency-conversion/
helm rollback currency-services-1 1
helm upgrade currency-services-1 ./currency-conversion/ --debug --dry-run
helm upgrade currency-services-1 ./currency-conversion/
helm history currency-services-1

```
## Notes

- Assume replicas = 200 maxUnavailable = 20% maxSurge = 20%. Max pods that can be unavailable during release = 20%(maxUnavailable) * 200 = 40. Max pods used during release = 200 + 20%(maxSurge) * 200 = 240
- updateMode: "Auto"
- Step 1 : Install all the Istio Custom Resource Definitions (CRD)
- Step 2 : Install Istio with Components for graphana, prometheus, tracing(jaeger), kiali as subcharts using Helm Charts.
- Fun Fact : istio.yaml has 18,000 lines of configuration!
- Step 3 : Verify Intallation of Istio
- Step 4 : Enable Adding Istio Side Cars in each Pod

## Diagrams

- Courtesy http://viz-js.com/

```
graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = TB
node[shape=record, width=2]
Level1[shape=record, width=7.0, style=filled,color="#D14D28", fontcolor=white]
edge [width=0]
graph [pad=".75", ranksep="0.05", nodesep="0.25"];
Block1,Block2,Block3[height=2]

Block1 -- Level1 [style=invis]
Block2 -- Level1 [style=invis]
Block3 -- Level1 [style=invis]

Level1[label=<Kubernetes>]
Block1[label=<Container Orchestration <BR/><BR/><BR/><BR/> <FONT POINT-SIZE="10">Manage 1000's of instances<BR/>1000's of microservices<BR/>Declaratively</FONT>>]
Block2[label=<Features <BR/><BR/> <FONT POINT-SIZE="10">Auto Scaling<BR/> Service Discovery <BR/> Load Balancing <BR/> Self Healing <BR/> Zero Downtime Deployments </FONT> 
>]
Block3[label=<Cloud Neutral <BR/><BR/><BR/><BR/><FONT POINT-SIZE="10">Standardized Platform <BR/> on any infrastructure</FONT>>]

}

graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = TB
node[shape=record, width=2]
Level1[shape=record, width=7.0, style=filled,color="#D14D28", fontcolor=white]
edge [width=0]
graph [pad=".75", ranksep="0.05", nodesep="0.25"];
Block1,Block2,Block3[height=2]

Block1 -- Level1 [style=invis]
Block2 -- Level1 [style=invis]
Block3 -- Level1 [style=invis]

Level1[label=<Docker>]
Block1[label=<Standaridized <BR/> Application Packaging <BR/><BR/><BR/> <FONT POINT-SIZE="10">Same packaging for <BR/>all types of applications</FONT>>]
Block2[label=<Features <BR/> <FONT POINT-SIZE="10">Language Neutral<BR/>  Cloud Neutral <BR/> Enables Standardization </FONT> 
>]
Block3[label=<Challenges <BR/><BR/><FONT POINT-SIZE="10"> 1000 Microservices<BR/> 1000 Instances</FONT>>]

}


graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = TB
node[shape=record, width=2, height=2]
Block11, Block12[width=1,height=1]
Block21, Block22[width=1,height=1]
Level1[shape=record, width=10, style=filled,color="#D14D28", fontcolor=white]
edge [width=0]
graph [pad=".75", ranksep="0.05", nodesep="0.25"];
Block1,Block2[ width=4.8]

Block1 -- Level1 [style=invis]
Block2 -- Level1 [style=invis]

Block11 -- Block1 [style=invis]
Block12 -- Block1 [style=invis]

Block21 -- Block2 [style=invis]
Block22 -- Block2 [style=invis]


Level1[label=<Deployment>]
Block1[label=<Replica Set 1 >]
Block2[label=<Replica Set 2 >]
Block11[label=<Pod Instance 1>]
Block12[label=<Pod Instance 2>]
Block21[label=<Pod Instance 1>]
Block22[label=<Pod Instance 2>]

}

graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = TB
node[shape=record, width=2]
Level1[shape=record, width=4.5, style=filled,color="#D14D28", fontcolor=white]
edge [width=0]
graph [pad=".75", ranksep="0.05", nodesep="0.25"];
Block1,Block2[height=2]

Block1 -- Level1 [style=invis]
Block2 -- Level1 [style=invis]

Level1[label=<Cluster>]
Block1[label=<Master Node(s) <BR/> <FONT POINT-SIZE="10">Manages Cluster</FONT>>]
Block2[label=<Worker Node(s) <BR/> <FONT POINT-SIZE="10">Run Your Applications</FONT>>]

}

graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = TB
node[shape=record, width=2, height=2]
Block11, Block12[width=1,height=1]
Block21, Block22[width=1,height=1]
Level1[shape=record, width=10, style=filled,color="#D14D28", fontcolor=white]
edge [width=0]
graph [pad=".75", ranksep="0.05", nodesep="0.25"];
Block1,Block2[ width=4.8]

Block1 -- Level1 [style=invis]
Block2 -- Level1 [style=invis]

Block11 -- Block1 [style=invis]
Block12 -- Block1 [style=invis]

Block21 -- Block2 [style=invis]
Block22 -- Block2 [style=invis]


Level1[label=<Node>]
Block1[label=<Pod 1 >]
Block2[label=<Pod 2 >]
Block11[label=<Container 1>]
Block12[label=<Container 2>]
Block21[label=<Container 3>]
Block22[label=<Container 4>]

}

graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = TB
node[shape=record, width=2]
Level1[shape=record, width=9.0, style=filled,color="#D14D28", fontcolor=white]
edge [width=0]
graph [pad=".75", ranksep="0.05", nodesep="0.25"];
Block1,Block2,Block3,Block4[height=2]

Block1 -- Level1 [style=invis]
Block2 -- Level1 [style=invis]
Block3 -- Level1 [style=invis]
Block4 -- Level1 [style=invis]

Level1[label=<Master Node>]
Block1[label=<API Server <BR/> <FONT POINT-SIZE="10">(kube-apiserver)</FONT>>]
Block2[label=<Distribute Database <BR/> <FONT POINT-SIZE="10">(etcd)</FONT>>]
Block3[label=<Scheduler  <BR/> <FONT POINT-SIZE="10">(kube-scheduler)</FONT>>]
Block4[label=<Controller Manager  <BR/> <FONT POINT-SIZE="10">(kube-controller-manager)</FONT>>]

}

graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = TB
node[shape=record, width=2]
Level1[shape=record, width=9.0, style=filled,color="#D14D28", fontcolor=white]
edge [width=0]
graph [pad=".75", ranksep="0.05", nodesep="0.25"];
Block1,Block2,Block3,Block4[height=2]

Block1 -- Level1 [style=invis]
Block2 -- Level1 [style=invis]
Block3 -- Level1 [style=invis]
Block4 -- Level1 [style=invis]

Level1[label=<Worker Node (or) Node>]
Block1[label=<Node Agent <BR/> <FONT POINT-SIZE="10">(kubelet)</FONT>>]
Block2[label=<Networking Component <BR/> <FONT POINT-SIZE="10">(kube-proxy)</FONT>>]
Block3[label=<Container Runtime  <BR/> <FONT POINT-SIZE="10">(CRI - docker, rkt etc)</FONT>>]
Block4[label=<PODS  <BR/> <FONT POINT-SIZE="10">(Multiple pods running <BR/> containers)</FONT>>]

}



graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = LR
node[shape=record, width=3]


ParentNode -- ChildNode1
ParentNode -- ChildNode2
ParentNode -- ChildNode3
ParentNode -- ChildNode4

ParentNode[label=<Master Node>]
ChildNode1[label=<API Server>];
ChildNode2[label=<Distributed Database - etcd>];
ChildNode3[label=<Scheduler>];
ChildNode4[label=<Controller Manager>];

}

graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = LR
node[shape=record, width=3]


ParentNode -- ChildNode1
ParentNode -- ChildNode2
ParentNode -- ChildNode3
ParentNode -- ChildNode4

ParentNode[label=<Worker Node (or) Node>]
ChildNode1[label=<Kubelet>];
ChildNode2[label=<Kube Proxy>];
ChildNode3[label=<Container Runtime>];
ChildNode4[label=<Pods>];

}


graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = LR
node[shape=record, width=1.6]


ParentNode1 -- ChildNode1
ParentNode2 -- ChildNode1
ChildNode1 -- ChildNode2

ParentNode1[label=<User>]
ParentNode2[label=<Service Consumer>]
ChildNode1[label=<Service>];
ChildNode2[label=<Pod>];

}

graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = TB
node[shape=record, width=2]


ParentNode1 -- ChildNode1
ChildNode1 -- Level2Child1
ChildNode1 -- Level2Child2
ParentNode1 -- ChildNode2
ChildNode2 -- Level2Child3
ChildNode2 -- Level2Child4

ParentNode1[label=<Node>]
ChildNode1[label=<Pod 1>]
Level2Child1[label=<Container 1>]
Level2Child2[label=<Container 2>]

ChildNode2[label=<Pod 2>]
Level2Child3[label=<Container 3>]
Level2Child4[label=<Container 4>]
}

graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = LR
node[shape=record, width=2]


Node1 -- Node2
Node2 -- Node3

Node1[label=<Project Code>]
Node2[label=<Docker Image>]
Node3[label=<Docker Repository>]
}

graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = LR
node[shape=record, width=2]


Node1 -- Node2
Node2 -- Node3
Node2 -- Node4

Node1[label=<Istio Gateway>]
Node2[label=<Istio Virtual Service <BR/> <FONT POINT-SIZE="10">Configure Routes</FONT>>]
Node3[label=<K8S Service A>]
Node4[label=<K8S Service B>]
}

graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = LR
node[shape=record, width=2]


Node1 -- Node3
Node3 -- Node2
Node2 -- Node4
Node2 -- Node5

Node1[label=<Istio Gateway>]
Node3[label=<Istio Virtual Service <BR/> <FONT POINT-SIZE="10">Configure routes to Services<BR/>Configure weights for Subsets</FONT>>]
Node2[label=<Destination Rule<BR/> <FONT POINT-SIZE="10">Map to different <BR/> Service Versions</FONT>>]
Node4[label=<K8S Service A V1>]
Node5[label=<K8S Service A V2>]
}

graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = LR
node[shape=record, width=2]


Node1 -- Node2
Node2 -- Node3

Node1[label=<Create Cluster>]
Node2[label=<Create Deployment>]
Node3[label=<Docker Repository>]
}

graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = TB
node[shape=record, width=3]

Clusters, LocalImages [height=1]

KubernetesClient -- Daemon
Daemon -- Clusters 
Daemon -- LocalImages
Daemon -- ImageRegistry

KubernetesClient[label=<Kubernetes Client>]
ImageRegistry[label=<Image Registry <BR /><FONT POINT-SIZE="10">nginx<BR />mysql<BR />eureka<BR />your-app<BR /><BR /></FONT>>];
Daemon[label=<Kubernetes Daemon>]


}


graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = TB
node[shape=record, width=2]
Hypervisor,HostOS, Hardware[shape=record, width=6.5, style=filled,color="#D14D28", fontcolor=white]
edge [width=0]
graph [pad=".75", ranksep="0.05", nodesep="0.25"];

Application1 -- Software1 [style=invis]
Application2 -- Software2 [style=invis]
Application3 -- Software3 [style=invis]

Software1 -- GuestOS1 [style=invis]
Software2 -- GuestOS2 [style=invis]
Software3 -- GuestOS3 [style=invis]
GuestOS1 -- Hypervisor [style=invis]
GuestOS2 -- Hypervisor [style=invis]
GuestOS3 -- Hypervisor [style=invis]
Hypervisor -- HostOS [style=invis]
HostOS -- Hardware [style=invis]

}


graph architecture {

node[style=filled,color="#59C8DE"]
//node [style=filled,color="#D14D28", fontcolor=white];
rankdir = TB
node[shape=record, width=2]
HostOS, CloudInfrastructure, KubernetesEngine[shape=record, width=6.5, style=filled,color="#D14D28", fontcolor=white]
edge [width=0]
graph [pad=".75", ranksep="0.05", nodesep="0.25"];
Container1,Container2,Container3[height=2]

Container1 -- KubernetesEngine [style=invis]
Container2 -- KubernetesEngine [style=invis]
Container3 -- KubernetesEngine [style=invis]
KubernetesEngine -- HostOS [style=invis]
HostOS -- CloudInfrastructure [style=invis]

}
```


## Next Steps

## Todo
---
- Go Declarative - Go YAML
- Use Helm
- Stay Cloud Neutral
> Kubernetes Best Pracises
---
- Naming Server
- Load Balancing
- Distributed Tracing 

> Spring Cloud - A Couple Of Years Ago
---
- spring-cloud-starter-kubernetes
- spring-cloud-gcp-starter-trace
- spring-cloud-gcp-starter-logging

> Spring Cloud - In the Cloud World
---
Update the step referring to Docker to refer to Appendix Section on Docker.
---
Google Console Keyboard Shortcuts
---
Debugging Problems in K8s
---
Billing
---
NodePort Example
---