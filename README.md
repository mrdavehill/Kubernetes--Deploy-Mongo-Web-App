# Kubernetes--MondoDB
Kubernetes and Minikube MondoDB Cluster

kubectl apply -f mongodb-secret.yaml        # Load secret file
kubectl get secret                          # Load secrets into Kubernetes
kubectl apply -f mongodb-deployment.yaml    # Launch ReplicaSets
kubectl get pod                             # Verify
