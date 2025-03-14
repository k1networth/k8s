# k8s
```
kubectl create namespace my-namespace
kubectl create configmap nginx-config --from-file=nginx.conf -n my-namespace
kubectl get configmap -n my-namespace
kubectl get configmap nginx-config -o yaml -n my-namespace

kubectl apply -f main.yaml
kubectl delete -f main.yaml
```
