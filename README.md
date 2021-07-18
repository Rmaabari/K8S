# K8S
K8s Lab
Question #1 
minikube kubectl -- run --image nginx/alpine raz-nginx

Question #2
kubectl run messaging --image redis:alpine --labels="tier=msg"

Question #3
kubectl create namespace apx-x998-raz

Question #4
kubectl get pods -o json > /tmp/nodes-raz

Question #5
kubectl create deployment messaging --image redis:alpine --replicas=3
kubectl expose deployment messaging --port=6379 --type=ClusterIP --name=messaging-service


**Pod Desgin Questions**

1.kubectl get pods --show-labels

2. kubectl apply -f deploy5-replicas.yml






**Deployments**
