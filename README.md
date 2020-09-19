# Provision a GKE Cluster (Google Cloud)

This repo contains terraform code to create a one node GKE cluster by using free tier resources as much as possible to learn Kubernetes.

Please note although some resources sush as compute engine(f1-micro) are [free] (https://cloud.google.com/free/docs/gcp-free-tier), you may still be charged very minimal amount. Make sure you delete the resources using the below command if you no longer need to resources to save cost.

```
terraform destroy
``` 
