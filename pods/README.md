
```
cd pods
kubectl version --client=true -o yaml
kubectl get nodes 
kubectl apply -f pod.yml
kubectl get pods     
kubectl describe pod hello-pod
kubectl exec -it hello-pod -- sh
kubectl edit pod hello-pod
kubectl apply -f initpod.yml
kubectl get pods --watch 
kubectl describe pod initpod
kubectl apply -f initsvc.yml
kubectl get pods --watch
kubectl describe pod initpod
```
edit sidecarpod.yml with forked repo address
```
kubectl apply -f sidecarpod.yml
```
when running
```
kubectl get svc 
```
copy the value from the EXTERNAL-IP column
paste to a new browser tab

```
kubectl delete pod hello-pod initpod git-sync 
kubectl delete svc k8sbook svc-sidecar 
```