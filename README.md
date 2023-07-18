Before running the project:

kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/controller-v1.8.0/deploy/static/provider/cloud/deploy.yaml

kubectl create secret generic jwt-secret --from-literal=JWT_KEY=asdf

in hosts file => 127.0.0.1 ticketing.dev

Usefull commands:

skaffold dev

kubectl get secrets

kubectl get pods

kubectl delete pod pod_id

kubectl get namespace

kubectl get services -n namespace_name