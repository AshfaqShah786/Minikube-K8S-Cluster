# Minikube-K8S-Cluster
DAY-5


Step 1: Requirements

Install Minikube
Install kubectl
Install Docker (optional)

Step 2: Start the Minikube cluster

    minikube start

Step 3: Create Deployment YAML file

(Create a YAML file locally describing your app deployment Or Can Refer the filegiven above.)

Step 4: Apply the Deployment

    kubectl apply -f deployment.yaml

Step 5: Verify Pods

    kubectl get pods

Step 6: Create Service YAML file

(Create a YAML file locally describing your service — no commands here.)

Step 7: Apply the Service

    kubectl apply -f service.yaml

Step 8: Verify Services

    kubectl get services

Step 9: Access the Service in Browser

    minikube service nginx-service

Step 10: Scale the Deployment

    kubectl scale deployment nginx-deployment --replicas=4

Step 11: Verify Scaling

    kubectl get pods

Step 12: Inspect Pod Details

    kubectl describe pod <pod-name>

Step 13: View Pod Logs

    kubectl logs <pod-name>

Replace <pod-name> with the actual pod name from kubectl get pods.
