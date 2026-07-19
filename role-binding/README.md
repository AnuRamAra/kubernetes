Kube Clustter-role templates
_______________________________

FullStack:
kubectl apply -f https://raw.githubusercontent.com/AnuRamAra/kubernetes/refs/heads/master/cluster-role/fullstack/froentend.yml
kubectl apply -f https://raw.githubusercontent.com/AnuRamAra/kubernetes/refs/heads/master/cluster-role/fullstack/backend.yml
kubectl apply -f https://raw.githubusercontent.com/AnuRamAra/kubernetes/refs/heads/master/cluster-role/fullstack/qa.yml

Data:
kubectl apply -f https://raw.githubusercontent.com/AnuRamAra/kubernetes/refs/heads/master/cluster-role/data/data-science.yml

infra:
kubectl apply -f https://raw.githubusercontent.com/AnuRamAra/kubernetes/refs/heads/master/cluster-role/infrastructure/devops.yml





Cluster-role-binding templates
_________________________________

FullStack:
kubectl apply -f https://raw.githubusercontent.com/AnuRamAra/kubernetes/refs/heads/master/cluster-role-bindning/fullstack/backend.yml
kubectl apply -f https://raw.githubusercontent.com/AnuRamAra/kubernetes/refs/heads/master/cluster-role-bindning/fullstack/frontend.yml
kubectl apply -f https://raw.githubusercontent.com/AnuRamAra/kubernetes/refs/heads/master/cluster-role-bindning/fullstack/qa.yml

data:
kubectl apply -f https://raw.githubusercontent.com/AnuRamAra/kubernetes/refs/heads/master/cluster-role-bindning/data/data-science.yml

infra:
kubectl apply -f https://raw.githubusercontent.com/AnuRamAra/kubernetes/refs/heads/master/cluster-role-binding/infrastructure/devops.yml
