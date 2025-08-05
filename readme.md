# Ingress Controller

### OIDC Provider

trust and authentication 
provider

REGION_CODE=us-east-1 CLUSTER_NAME=roboshop
ACC_ID=607700977716
```
eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve
```