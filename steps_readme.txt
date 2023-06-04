Steps that need to follow:-

Part:1 

Create all the Pods, and service
Pods:- voting-app-pod, result-app-pod, redis-pod, postgres-pod, worker-app-pod
Services:- redis-service, postgres-service, voting-app-service, result-app-service

Now, run all the Pods, and services to access the vote and result app via service:

minikube service voting-service --url 

minikube service result-service --url 

----

Part:2

Create all the deployments:

Deployments: voting-app-deployment, redis-deployment, postgres-deployment, worker-app-deployment, result-app-deployment

Make sure, all the services are running and now we can access the app that running on the deployment Pods.

============
