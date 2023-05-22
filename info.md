0/1:  minikube delete --all  
2: minikube start 
3: kubectl create secret generic pgpassword --from-literal PGPASSWORD=postgres12345
4: kubectl apply -f k8s
5: minikube stop
6: minikube tunnel
7: go to localhost on browser

to update with latest docker image imperatively: kubectl set image deployment/client-deployment client=discoveranirban/multi-client:v5
kubectl set image <objectType>/<objectName> <containerName>=discoveranirban/multi-client:v5

minikube service <service-name> --url

