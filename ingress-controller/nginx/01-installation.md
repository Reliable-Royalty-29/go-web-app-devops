## Install Nginx Ingress Controller on Azure

### Step 1: Go to the Official GitHub Repository

Visit the [kubernetes/ingress-nginx GitHub repository](https://github.com/kubernetes/ingress-nginx?tab=readme-ov-file).

In the repository, find the "Getting Started" document and click on "Azure".

### Step 2: Deploy the Manifest

Deploy the Nginx Ingress Controller on Azure by applying the following manifest:

```bash
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.11.1/deploy/static/provider/aws/deploy.yaml
```

This command will set up the Nginx Ingress Controller using the provided manifest file.yaml


