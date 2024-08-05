# A Guide to the Most Useful AWS EKS Commands

Amazon Elastic Kubernetes Service (`EKS`) is a managed Kubernetes service that simplifies the deployment, management, and scaling of containerized applications using Kubernetes. In this tutorial, we’ll cover the most useful `AWS EKS` commands.


Amazon Elastic Kubernetes Service (EKS) is a managed Kubernetes service that simplifies the deployment, management, and scaling of containerized applications using Kubernetes. In this tutorial, we’ll cover the most useful AWS EKS commands.

These are the commands we’ll cover:

- Creating an EKS Cluster
- Updating an EKS Cluster
- Deleting an EKS Cluster
- Listing EKS Clusters
- Describing an EKS Cluster
- Creating a Node Group
- Updating a Node Group
- Deleting a Node Group
- Listing Node Groups
- Describing a Node Group

## Prerequisites

Before proceeding, ensure that you have the following installed:

AWS CLI: Install and configure the AWS CLI by following the official documentation.
kubectl: [Install kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/) to interact with the Kubernetes cluster.
eksctl: Install eksctl, a command-line tool for creating and managing EKS clusters.

## 1. Creating an EKS Cluster

To create an EKS cluster, use the `eksctl create` cluster command. Include your desired cluster name and your chosen AWS region:

> eksctl create cluster --name --region

> example: eksctl create cluster --name my-eks-cluster --region ap-south-1
