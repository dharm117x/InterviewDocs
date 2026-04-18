helm create springboot-app
cd springboot-app


helm install myapp .

helm install myapp . -f values-dev.yaml

helm upgrade myapp . -f values-dev.yaml

helm list

helm delete myapp

helm uninstall myapp

kubectl get all
kubectl get pods,svc

kubectl delete all -l app=myapp
