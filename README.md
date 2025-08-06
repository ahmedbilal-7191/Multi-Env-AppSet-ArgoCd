Apply the ApplicationSet:
kubectl apply -f applicationset.yaml -n argocd
This will:

Automatically create Argo CD Applications for:

dev-nginx

staging-nginx

production-nginx

Sync them with their respective YAML files in dev/, staging/, and production/.

Create namespaces automatically and deploy NGINX with 1 replica each.
