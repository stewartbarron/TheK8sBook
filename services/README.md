# Services

```
kubectl apply -f deploy.yml
kubectl get pods
kubectl expose deployment svc-test --type=LoadBalancer
kubectl get svc -o wide
kubectl describe svc svc-test
kubectl delete svc svc-test

kubectl apply -f lb.yml
kubectl get svc cloud-lb
kubectl get endpointslices
kubectl describe endpointslice cloud-lb-m6jk9
kubectl delete -f deploy.yml -f lb.yml
```
