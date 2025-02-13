# Install EKS

Pre-requisites: **kubectl**, **eksctl**, **AWS CLI**

## Install a EKS cluster with EKSCTL

```
eksctl create cluster --name demo-cluster --region us-east-1 --nodegroup-name my-nodegroup --node-type t2.medium --nodes 2
```

## Delete the cluster

```
eksctl delete cluster --name demo-cluster --region us-east-1
```
