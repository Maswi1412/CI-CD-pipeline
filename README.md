Building an End-to-End CI/CD Pipeline with AWS, Jenkins, Docker, SonarQube, ArgoCD and Kubernetes
Table of contents
1. Create an EC2 instance in AWS:
Allocate the elastic IP address and associate it with the newly created EC2 instance.
2. Install and configure Jenkins:
3. Fork the GitHub repository and create a webhook:
4. Build a new item in Jenkins:
5. Installing plugins:
6. Install SonarQube in Ubuntu and configure it in Jenkins:
7. Adding Credentials in Jenkins
Connecting Jenkins and SonarQube:
Adding credentials for DockerHub in Jenkins:
Adding credentials for github in Jenkins:
8. Install Docker and configure it in Jenkins:
9. Writing Jenkinsfile and manifest file:
10. Build the pipeline:
Now let’s perform continuous deployment using ArgoCD in Kubernetes in the local system
1. Install Dependencies:
2. Install kubectl and minikube and start minikube
3. Installing and configuring Argo CD
4. Setting up Argo CD for deployment in K8s
5. Testing the deployment from the browser
