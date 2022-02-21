# kubernate-node-mongo-rancher

Node with Mongo db and deploy in kubernate with  Rancher Desktop

Steps with MiniKube : 

1) Install Rancher Desktop
2) kubectl get all
3) kubectl get pods
4) kubectl apply -f mongo-config.yaml
5) kubectl apply -f mongo-secret.yaml
6) kubectl apply -f mongo.yaml
7) kubectl apply -f webapp-service.yaml
8) kubectl apply -f webapp.yaml
9) kubectl get svc


Few Other Commands : 

1) kubectl get ingress
2) kubectl get service
3) kubectl get deployment
4) kubectl delete deployment <deployment-name>
5) kubectl delete service <service-name>
6) kubectl delete ingress <ingress-name>
7) kubectl logs <pod-id)

