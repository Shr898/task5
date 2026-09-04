## Task5
This is a kubernetes bases task.
We have to create an app and its service.
Then we have to create a deployment.yaml and service.yaml file.
In my case, I have created a nginx app.
Then I have to run kubectl apply -f deployment.yaml and do the same for service.yaml.
Then it will be applied and the service and the 2 nginx apps will run.
After that we scale the 2 nginx apps to 4.

## Screenshots
## 1. kubectl minikube running
![minikube running](screenshots/task5-minikube-start-success.png)

## 2. kubectl get nodes
![nodes](screenshots/task5-get-nodes.png)

## 3. kubectl deployment.yaml
![deployment yaml](screenshots/task5-kubectl-deployment-yaml.png)

## 4. kubectl services.yaml
![service.yaml applied](screenshots/task5-service-yaml-created.png)
![service](screenshots/task5-nginx-service-running.png)

## 5. pods and services before scaling to 4
![pods](screenshots/task5-kubectl-get-pods.png)
![service and pods](screenshots/task5-kubectl-pods-and-service.png)

## 6. After scaling to 4 
![After scaling to 4](screenshots/task5-kubectl-deployment-scaled.png)
![scale proof](screenshots/task5-kubectl-deployment-scaled-proof.png)

## 7. kubectl describe pod
![describe a pod](screenshots/task5-kubectl-describe-pod.png)