# Kubernetes Crash Course with Spring Boot and Google Cloud


## Learn Kubernetes using Java, Spring Boot and Google Kubernetes Engine

Learn Kubernetes Fundamentals? Yes.   Create Clusters for Microservices? Yes.     Create Clusters for Full Stack Applications? Yes. Of Course. Hands-on? Of course.

Do you have ZERO experience with Kubernetes? No Problem.

Do you want to learn to create Clusters for Java Spring Boot Applications and Microservices using Kubernetes with an easy to learn, step by step approach?

Are you ready to learn about Kubernetes and take the next step in your programming career?

Do you want to join 300,000+ learners having Amazing Learning Experiences with in28Minutes?

Look No Further!

## Getting Started
- [Video - Docker in 5 Steps](https://youtu.be/Rt5G5Gj7RP0)
- [Video - Spring in Steps](https://www.youtube.com/watch?v=edgZo2g-LTM)
- [Video - Spring Boot in Steps](https://www.youtube.com/watch?v=pcdpk3Yd1EA)
- [Video - JPA/Hibernate in Steps](https://www.youtube.com/watch?v=MaI0_XdpdP8)

## Installation Guides

#### Required Tools

- Java 8+
- Eclipse - Recent Version - (Embedded Maven From Eclipse)
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

Architectures are moving towards Microservices and Cloud. Kubernetes makes it easy to containerize your applications and deploy them to the cloud.

Kubernetes is the No 1 Tool to orchestrate Docker containers. Learning Kubernetes would help you streamline your deployment processes and experiment easily with new frameworks and tools. 

In this handson course, we will use Docker and Kubernetes for a variety of Spring Boot Applications with Google Cloud using Google Kubernetes Engine:
- REST APIs - Hello World and Todo - Jar
- Todo Web Application War
- Full Stack Application with React and Spring Boot
- CCS and CES Microservices
- Eureka Naming Server and Zuul API Gateway

This course would be a perfect first step as an introduction to Kubernetes.

You will be using containerizing and deploying a variety of projects to Kubernetes Clusters. These projects are created with  React (Frontend Framework), Spring Boot (REST API Framework), Spring (Dependency Management), Spring Security (Authentication and Authorization - Basic and JWT), BootStrap (Styling Pages), Maven (dependencies management), Node (npm), Visual Studio Code (TypeScript IDE), Eclipse (Java IDE) and Tomcat Embedded Web Server. We will help you set up each one of these.

## What you'll learn
- You will Learn the Fundamentals of Kubernetes from Zero, no previous experience required
- You will learn the important Kubernetes Concepts
- You will learn the important Kubernetes commands  
- You will understand the Kubernetes Architecture
- You will learn to use Kubernetes to Manage Your Clusters
- You will learn the basics of Microservices
- You will Join 250,000 Learners having AMAZING LEARNING Experiences with in28Minutes

## Requirements
- You have an attitude to learn while having fun :)
- You have some programming experience with Java, Spring and Spring Boot
- You DO NOT need to have any experience with Kubernetes
- We will help you install Eclipse, Visual Studio Code, Git client, Docker Desktop and Node JS (for npm)

## Who is this course for
- You are a Java Spring Boot developer getting started with the Cloud
- You want to deploy your Java applications with Kubernetes
- You are a Java Developer and You are curious about Kubernetes
- You want to learn to play with Kubernetes and Spring Boot Microservices - Service Registry, Distributed Tracing and Zuul API Gateway

## Step By Step Details

### Introduction to the Course
- 00 Step 01 - Deploy Spring Boot Applications to Kubernetes - Course Overview
- 00 Step 02 - Deploy Spring Boot Applications to Kubernetes - Getting Started


```sh
for file in *; do mv "${file}" "${file//-/ }"; done
for file in *; do mv "${file}" "${file//   / - }"; done
for file in *; do mv "${file}" "${file//01 Step/Step}"; done
```

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


### Commands Executed during the course

```

docker run -p 8080:8080 in28min/hello-world-rest-api:0.0.1.RELEASE

 kubectl create deployment hello-world-rest-api --image=in28min/hello-world-rest-api:0.0.1.RELEASE
  505  kubectl expose deployment hello-world-rest-api --type=LoadBalancer --port=8080
  506  kubectl scale deployment hello-world-rest-api --replicas=3
  507  kubectl delete pod hello-world-rest-api-58ff5dd898-62l9d
  508  kubectl autoscale deployment hello-world-rest-api --max=10 --cpu-percent=70
  509  kubectl edit deployment hello-world-rest-api
  510  kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.2.RELEASE

1  gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105
    2  clear
    3  gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105
    4  kubectl
    5  clear
    6  kubectl create deployment todo-rest-api-h2 --image=  completion     Output shell completion code for the specified shell (bash or zsh)
    7  Other Commands:
    8  clear
    9  kubectl create deployment todo-rest-api-h2 --image=in28min/todo-rest-api-h2:1.0.0.RELEASE
   10  kubectl get deployments
   11  gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105
   12  kubectl create deployment todo-rest-api-h2 --image=in28min/todo-rest-api-h2:1.0.0.RELEASE
   13  gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105
   14  kubectl version
   15  kubectl create deployment hello-world-rest-api --image=in28min/hello-world-rest-api:1.0.0.RELEASE
   16  kubectl expose deployment --type=LoadBalancer --port=8080
   17  clear
   18  kubectl expose deployment hello-world-rest-api --type=LoadBalancer --port=8080
   19  clear
   20  gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105
   21  kubectl version
   22  kubectl create deployment hello-world-rest-api --image=in28min/hello-world-rest-api:0.0.1.RELEASE
   23  kubectl expose deployment hello-world-rest-api --type=LoadBalancer --port=8080
   24  kubectl get events
   25  kubectl get pods
   26  kubectl get replicaset
   27  kubectl get deployment
   28  kubectl get service
   29  clear
   30  kubectl get pods -o wide
   31  kubectl explain pods
   32  kubectl get pods -o wide
   33  clear
   34  kubectl get pods
   35  kubectl describe pod hello-world-rest-api-58ff5dd898-9trh2
   36  clear
   37  kubectl get replicasets
   38  kubectl get replicaset
   39  kubectl get rs
   40  kubectl get pods -o wide
   41  kubectl delete pods hello-world-rest-api-58ff5dd898-9trh2
   42  kubectl get pods -o wide
   43  kubectl scale deployment hello-world-rest-api --replicas=3
   44  kubectl get pods
   45  kubectl get replicaset
   46  kubectl get events
   47  kubectl get events --sort.by=.metadata.creationTimestamp
   48  kubectl get events --sort-by=.metadata.creationTimestamp
   49  kubectl explain replicaset
   50  clear
   51  kubectl get rs
   52  kubectl get rs -o wide
   53  kubectl set image deployment hello-world-rest-api hello-world-rest-api=DUMMY_IMAGE:TEST
   54  kubectl get rs -o wide
   55  kubectl get pods
   56  kubectl describe pod hello-world-rest-api-85995ddd5c-msjsm
   57  clear
   58  kubectl get events --sort-by=.metadata.creationTimestamp
   59  kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.2.RELEASE
   60  kubectl get pods
   61  kubectl get res
   62* kubectl get even
   63  kubectl get events --sort-by=.metadata.creationTimestamp
   64  clear
   65  kubectl get pods -o wide
   66  kubectl delete pod hello-world-rest-api-67c79fd44f-n6c7l
   67  kubectl get pods -o wide
   68  kubectl delete pod hello-world-rest-api-67c79fd44f-8bhdt
   69  kubectl get pods -o wide
   70  clear
   71  kubectl get services
   72  kubectl get componentstatuses
   73  kubectl get pods --all-namespaces
   74  history

watch -n 0.1 curl 35.232.144.134:8080/hello-world

   gcloud init
  502  clear
  503  gcloud auth login
  504  kubectl version
  505  kubectl version
  506  gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105
  507  kubectl version
  508  clear
  509  kubectl set image deployment hello-world-rest-api --image=in28min/hello-world-rest-api:0.0.4-SNAPSHOT
  510  kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.4-SNAPSHOT
  511  kubectl get pods
  512  kubectl get pods
  513  clear
  514  kubectl rollout history deployment hello-world-rest-api
  515  kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.4-SNAPSHOT --record
  516  kubectl rollout history deployment hello-world-rest-api
  517  kubectl rollout status deployment hello-world-rest-api
  518  kubectl rollout undo deployment hello-world-rest-api --to-revision=3
  519  kubectl rollout status deployment hello-world-rest-api
  520  kubectl rollout undo deployment hello-world-rest-api --to-revision=3
  521  kubectl rollout status deployment hello-world-rest-api
  522  kubectl rollout history deployment hello-world-rest-api
  523  kubectl get pods
  524  kubectl logs hello-world-rest-api-67c79fd44f-d6q9z
  525  kubectl logs hello-world-rest-api-67c79fd44f-d6q9z -f
  526  clear
  527  kubectl get deployment hello-world-rest-api
  528  kubectl get deployment hello-world-rest-api -o wide
  529  kubectl get deployment hello-world-rest-api -o yaml
  530  kubectl get deployment hello-world-rest-api -o yaml > deployment.yaml
  531  kubectl get service hello-world-rest-api -o yaml
  532  kubectl get service hello-world-rest-api -o yaml > service.yaml
  533  clear
  534  kubectl apply -f deployment.yaml
  535  kubectl get pods
  536  kubectl delete all -l app=hello-world-rest-api
  537  kubectl get all
  538  kubectl apply -f deployment.yaml
  539  kubectl get all
  540  kubectl get all
  541  clear
  542  kubectl diff -f deployment.yaml 
  543  kubectl apply -f deployment.yaml --trial-run
  544  kubectl apply -f deployment.yaml --dry-run
  545  kubectl get all
  546  clear
  547  kubectl apply -f deployment.yaml 
  548  kubectl get pods
  549  kubectl apply -f deployment.yaml 
  550  kubectl get pods
  551  kubectl get pods
  552  kubectl get pods
  553  kubectl get pods
  554  kubectl apply -f deployment.yaml 
  555  kubectl delete all -l app=hello-world-rest-api
  556  kubectl apply -f deployment.yaml 
  557  kubectl apply -f deployment.yaml 
  558  kubectl get all
  559  kubectl get all
  560  kubectl apply -f deployment.yaml 
  561  kubectl get pods
  562  kubectl get rs
  563  kubectl delete pod hello-world-rest-api-4n2cg
  564  kubectl get rs
  565  kubectl get pods
  566  kubectl delete pod hello-world-rest-api-pvnpl
  567  kubectl get pods
  568  kubectl delete all -l app=hello-world-rest-api
  569  clear
  570  kubectl apply -f deployment.yaml 
  571  kubectl get pods
  572  kubectl get all
  573  kubectl get pods -o wide
  574  clear
  575  kubectl get all -o wide
  576  kubectl get all -o wide
  577  kubectl apply -f deployment.yaml 
  578  kubectl apply -f deployment.yaml 

581  cd ../02-todo-web-application-h2/
  582  pwd
  583  mvn clean install
  584  docker push in28min/todo-web-application-h2:0.0.1-SNAPSHOT
  585  clear
  586  kubectl get all
  587  kubectl delete all -l app=hello-world-rest-api
  588  kubectl get all
  589  kubectl apply -f deployment.yaml 
  590  kubectl get all
  591  kubectl get all
  592  clear
  593  kubectl get pods
  594  kubectl get pods --all-namespaces
  595  kubectl get pods -l app=todo-web-application-h2
  596  kubectl get pods -l app=todo-web-application-h2 --all-namespaces
  597  kubectl get services --all-namespaces
  598  kubectl get services --all-namespaces --sort-by=.spec.type
  599  kubectl get services --all-namespaces --sort-by=.metadata.name
  600  clear
  601  kubectl cluster-info
  602  kubectl top node
  603  kubectl top pod
  604  clear
  605  kubectl get services
  606  kubectl get svc
  607  kubectl get ev
  608  kubectl get rs
  609  kubectl get ns
  610  kubectl get nodes
  611  kubectl get no
  612  kubectl get po
  613  docker run --detach --env MYSQL_ROOT_PASSWORD=dummypassword --env MYSQL_USER=todos-user --env MYSQL_PASSWORD=dummytodos --env MYSQL_DATABASE=todos --name mysql --publish 3306:3306 mysql:5.7
  614  cd ../03-todo-web-application-mysql/
  615  clear
  616  pwd
  617  mvn clean install
  618  docker run -p 8080:8080 in28min/todo-web-application-mysql:0.0.1-SNAPSHOT
  619  docker run -p 8080:8080 --link=mysql --env RDS_HOSTNAME=mysql in28min/todo-web-application-mysql:0.0.1-SNAPSHOT
  620  docker-compose up
  621  clear
  622  docker-compose --version
  623  docker container ls
  624  docker container stop 5d3bc64e2c07
  625  docker container rm 5d3bc64e2c07
  626  pwd
  627  ls
  628  docker-compose up
  629  clear
  630  brew install kompose
  631  clear
  632  ls
  633  kompose convert
  634  kubectl get all
  635  kubectl delete all -l app=todo-web-application-h2
  636  clear
  637  ls
  638  ls *.yaml
  639  clear
  640  clear
  641  ls *.yaml
  642  kubectl apply -f mysql-database-data-volume-persistentvolumeclaim.yaml,mysql-deployment.yaml,mysql-service.yaml
  643  kubectl get status
  644  kubectl get all
  645* kubectl delete all 
  646  kubectl get endpoints
  647  kubectl get all
  648  kubectl get nodes
  649  kubectl get nodes -o wide
  650  kubectl get pods
  651  kubectl get pods -o wide
  652  kubectl get all
  653  kubectl delete deployment.apps/mysql
  654  kubectl delete replicaset.apps/mysql-5ccbbbdcd8
  655  kubect get all
  656  kubectl get all
  657  kubectl delete service/mysql
  658  clear
  659  ls
  660  clear
  661  ls *.yaml
  662  kubectl apply -f mysql-database-data-volume-persistentvolumeclaim.yaml,mysql-deployment.yaml,mysql-service.yaml
  663  kubectl get all
  664  kubectl get svc
  665  kubectl get svc --watch
  666  clear
  667  ls *.yaml
  668  kubectl apply -f todo-web-application-deployment.yaml,todo-web-application-service.yaml
  669  kubectl get all
  670  docker push in28min/todo-web-application-mysql:0.0.1-SNAPSHOT
  671  kubectl get all
  672  kubectl delete pod/todo-web-application-b65cc44d9-jfmbj
  673  kubectl get all
  674  kubectl logs todo-web-application-b65cc44d9-7h9pr -f
  675  kubectl get svc
  676  kubectl apply -f mysql-service.yaml
  677  clear
  678  kubectl get all
  679  history| grep "kubectl delete"
  680  kubectl delete -f mysql-service.yaml
  681  kubectl delete -f mysql-database-data-volume-persistentvolumeclaim.yaml,mysql-deployment.yaml
  682  kubectl delete -f todo-web-application-deployment.yaml,todo-web-application-service.yaml
  683  kubectl get all
  684  kubectl apply -f mysql-database-data-volume-persistentvolumeclaim.yaml,mysql-deployment.yaml,mysql-service.yaml
  685  kubectl get all
  686  kubectl apply -f todo-web-application-deployment.yaml,todo-web-application-service.yaml
  687  kubectl get all
  688  kubectl get all
  689  kubectl get pv
  690  kubectl get pvc
  691  kubectl describe pod/mysql-5ccbbbdcd8-5zjqg 
  692  clear
  693  kubectl get pv
  694  kubectl get pvc
  695  clear
  696  kubectl get pv
  697  kubectl get pvc
  698  clear
  699  kubectl create configmap todo-web-application-config --from-literal=RDS_DB_NAME=todos
  700  kubectl get configmap todo-web-application-config
  701  kubectl describe configmap/todo-web-application-config
  702  kubectl apply -f todo-web-application-deployment.yaml 
  703  kubectl get pods
  704  kubectl edit configmap/todo-web-application-config
  705  kubectl scale deployment todo-web-application --replicas=0
  706  kubectl scale deployment todo-web-application --replicas=1
  707  kubectl get pods
  708  kubectl logs todo-web-application-59f6776c94-9j77f -f
  709  kubectl edit configmap/todo-web-application-config
  710  kubectl apply -f todo-web-application-deployment.yaml 
  711  kubectl get pods
  712  kubectl logs todo-web-application-644d56758c-9sd7w -f
  713  kubectl edit configmap todo-web-application-config
  714  kubectl scale deployment todo-web-application --replicas=0
  715  kubectl scale deployment todo-web-application --replicas=1
  716  kubectl get pods
  717  kubectl logs todo-web-application-644d56758c-qpfws -f
  718  clear
  719  kubectl create secret generic todo-web-application-secrets --from-literal=RDS_PASSWORD=dummytodos
  720  kubectl get secret/todo-web-application-secrets
  721  kubectl describe secret/todo-web-application-secrets
  722  kubectl apply -f todo-web-application-deployment.yaml 
  723  kubectl get pods
  724  kubectl logs todo-web-application-5cc485458b-sqbtt -f
  725  clear
  726  kubectl delete service mysql
  727  kubectl apply -f mysql-service.yaml 
  728  kubectl get services
  729  kubectl get all
  730  kubectl edit configmap todo-web-application-config
  731  clear
  732  ls
  733  clear
  734  ls *.yaml
  735  kubectl delete -f mysql-database-data-volume-persistentvolumeclaim.yaml,mysql-deployment.yaml,mysql-service.yaml,todo-web-application-deployment.yaml,todo-web-application-service.yaml

apiVersion: v1
data:
  RDS_DB_NAME: todos
  RDS_HOSTNAME: mysql
  RDS_PORT: "3306"
  RDS_USERNAME: todos-user
kind: ConfigMap
metadata:
  creationTimestamp: "2019-11-09T13:09:16Z"
  name: todo-web-application-config
  namespace: default
  resourceVersion: "702668"
  selfLink: /api/v1/namespaces/default/configmaps/todo-web-application-config
  uid: 21cb4b10-02f2-11ea-981b-42010a8000df

501  cd /in28Minutes/git/kubernetes-crash-course/04-currency-exchange-microservice-basic 
  502  mvn clean install
  503  clear
  504  pwd
  505  mvn clean install
  506  clear
  507  pwd
  508  mvn clean install
  509  miner f39fc9d0cf82
  519  docker push in28min/currency-exchange:0.0.1-RELEASE
  520  kubectl apply -f deployment.yaml
  521  kubectl get all
  522  kubectl get all
  523  kubectl get all
  524  kubectl logs pod/currency-exchange-578ddd7b8d-b8pjl 
  525  kubectl logs pod/currency-exchange-578ddd7b8d-b8pjl -f
  526  kubectl get all
  527  curl 34.67.103.178:8000/currency-exchange/from/USD/to/INR
  528  clear
  529  curl 34.67.103.178:8000/currency-exchange/from/USD/to/INR|json
  530  clear
  531  curl 34.67.103.178:8000/currency-exchange/from/USD/to/IN
  532  curl 34.67.103.178:8000/currency-exchange/from/USD/to/INR
  533  clear
  534  curl 34.67.103.178:8000/currency-exchange/from/USD/to/INR
  535  curl 34.67.103.178:8000/currency-exchange/from/USD/to/INR
  536  clear
  537  kubectl get pods
  538  kubectl logs currency-exchange-578ddd7b8d-b8pjl -f
  kubectl create configmap currency-conversion --from-literal=YOUR_PROPERTY=value --from-literal=YOUR_PROPERTY_2=value2
  539  kubectl get all
  540  kubectl get svc
  541  kubectl apply -f deployment.yaml 
  542  kubectl get services
  543  gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105
  544  kubectl apply -f deployment.yaml 
  545  kubectl get all
  546  clear
  547  kubectl get pods
  548  kubectl apply -f deployment.yaml 
  549  kubectl get pods
  550  kubectl get pods
  551  kubectl get pods
  552  clear
  553  kubectl get pods
  554  clear
  555  kubectl get pods
  556  kubectl get pods
  557  kubectl get pods
  558  kubectl get pods
  559  clear
  560  kubectl get pods
  561  kubectl get pods
  562  kubectl get pods
  563  clear
  564  kubectl get pods
  565  kubectl get pods
  566  kubectl get pods
  567  kubectl get pods
  568  kubectl logs currency-exchange-57cd8f789b-lfhh6 -f
  569  kubectl apply -f deployment.yaml 
  570  kubectl get pods
  571  kubectl logs currency-exchange-dfbbd955b-x9kzc -f
  572  kubectl get pods
  573  kubectl get pods
  574  kubectl get pods
  575  kubectl get pods
  576  kubectl get pods
  577  kubectl get pods
  578  kubectl top pods
  579  kubectl top pods
  580  kubectl top pods
  581  kubectl top pods
  582  kubectl top pods
  583  kubectl top pods
  584  kubectl top pods
  585  kubectl top pods
  586  kubectl top pods
  587  kubectl top pods
  588  clear
  589  kubectl autoscale deployment currency-exchange --min=1 --max=3 --cpu-percent=10 
  590  kubectl get pods
  591  kubectl get pods
  592  kubectl get events
  593* 
  594  kubectl get hpa
  595  kubectl get hpa -o yaml
  596  kubectl get hpa -o yaml > 01-hpa.yaml
  597  kubectl get hpa currency-exchange -o yaml > 01-hpa.yaml
  507  kubectl get pods
  508  kubectl get pods
  509  kubectl get pods
  510  kubectl get svcs
  511  kubectl get services
  512  kubectl get svc
  513  kubectl get svc
  514  kubectl get svc
  515  kubectl get svc --watch
   83  exec -l $SHELL
   84  gcloud init
   85  clear
   86  gcloud auth login
   87  kubectl version
   88  kubectl version
   89  gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105
   90  kubectl version
   91  clear
   92  kubectl set image deployment hello-world-rest-api --image=in28min/hello-world-rest-api:0.0.4-SNAPSHOT
   93  kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.4-SNAPSHOT
   94  kubectl get pods
   95  kubectl get pods
   96  clear
   97  kubectl rollout history deployment hello-world-rest-api
   98  kubectl set image deployment hello-world-rest-api hello-world-rest-api=in28min/hello-world-rest-api:0.0.4-SNAPSHOT --record
   99  kubectl rollout history deployment hello-world-rest-api
  100  kubectl rollout status deployment hello-world-rest-api
  101  kubectl rollout undo deployment hello-world-rest-api --to-revision=3
  102  kubectl rollout status deployment hello-world-rest-api
  103  kubectl rollout undo deployment hello-world-rest-api --to-revision=3
  104  kubectl rollout status deployment hello-world-rest-api
  105  kubectl rollout history deployment hello-world-rest-api
  106  kubectl get pods
  107  kubectl logs hello-world-rest-api-67c79fd44f-d6q9z
  108  kubectl logs hello-world-rest-api-67c79fd44f-d6q9z -f
  109  clear
  110  kubectl get deployment hello-world-rest-api
  111  kubectl get deployment hello-world-rest-api -o wide
  112  kubectl get deployment hello-world-rest-api -o yaml
  113  kubectl get deployment hello-world-rest-api -o yaml > deployment.yaml
  114  kubectl get service hello-world-rest-api -o yaml
  115  kubectl get service hello-world-rest-api -o yaml > service.yaml
  116  clear
  117  kubectl apply -f deployment.yaml
  118  kubectl get pods
  119  kubectl delete all -l app=hello-world-rest-api
  120  kubectl get all
  121  kubectl apply -f deployment.yaml
  122  kubectl get all
  123  kubectl get all
  124  clear
  125  kubectl diff -f deployment.yaml 
  126  kubectl apply -f deployment.yaml --trial-run
  127  kubectl apply -f deployment.yaml --dry-run
  128  kubectl get all
  129  clear
  130  kubectl apply -f deployment.yaml 
  131  kubectl get pods
  132  kubectl apply -f deployment.yaml 
  133  kubectl get pods
  134  kubectl get pods
  135  kubectl get pods
  136  kubectl get pods
  137  kubectl apply -f deployment.yaml 
  138  kubectl delete all -l app=hello-world-rest-api
  139  kubectl apply -f deployment.yaml 
  140  kubectl apply -f deployment.yaml 
  141  kubectl get all
  142  kubectl get all
  143  kubectl apply -f deployment.yaml 
  144  kubectl get pods
  145  kubectl get rs
  146  kubectl delete pod hello-world-rest-api-4n2cg
  147  kubectl get rs
  148  kubectl get pods
  149  kubectl delete pod hello-world-rest-api-pvnpl
  150  kubectl get pods
  151  kubectl delete all -l app=hello-world-rest-api
  152  clear
  153  kubectl apply -f deployment.yaml 
  154  kubectl get pods
  155  kubectl get all
  156  kubectl get pods -o wide
  157  clear
  158  kubectl get all -o wide
  159  kubectl get all -o wide
  160  kubectl apply -f deployment.yaml 
  161  kubectl apply -f deployment.yaml 
  162  history
  163  clear
  164  cd ../02-todo-web-application-h2/
  165  pwd
  166  mvn clean install
  167  docker push in28min/todo-web-application-h2:0.0.1-SNAPSHOT
  168  clear
  169  kubectl get all
  170  kubectl delete all -l app=hello-world-rest-api
  171  kubectl get all
  172  kubectl apply -f deployment.yaml 
  173  kubectl get all
  174  kubectl get all
  175  clear
  176  kubectl get pods
  177  kubectl get pods --all-namespaces
  178  kubectl get pods -l app=todo-web-application-h2
  179  kubectl get pods -l app=todo-web-application-h2 --all-namespaces
  180  kubectl get services --all-namespaces
  181  kubectl get services --all-namespaces --sort-by=.spec.type
  182  kubectl get services --all-namespaces --sort-by=.metadata.name
  183  clear
  184  kubectl cluster-info
  185  kubectl top node
  186  kubectl top pod
  187  clear
  188  kubectl get services
  189  kubectl get svc
  190  kubectl get ev
  191  kubectl get rs
  192  kubectl get ns
  193  kubectl get nodes
  194  kubectl get no
  195  kubectl get po
  196  docker run --detach --env MYSQL_ROOT_PASSWORD=dummypassword --env MYSQL_USER=todos-user --env MYSQL_PASSWORD=dummytodos --env MYSQL_DATABASE=todos --name mysql --publish 3306:3306 mysql:5.7
  197  cd ../03-todo-web-application-mysql/
  198  clear
  199  pwd
  200  mvn clean install
  201  docker run -p 8080:8080 in28min/todo-web-application-mysql:0.0.1-SNAPSHOT
  202  docker run -p 8080:8080 --link=mysql --env RDS_HOSTNAME=mysql in28min/todo-web-application-mysql:0.0.1-SNAPSHOT
  203  docker-compose up
  204  clear
  205  docker-compose --version
  206  docker container ls
  207  docker container stop 5d3bc64e2c07
  208  docker container rm 5d3bc64e2c07
  209  pwd
  210  ls
  211  docker-compose up
  212  clear
  213  brew install kompose
  214  clear
  215  ls
  216  kompose convert
  217  kubectl get all
  218  kubectl delete all -l app=todo-web-application-h2
  219  clear
  220  ls
  221  ls *.yaml
  222  clear
  223  clear
  224  ls *.yaml
  225  kubectl apply -f mysql-database-data-volume-persistentvolumeclaim.yaml,mysql-deployment.yaml,mysql-service.yaml
  226  kubectl get status
  227  kubectl get all
  228  kubectl delete all 
  229  kubectl get endpoints
  230  kubectl get all
  231  kubectl get nodes
  232  kubectl get nodes -o wide
  233  kubectl get pods
  234  kubectl get pods -o wide
  235  kubectl get all
  236  kubectl delete deployment.apps/mysql
  237  kubectl delete replicaset.apps/mysql-5ccbbbdcd8
  238  kubect get all
  239  kubectl get all
  240  kubectl delete service/mysql
  241  clear
  242  ls
  243  clear
  244  ls *.yaml
  245  kubectl apply -f mysql-database-data-volume-persistentvolumeclaim.yaml,mysql-deployment.yaml,mysql-service.yaml
  246  kubectl get all
  247  kubectl get svc
  248  kubectl get svc --watch
  249  clear
  250  ls *.yaml
  251  kubectl apply -f todo-web-application-deployment.yaml,todo-web-application-service.yaml
  252  kubectl get all
  253  docker push in28min/todo-web-application-mysql:0.0.1-SNAPSHOT
  254  kubectl get all
  255  kubectl delete pod/todo-web-application-b65cc44d9-jfmbj
  256  kubectl get all
  257  kubectl logs todo-web-application-b65cc44d9-7h9pr -f
  258  kubectl get svc
  259  kubectl apply -f mysql-service.yaml
  260  clear
  261  kubectl get all
  262  history| grep "kubectl delete"
  263  kubectl delete -f mysql-service.yaml
  264  kubectl delete -f mysql-database-data-volume-persistentvolumeclaim.yaml,mysql-deployment.yaml
  265  kubectl delete -f todo-web-application-deployment.yaml,todo-web-application-service.yaml
  266  kubectl get all
  267  kubectl apply -f mysql-database-data-volume-persistentvolumeclaim.yaml,mysql-deployment.yaml,mysql-service.yaml
  268  kubectl get all
  269  kubectl apply -f todo-web-application-deployment.yaml,todo-web-application-service.yaml
  270  kubectl get all
  271  kubectl get all
  272  kubectl get pv
  273  kubectl get pvc
  274  kubectl describe pod/mysql-5ccbbbdcd8-5zjqg 
  275  clear
  276  kubectl get pv
  277  kubectl get pvc
  278  clear
  279  kubectl get pv
  280  kubectl get pvc
  281  clear
  282  kubectl create configmap todo-web-application-config --from-literal=RDS_DB_NAME=todos
  283  kubectl get configmap todo-web-application-config
  284  kubectl describe configmap/todo-web-application-config
  285  kubectl apply -f todo-web-application-deployment.yaml 
  286  kubectl get pods
  287  kubectl edit configmap/todo-web-application-config
  288  kubectl scale deployment todo-web-application --replicas=0
  289  kubectl scale deployment todo-web-application --replicas=1
  290  kubectl get pods
  291  kubectl logs todo-web-application-59f6776c94-9j77f -f
  292  kubectl edit configmap/todo-web-application-config
  293  kubectl apply -f todo-web-application-deployment.yaml 
  294  kubectl get pods
  295  kubectl logs todo-web-application-644d56758c-9sd7w -f
  296  kubectl edit configmap todo-web-application-config
  297  kubectl scale deployment todo-web-application --replicas=0
  298  kubectl scale deployment todo-web-application --replicas=1
  299  kubectl get pods
  300  kubectl logs todo-web-application-644d56758c-qpfws -f
  301  clear
  302  kubectl create secret generic todo-web-application-secrets --from-literal=RDS_PASSWORD=dummytodos
  303  kubectl get secret/todo-web-application-secrets
  304  kubectl describe secret/todo-web-application-secrets
  305  kubectl apply -f todo-web-application-deployment.yaml 
  306  kubectl get pods
  307  kubectl logs todo-web-application-5cc485458b-sqbtt -f
  308  clear
  309  kubectl delete service mysql
  310  kubectl apply -f mysql-service.yaml 
  311  kubectl get services
  312  kubectl get all
  313  kubectl edit configmap todo-web-application-config
  314  clear
  315  ls
  316  clear
  317  ls *.yaml
  318  kubectl delete -f mysql-database-data-volume-persistentvolumeclaim.yaml,mysql-deployment.yaml,mysql-service.yaml,todo-web-application-deployment.yaml,todo-web-application-service.yaml
  319  history
  320  exit
  321  watch -n 0.1 curl http://34.96.78.210/currency-exchange/from/USD/to/INR
  322  cd /in28Minutes/git/kubernetes-crash-course/05-currency-conversion-microservice-basic 
  323  mvn clean install
  324  clear
  325  pwd
  326  mvn clean insta
  327  mvn clean install
  328  clear
  329  pwd
  330  mvn clean install
  331  docker push in28min/currency-conversion:0.0.1-RELEASE
  332  kubectl apply -f deployment.yaml 
  333  kubectl get all
  334  kubectl logs pod/currency-conversion-65cdf4df86-qcb6f -f
  335  mvn clean install
  336  docker push in28min/currency-conversion:0.0.2-RELEASE
  337  kubectl apply -f deployment.yaml 
  338  kubectl get pods
  339  kubectl get pods
  340  kubectl logs currency-conversion-699869557d-2jzts -f
  341  kubectl get pods
  342  kubectl get all -o wide
  343  kubectl get rs -o wide
  344  clear
  345  kubectl get svc
  346  pwd
  347  ls
  348  kubectl apply -f ingress.yaml
  349  kubectl get ingress
  350  kubectl describe gateway-ingress
  351  kubectl describe gateway gateway-ingress
  352  kubectl describe ingress gateway-ingress
  353  kubectl  ingress
  354  kubectl describe ingress gateway-ingress
  355  clear
  356  ls
  357  kubectl apply -f rbac.yml
  358  kubectl delete -f rbac.yml
  359  kubectl delete -f ingress.yaml 
  360  kubectl get services
  361  clear
  362  kubectl get services
  363  kubectl apply -f ingress.yaml 
  364  kubectl get services
  365  kubectl get ingress
  366  kubectl apply -f deployment.yaml 
  367  kubectl apply -f deployment.yaml,gateway.yaml
  368  gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105
  369  ls
  370  kubectl apply -f deployment.yaml,ingress.yaml
  371  kubectl get ingress
  372  kubectl get pods
  373  clear
  374  kubectl get services
  375  pwd
  376  cd ../06-currency-conversion-microservice-cloud/
  377  mvn clean install
  378  mvn clean install
  379  docker push in28min/currency-conversion:0.0.5-RELEASE
  380  clear
  381  pwd
  382  kubectl apply -f deployment.yaml
  383  kubectl get pods
  384  kubectl get serviceaccount
  385  kubectl get serviceaccount
  386  kubectl apply -f 02-rbac.yml 
  387  clear
  388  kubectl create configmap currency-conversion --from-literal=YOUR_PROPERTY=value --from-literal=YOUR_PROPERTY_2=value2
  389  kubectl describe configmap/currency-conversion
  390  kubectl get pods
  391  kubectl logs currency-conversion-6ccdd9766b-8whhv -f
  392  clear
  393  kubectl scale deployment currency-conversion --replicas=0
  394  kubectl scale deployment currency-conversion --replicas=1
  395  kubectl get pods
  396  kubectl logs currency-conversion-6ccdd9766b-d5c72 -f 
  397  clear
  398  cd /in28Minutes/git/kubernetes-crash-course/04-currency-exchange-microservice-basic 
  399  mvn clean install
  400  clear
  401  pwd
  402  mvn clean install
  403  clear
  404  pwd
  405  mvn clean install
  406  miner f39fc9d0cf82
  407  [INFO]  ---> 1ec056fbf00c
  408  [INFO] Successfully built 1ec056fbf00c
  409  [INFO] Successfully tagged in28min/currency-exchange:0.0.1-RELEASE
  410  [INFO] 
  411  [INFO] Detected build of image with id 1ec056fbf00c
  412  [INFO] Building jar: /in28Minutes/git/kubernetes-crash-course/04-currency-exchange-microservice-basic/target/currency-exchange-docker-info.jar
  413  [INFO] Successfully built in28min/currency-exchange:0.0.1-RELEASE
  414  [INFO] 
  415  [INFO] --- maven-install-plugin:2.5.2:install (default-install) @ 04-currency-exchange-basic ---
  416  docker push in28min/currency-exchange:0.0.1-RELEASE
  417  kubectl apply -f deployment.yaml
  418  kubectl get all
  419  kubectl get all
  420  kubectl get all
  421  kubectl logs pod/currency-exchange-578ddd7b8d-b8pjl 
  422  kubectl logs pod/currency-exchange-578ddd7b8d-b8pjl -f
  423  kubectl get all
  424  curl 34.67.103.178:8000/currency-exchange/from/USD/to/INR
  425  clear
  426  curl 34.67.103.178:8000/currency-exchange/from/USD/to/INR|json
  427  clear
  428  curl 34.67.103.178:8000/currency-exchange/from/USD/to/IN
  429  curl 34.67.103.178:8000/currency-exchange/from/USD/to/INR
  430  clear
  431  curl 34.67.103.178:8000/currency-exchange/from/USD/to/INR
  432  curl 34.67.103.178:8000/currency-exchange/from/USD/to/INR
  433  clear
  434  kubectl get pods
  435  kubectl logs currency-exchange-578ddd7b8d-b8pjl -f
  436  kubectl get all
  437  kubectl get svc
  438  kubectl apply -f deployment.yaml 
  439  kubectl get services
  440  gcloud container clusters get-credentials in28minutes-cluster --zone us-central1-a --project solid-course-258105
  441  kubectl apply -f deployment.yaml 
  442  kubectl get all
  443  clear
  444  kubectl get pods
  445  kubectl apply -f deployment.yaml 
  446  kubectl get pods
  447  kubectl get pods
  448  kubectl get pods
  449  clear
  450  kubectl get pods
  451  clear
  452  kubectl get pods
  453  kubectl get pods
  454  kubectl get pods
  455  kubectl get pods
  456  clear
  457  kubectl get pods
  458  kubectl get pods
  459  kubectl get pods
  460  clear
  461  kubectl get pods
  462  kubectl get pods
  463  kubectl get pods
  464  kubectl get pods
  465  kubectl logs currency-exchange-57cd8f789b-lfhh6 -f
  466  kubectl apply -f deployment.yaml 
  467  kubectl get pods
  468  kubectl logs currency-exchange-dfbbd955b-x9kzc -f
  469  kubectl get pods
  470  kubectl get pods
  471  kubectl get pods
  472  kubectl get pods
  473  kubectl get pods
  474  kubectl get pods
  475  kubectl top pods
  476  kubectl top pods
  477  kubectl top pods
  478  kubectl top pods
  479  kubectl top pods
  480  kubectl top pods
  481  kubectl top pods
  482  kubectl top pods
  483  kubectl top pods
  484  kubectl top pods
  485  clear
  486  kubectl autoscale deployment currency-exchange --min=1 --max=3 --cpu-percent=10 
  487  kubectl get pods
  488  kubectl get pods
  489  kubectl get events
  490  kubectl get hpa
  491  kubectl get hpa -o yaml
  492  kubectl get hpa -o yaml > 01-hpa.yaml
  493  kubectl get hpa currency-exchange -o yaml > 01-hpa.yaml
  494  clear
  495  history
  496  kubectl get cm
  497  kubectl get cm currency-conversion > 00-configmap-currency-conversion.yaml
  498  kubectl get cm currency-conversion -o yaml> 00-configmap-currency-conversion.yaml
  499  exit
  500  cd /in28Minutes/git/kubernetes-crash-course/11-istio-scripts-and-configuration 
  501  take-step-backup.sh backup
  502  gcloud container clusters get-credentials in28minutes-cluster-istio --zone us-central1-a --project solid-course-258105
  503  pwd
  504  ls
  505  kubectl apply -f 01-helloworld-deployment.yaml 
  506  kubectl get pods
  507  kubectl get all -o wide
  508  kubectl describe pod hello-world-rest-api-6845c5bbcd-bhjv2
  509  kubectl label namespace default istio-injection=enabled
  510  kubectl apply -f 01-helloworld-deployment.yaml 
  511  kubectl get pods
  512  kubectl get pods
  513  kubectl get pods
  514  kubectl get pods
  515  kubectl get pods
  516  kubectl get all
  517  kubectl apply -f 01-helloworld-deployment.yaml
  518  kubectl get all
  519  kubectl delete -f 01-helloworld-deployment.yaml
  520  kubectl apply -f 01-helloworld-deployment.yaml
  521  kubectl get all
  522  kubectl get pods --watch
  523  kubectl apply -f 01-helloworld-deployment.yaml
  524  kubectl get pods --watch
  525  pwd
  526  cd ../09-currency-exchange-microservice-istio/11-istio-scripts-and-configuration/
  527  kubectl apply -f 01-helloworld-deployment.yaml
  528  kubectl get pods
  529  kubectl get pods
  530  kubectl get svc
  531  kubectl logs hello-world-rest-api-58d8f57cb7-wpx8w -f
  532  kubectl logs hello-world-rest-api-58d8f57cb7-wpx8w hello-world-rest-api -f
  533  kubectl get pods
  534  kubectl describe pod hello-world-rest-api-58d8f57cb7-wpx8w
  535  kubectl get pods
  536  kubectl delete pod hello-world-rest-api-6845c5bbcd-g9w6g
  537  kubectl get pods
  538  kubectl logs hello-world-rest-api-58d8f57cb7-wpx8w hello-world-rest-api -f
  539  kubectl get svcs --namespace istio-system
  540  kubectl get svc --namespace istio-system
  541  pwd
  542  kubectl apply -f 02-creating-http-gateway.yaml 
  543  kubectl apply -f 03-creating-virtualservice-external.yaml 
  544  clear
  545  kubectl get svc --namespace istio-system
  546  kubectl get svc istio-ingressgateway --namespace istio-system
  547  kubectl get pods
  548  kubectl apply -f 01-helloworld-deployment.yaml 
  549  kubectl apply -f 01-helloworld-deployment.yaml 
  550  kubectl get pods
  551  kubectl get pods
  552  kubectl apply -f 01-helloworld-deployment.yaml 
  553  kubectl get pods
  554  kubectl get svcs --namespace=istio-system
  555  kubectl get svc --namespace istio-system
  556  kubectl get pods
  557  kubectl apply -f 01-helloworld-deployment.yaml 
  558  kubectl get pods
  559  kubectl get pods
  560  kubectl get pods
  561  kubectl scale deployment hello-world-rest-api --replicas=4
  562  kubectl get pods
  563  kubectl scale deployment hello-world-rest-api --replicas=2
  564  kubectl get pods
  565  kubectl delete all -l app=hello-world-rest-api
  566  kubectl apply -f 04-helloworld-multiple-deployments.yaml 
  567  kubectl get pods
  568  kubectl apply -f 04-helloworld-multiple-deployments.yaml 
  569  clear
  570  kubectl get pods
  571  kubectl get pods
  572  clear
  573  kubectl get pods
  574  kubectl apply -f 05-helloworld-mirroring.yaml 
  575  kubectl get pods
  576  kubectl logs hello-world-rest-api-v2-54cd78cfb6-gzz9n -f
  577  kubectl logs hello-world-rest-api-v2-54cd78cfb6-gzz9n hello-world-rest-api -f
  578  kubectl apply -f 06-helloworld-canary.yaml 
  579  kubectl apply -f 06-helloworld-canary.yaml 
  580  kubectl apply -f 06-helloworld-canary.yaml 
  581  kubectl apply -f 06-helloworld-canary.yaml
  watch -n 0.1 curl 35.223.25.220/hello-world

  gcloud container clusters get-credentials standard-cluster-1 --zone=europe-west1-b

kubectl create namespace istio-system
curl -L https://git.io/getLatestIstio | ISTIO_VERSION=1.2.2 sh -
cd istio-1.2.2
for i in install/kubernetes/helm/istio-init/files/crd*yaml; do kubectl apply -f $i; done
helm template install/kubernetes/helm/istio --name istio --set global.mtls.enabled=false --set tracing.enabled=true --set kiali.enabled=true --set grafana.enabled=true --namespace istio-system > istio.yaml
kubectl apply -f istio.yaml
kubectl label namespace default istio-injection=enabled


mvn clean install
  502  docker push in28min/currency-exchange:3.0.0-RELEASE
  503  pwd
  504  clear
  505  kubectl apply -f deployment.yaml 
  506  pwd
  507  kubectl apply -f 11-istio-scripts-and-configuration/07-hw-virtualservice-all-services.yaml 
  508  kubectl get secret -n istio-system kiali
  509  kubectl create secret generic kiali -n istio-system --from-literal=username=admin --from-literal=passphrase=admin

  kubectl get svc --namespace istio-system

583  gcloud container clusters get-credentials helm-cluster --zone us-central1-a --project solid-course-258105
  584  pwd
  585  ls
  586  ls
  587  ./helm-tiller.sh
  588  cat helm-tiller.sh 
  589  kubectl get deploy,svc tiller-deploy -n kube-system
  590  ls
  591  clear
  592  ls
  593  helm install ./currency-exchange/ --name=currency-services
  594  kubectl get all
  595  kubectl get svc --watch
  596  clear
  597  helm install ./currency-conversion/ --name=currency-services-1
  598  kubectl get pods
  599  kubectl get svc --watch
  600  clear
  601  helm install ./currency-conversion/ --name=currency-services-1 --debug --dry-run
  602  helm install ./currency-conversion/ --name=currency-services-3 --debug --dry-run
  603  helm history currency-services-1
  604  clear
  605  helm upgrade currency-services-2 ./currency-conversion/
  606  clear
  607  helm upgrade currency-services-1 ./currency-conversion/
  608  kubectl get pods
  609  helm history currency-services-1
  610  helm rollback currency-services-1 1
  611  kubectl get pods
  612  helm upgrade currency-services-1 ./currency-conversion/ --debug --dry-run
  613  helm upgrade currency-services-1 ./currency-conversion/
  614  helm history currency-services-1
  615  helm rollback currency-services-1 1
  616  kubectl get cm
  617  history
```

## Next Steps

## Todo
- Course Promotion Emails/Posts
  - 2 Emails on Udemy
  - 2 Emails to Email List
- Create YouTube Course Preview Video
  - Add YouTube Course Preview Video as End Video for all videos
  - Make it the YouTube Default Video
- Release atleast 20 small videos - one a day on Youtube
- Do atleast 3 Youtube live sessions
- After a Month
  - UFB and Packt
