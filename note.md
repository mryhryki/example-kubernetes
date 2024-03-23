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

https://kubernetes.io/docs/concepts/workloads/controllers/deployment/#updating-a-deployment

```shell
$ kubectl set image deployment.v1.apps/nginx-deployment nginx=nginx:1.16.1
$ kubectl describe deployments
```

https://qiita.com/dsagnlaiweudlbfna/items/55b162197afa74306067#node

```shell
$ kubectl get nodes
$ kubectl get namespace
```
