Taint the node

ip-192-168-30-193.ec2.internal   Ready    <none>   6m47s   v1.30.4-eks-a737599
ip-192-168-32-171.ec2.internal   Ready    <none>   62s     v1.30.4-eks-a737599
ip-192-168-9-192.ec2.internal    Ready    <none>   7m36s   v1.30.4-eks-a737599

```
kubectl taint nodes node1 key1=value1:NoSchedule

kubectl taint nodes ip-192-168-32-171.ec2.internal hardware=gpu:NoSchedule

```

Label the node
```
kubectl label nodes <your-node-name> disktype=ssd

kubectl label nodes ip-192-168-9-192.ec2.internal hardware=gpu

```