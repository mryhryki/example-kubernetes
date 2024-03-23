# Note

## 2024-03-23

https://kubernetes.io/docs/concepts/workloads/controllers/deployment/#creating-a-deployment

```shell
$ kubectl apply -f controllers/nginx-deployment.yaml
$ kubectl rollout status deployment/nginx-deployment
$ kubectl get deployments
$ kubectl get rs # rs = ReplicaSet
$ kubectl get pods --show-labels
```
