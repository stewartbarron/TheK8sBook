# Namespaces

```
kubectl api-resources
kubectl get namespaces
kubectl describe ns default
kubectl get svc --namespace kube-system

kubectl create ns hydra
kubectl apply -f shield-ns.yml
kubectl get ns
kubectl delete ns hydra
kubectl config set-context --current --namespace shield
kubectl apply -f app.yml
kubectl get pods -n shield
kubectl get svc -n shield
curl localhost:8080
kubectl delete ns shield
kubectl config set-context --current --namespace default
```
