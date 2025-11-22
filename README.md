Apply namespace first
kubectl apply -f namespace.yml

Products
kubectl apply -f products.yml

Orders
kubectl apply -f orders.yml

Check:
kubectl get pods -n microservices

Deploy frontend
kubectl apply -f frontend.yml


Check:
kubectl get pods -n microservices

Deploy Ingress (very important)
kubectl apply -f ingress.yml


Get load balancer URL:
kubectl get ingress -n microservices
