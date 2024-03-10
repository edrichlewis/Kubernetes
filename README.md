# Kubernetes
Kubernetes Projects
1. Deployed a Mongo-express app in Minikube to practise Kubernetes

![image](https://github.com/edrichlewis/Kubernetes/assets/105597780/03f65263-407f-4cee-87bd-fdf5495ef9bd)

1. we create the yaml files for secrets and config where we save the passwords in the secrets file and config which has the URL of Mongo Express app

   Prerequisite:
   1. Created a Linux machine using Vmware
   2. Installed Docker which Minikube will use.
   3. Installed kubectl
   4. Installed Minikube
  
2. Created the secret.yaml file
3. Created the config.yaml file
4. Created the deployment yaml and service yaml file for Mongo db as well as the Web app

5. we will use the Mongo Express app image from docker and the Mongo db image from docker
6. Start the Minikube and use kubectl apply command: ex: kubectl apply -f service.yaml first the secret, config and the deployment (service components are within the deployment file itself)
7. Run Kubectl get pods to see if all deployments are successful
8. run kubectl get svc
9. run the Minikuke service web app-service, we will receive an URL we can access it using the username: admin and password: pass

10. ![image](https://github.com/edrichlewis/Kubernetes/assets/105597780/25c19a3d-6a95-40b4-984b-a7b98bbe8180)

