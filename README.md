A kubernetes deployment for Alfresco 6.2.0 similar to https://github.com/Soldann/camunda-deployment

## Install to an existing kubernetes cluster with https://github.com/zalando/postgres-operator already installed
```
kubectl apply -f database-setup.yaml
kubectl apply -f ingress.yaml
```
Wait for the database to finish setting up before deploying
```
kubectl apply -f deployment.yaml
```
