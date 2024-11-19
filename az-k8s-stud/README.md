Cluster for exercise "Kubernetes on Azure"

```
az login
```

```
tofu init
tofu plan -out plan.cache
tofu apply plan.cache
```

```
az aks get-credentials --resource-group rg-swa-001 --name aks-swa-001 --overwrite-existing
kubectl cluster-info
kubectl get namespace
kubectl get node
```

```
tofu destroy
```
