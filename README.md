
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
what is the difference between jar and war file
difference between ci and cd





















# Docker compose 

docker network


# KUBERNETES
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

































   








