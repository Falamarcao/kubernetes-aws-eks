# Kubernetes - AWS EKS

<https://www.udemy.com/course/docker-kubernetes-the-practical-guide/learn/lecture/22628009>

```sh

    # Configure AWS Access Key ID and Secret Access Key
    aws configure

    # Configure Kubernetes Configuration File
    aws eks --region us-east-1 update-kubeconfig --name cluster_name

    cd kubernetes

    kubectl apply -f users.yaml,tasks.yaml

    kubectl get services

```