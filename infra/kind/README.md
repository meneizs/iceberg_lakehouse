# Iniciando o cluster local.

```
kind create cluster --config infra/kind/cluster.yaml
```


```
kubectl create namespace cicd
kubectl create namespace management
kubectl create namespace storage
kubectl create namespace database
```

