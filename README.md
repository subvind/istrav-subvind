istrav-subvind
========


production
```bash
# start
kubectl apply -f k8s/is-deployment.yaml
kubectl apply -f k8s/is-service.yaml

# get port
minikube service is-service --url
```