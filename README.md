git clone https://github.com/vijayvikma/todo-three-tier.git

cd todo-three-tier

helm install three-tier .

kubectl port-forward svc/frontend-service 8000:80 
