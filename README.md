
# docker

why only docker not other tool.
diffrence between vm and containerization.
why does ubuntu container get exited in.
difference between run and cmd.
host a static website in your docker container.
icmp

# docker commands--

1) docker --version                ------ check docker version
2) docker info                    ------- get system info about docker installation
3) docker pull <image>            ------- download image from docker hub
4) docker images                 -------  list all downloaded docker image
5) docker rmi <image id>         -------  remove image by id and name

# Kubernetes
Kubernetes (K8s) is an open-source container orchestration platform. It helps in deploying, managing, and scaling containerized applications. Kubernetes ensures apps are highly available, self-healing, and scalable. For example, if a container fails, Kubernetes automatically restarts it. Applications run in pods, multiple pods can be managed by deployments, and they are exposed to the network using services.

help always your appliction up.
1)explain the architecture of kubernetes.
2)explain what happen when pod is deleted.
3)you have instances one contain sap application and one contain hdb database now evereyday start instance morning 9 am and stop your instance at 9 pm along with that you also have to stop your service sap control will be started will be 9:15 and hdb start with  9:10 in the night sap can stop 8:50 and hdb stop 8:45.

master plane -- to give instruction
pod- to manage any type of container
pod can manage k8s
kubelet --can manage lifecycle
kube-proxy --- load balance
etcd --storage


Commonly Used Kubernetes Commands (kubectl):

Check cluster info:

kubectl cluster-info


List nodes in the cluster:

kubectl get nodes


List pods in the default namespace:

kubectl get pods


Create resources from YAML file:

kubectl apply -f deployment.yaml


Delete resources:

kubectl delete -f deployment.yaml


Describe a pod (detailed info):

kubectl describe pod pod-name


Get all resources:

kubectl get all


# terraform

Terraform is an open-source tool used for Infrastructure as Code (IaC). It allows developers to create, manage, and update cloud infrastructure using code instead of manual steps. With Terraform, you can define servers, storage, networks, and other resources in simple configuration files. This makes infrastructure consistent, repeatable, and version-controlled, reducing human errors.

Commonly Used Terraform Commands:

Initialize Terraform project:

terraform init


This command sets up the working directory with the required providers.

Check the plan before applying:

terraform plan


Shows what Terraform will create, change, or delete.

Apply the changes:

terraform apply


Executes the plan and creates or modifies the infrastructure.

Destroy infrastructure:

terraform destroy


Deletes all the resources defined in the Terraform files.

Format configuration files:

terraform fmt


Organizes and formats the code properly.
What is major difference between local variables and normal variable
Task :- Find the file meaning after init
Task :- What is meaning of terraform.tfstate
find meaning terraform.tfstate.backup after applying
Task :- How to integrate terraform with your provider aws without using access key and secret access key
What is import block?
terraform lifecycle
terraform basic files
what is difference between local values and variables in terraform


# jenkins

Jenkins is an automation server used for Continuous Integration (CI) and Continuous Deployment (CD). It automates tasks like building, testing, and deploying applications. Jenkins can pull code from Git repositories, run tests, build artifacts, and deploy to servers or Kubernetes clusters. It supports Freestyle jobs (simple GUI setup) and Pipeline jobs (scripted workflow).

Common Jenkins Tasks / Commands:

While Jenkins mostly uses the GUI, here are important CLI and Pipeline commands:

Trigger a job from CLI:

java -jar jenkins-cli.jar -s http://localhost:8080/ build job-name


Check job status:

java -jar jenkins-cli.jar -s http://localhost:8080/ get-job job-name


Pipeline Script Example (Jenkinsfile):

pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/username/repo.git', branch: 'main'
            }
        }
        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
    }
}


Restart Jenkins safely (CLI):

java -jar jenkins-cli.jar -s http://localhost:8080/ safe-restart

what is the difference between jar and war file.
difference between ci and cd.





















































   








