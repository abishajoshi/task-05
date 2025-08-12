**Build a Kubernetes Cluster Locally with Minikube
This project demonstrates how to set up a local Kubernetes cluster using Minikube and deploy a sample application.
**
Steps Followed

 -Install Minikube & Start the Cluster

-Minikube was installed locally to simulate a Kubernetes cluster environment.

-The cluster was started using the minikube start command.

-Create Deployment for the Application

A Kubernetes deployment was defined to manage the application pods.

Expose the Application via Service

The application was exposed using a Kubernetes service to make it accessible externally.

**Verify Pods

Verified the running pods using the kubectl get pods command.
**
Scale the Deployment

The deployment was scaled up or down to manage the number of running pods using the kubectl scale command.

View Pod and Deployment Details

Used kubectl describe to view detailed information and logs for debugging or monitoring.

**Outcome
Successfully deployed and exposed an application in a local Kubernetes environment.

Verified application availability and scalability.

Tools Used
Minikube

kubectl
**
Kubernetes

