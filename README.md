# Kubernetes--MondoDB
Kubernetes and Minikube MondoDB Cluster

Basic commands:

kubectl apply -f mongodb-secret.yaml        # Load secret file

kubectl get secret                          # Load secrets into Kubernetes

kubectl apply -f mongodb-deployment.yaml    # Launch ReplicaSets

kubectl get pod -A                           # Verify

kubectl get pod -o wide

kubectl apply -f mongodb-service.yaml

kubectl get service -A

kubectl describe service mongodb-service

kubectl apply -f mongo-configmap.yaml   

kubectl apply -f mongo-express-deployment.yaml    

kubectl apply -f mongo-express-service.yaml    

kubectl get service -A

minikube service mongodb-express-service -n web-namespace

|-----------|-------------------------|-------------|---------------------------|
| NAMESPACE |          NAME           | TARGET PORT |            URL            |
|-----------|-------------------------|-------------|---------------------------|
| default   | mongodb-express-service |        8081 | http://192.168.64.2:30000 |
|-----------|-------------------------|-------------|---------------------------|
🎉  Opening service default/mongodb-express-service in default browser...


