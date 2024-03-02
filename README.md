# Create AWS EKS Cluster and Node Groups using Terraform
![kubernetes cluster with eks](https://github.com/Omar-Ahmed-Dt/AWS-EKS-Cluster/blob/master/img/eks.png)
---
This repository contains Terraform files to deploy a Kubernetes cluster in AWS. It sets up a two-availability-zone architecture with four subnets—two public and two private. Additionally, The configuration includes two worker nodes, with one situated in the private subnet and the other in the public subnet, it deploys a bastion host in the public subnet to facilitate connections to worker nodes. 
## Steps:
1. Create EKS Cluster
2. Create Public EKS Node Group
3. Create Private EKS Node Group
4. Review the Sample Application Kubernetes Manifests
5. Deploy sample application and verify
6. Clean-Up (Sample Application and EKS Cluster and Node Groups)