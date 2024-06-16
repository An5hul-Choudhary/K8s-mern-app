
# commands that are used 

```
1 choco install kubernetes-cli
2 kubectl version --client
3 choco install minikube
```
++++++++++++++++++++++++++++++++++++++
```
minikube start
kubectl get pod
kubectl apply -f mongo-config.yaml
kubectl apply -f secret.yaml
kubectl apply -f mongo-app.yaml
kubectl apply -f web-app.yaml
kubectl get pod
kubectl get configmap
kubectl get secret
kubectl get svc
minikube ip
kubectl get node -o wide
```

```
minikube service webapp-service

```
#Login using username: admin & password: pass

++++++++++++++++++++++++++++++++++++++
```
kubectl delete deployment --all
```
```
kubectl delete secret --all
```
```
kubectl logs deployment/webapp-deployment
```
