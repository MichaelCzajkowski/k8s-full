```sh
kubectl apply -f pod.yaml
kubectl get pods
kubectl get pods -A
kubectl get all
kubectl get pod -A --selector="app=myapp"
kubectl exec -ti myapp-pod -- curl localhost
kubectl logs myapp-pod
kubectl port-forward pod/myapp-pod 8080:80
```
## moje
```sh
kubectl port-forward pod/myapp-pod-1 5002:5002
kubectl delete pod myapp-pod-1
```
