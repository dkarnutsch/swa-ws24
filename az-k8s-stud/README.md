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
kubectl cluster-info
kubectl get namespace
kubectl get node
```

```
tofu destroy
```
