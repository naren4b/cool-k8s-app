```
kubectl run httpbin --image kennethreitz/httpbin --port 80
kubectl expose pod httpbin --port 80
kubectl port-forward httpbin 80 --address 0.0.0.0

```
