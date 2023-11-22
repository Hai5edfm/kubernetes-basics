# kubernetes-basics

### Create a pod (in pods folder)
```bash
kubectl apply -f nginx.yaml
```

### To delete a pod
```bash
kubectl delete pod <pod-name>
```

### Create a replicaset (in replicas folder)
```bash
kubectl apply -f 
```

### To delete a rs
```bash
kubectl delete replicaset <replicaset-name>
```

### To Scale the number of pods in a replica
```bash
kubectl scale replicaset <replicaset-name> --replicas=<number-of-replicas>
```

