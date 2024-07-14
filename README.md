git clone https://github.com/vijayvikma/todo-three-tier.git

cd todo-three-tier

helm install three-tier .

kubectl port-forward svc/frontend-service 8000:80 

http://localhost:8000


<img width="827" alt="image" src="https://github.com/user-attachments/assets/f08eebd8-4924-451d-be8f-1cc66339ebfe">
