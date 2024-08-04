
```
cd pods
kubectl version --client=true -o yaml
kubectl apply -f pod.yml
kubectl get pods     
kubectl describe pod hello-pod
kubectl exec -it hello-pod -- sh
kubectl delete pod hello-pod
```
