# authenticus_k8s
Inicio de estudos para transição do authenticus para K8s

Para execução do arquivo de deplyment é necessario realizar a bulid da image por meio do dockerfile, e ter um ambinete kubernetes pre-configurado, recomenda-se o Minikube, em seguida deve-se realaizar o apply do arquivo:

"kubectl apply -f authenticus-4-sea-deployment.yaml"

em seguida poderá visualizar os 5 pods usando o comando: "kubectl get pods"
