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

set image: nigelpoulton/k8sbook:2.0 in deploy.yml

kubectl apply -f deploy.yml
kubectl rollout status deployment hello-deploy
kubectl get deploy hello-deploy
kubectl rollout pause deploy hello-deploy
kubectl describe deploy hello-deploy
kubectl rollout resume deploy hello-deploy
kubectl get deploy hello-deploy
```
