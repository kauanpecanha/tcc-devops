# Repositório de estudo de ideia para TCC

### Comandos importantes

- Deleção de custer
```
kind delete cluster --name cluster-demo
```

- Criação de cluster
```
kind create cluster --config kind-config.yaml 
```

- Configuração do cluster
```
kubectl apply -f nginx-deployment.yaml
kubectl apply -f nginx-service.yaml
kubectl apply -f nginx-ingress.yaml
```

Feito por: @kauanpecanha