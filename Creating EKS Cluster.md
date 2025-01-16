# Install Using Fargate

To create a cluster using Fargate, use the following command:

```bash
eksctl create cluster --name demo-cluster --region us-east-1 --fargate

#Delete the Cluster

To delete the cluster, use the following command:

```bash
eksctl delete cluster --name demo-cluster --region us-east-1
