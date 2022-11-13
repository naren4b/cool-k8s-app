# Listing cool apps 
Interesting application k8s manifest-files
# Build Docker image

```
docker build -t naren4b/cool-k8s-app:latest .
docker push naren4b/cool-k8s-app:latest
```
# Deploy in kubernetes 
```
kubectl run cool-k8s-app --image naren4b/cool-k8s-app:latest --port 80
kubectl expose pod cool-k8s-app --port 80
kubectl port-forward cool-k8s-app 80 --address 0.0.0.0

```
