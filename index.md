# Criando o cluster
kind create cluster --config cluster.yaml

# Criando o Ingress
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/main/deploy/static/provider/kind/deploy.yaml

