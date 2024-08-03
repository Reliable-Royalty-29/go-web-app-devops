##Install Nginx Ingress Controller on Azure

**Step 1: Go the this offical github repo

https://github.com/kubernetes/ingress-nginx?tab=readme-ov-file -> See the Getting Started document -> Click on Azure

**Step 2: Deploy the below manifest

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.11.1/deploy/static/provider/cloud/deploy.yaml


