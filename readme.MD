Taint the node
```
kubectl taint nodes node1 key1=value1:NoSchedule

kubectl taint nodes <paste-node-ip> hardware=gpu:NoSchedule

```

Label the node
```
kubectl label nodes <your-node-name> disktype=ssd

kubectl label nodes <paste-node-ip> hardware=gpu

```