# Kubernetes--MondoDB
Kubernetes and Minikube MondoDB Cluster

Basic commands:

kubectl apply -f mongodb-secret.yaml        # Load secret file

kubectl get secret                          # Load secrets into Kubernetes

kubectl apply -f mongodb-deployment.yaml    # Launch ReplicaSets

kubectl get pod                             # Verify

kubectl get pod -o wide

kubectl apply -f mongodb-service.yaml

kubectl get service

kubectl describe service mongodb-service

kubectl apply -f mongo-configmap.yaml   

kubectl apply -f mongo-express-deployment.yaml    




