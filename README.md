# MicroserviceEcommerce-K8S
kubernetes repository for MicroserviceEcommerce

Deployment

- After pulling this repository, Run these commands in CMD using local folder as root

  
kubectl apply -f ecommerceproductservice-depl.yaml

kubectl apply -f ecommerceuserservice-depl.yaml

kubectl apply -f ecommerceuserservice-np-srv.yaml

kubectl apply -f ingress-srv.yaml

kubectl apply -f local-pvc.yaml

kubectl apply -f mssql-ecommerceuserservice-depl.yaml

kubectl apply -f rabbitmq-depl.yaml
