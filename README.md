# Linux-Labs
linux-lab/

├── namespace.yaml

├── lab-deployment.yaml

├── lab-service.yaml

└── cleanup-cronjob.yaml

```
kubectl apply -f namespace.yaml
kubectl apply -f lab-rbac.yaml
kubectl apply -f lab-deployment.yaml
kubectl apply -f lab-service.yaml
kubectl apply -f cleanup-cronjob.yaml
```
