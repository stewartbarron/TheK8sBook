# Deployments

```
kubectl apply -f deploy.yml
kubectl get pods
kubectl get deploy hello-deploy
kubectl describe deploy hello-deploy
kubectl get rs
kubectl describe rs hello-deploy-85fb59464d
kubectl apply -f lb.yml
kubectl get svc lb-svc
kubectl get deploy hello-deploy
kubectl scale deploy hello-deploy --replicas 5
kubectl get deploy hello-deploy
kubectl apply -f deploy.yml
kubectl get deploy hello-deploy
```
