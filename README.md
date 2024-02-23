#                       KUBERNETES DEMO

# Prerequisites (Windows)

- Ensure that a CLI is available for running kubectl commands. 
    - Git Bash (https://git-scm.com/downloads) 
    - Visual Studio Code 

- Install Docker Desktop (Windows, Mac, Linux)
    - https://www.docker.com/products/docker-desktop/

- In the configuration settings of Docker Desktop, enable Kubernetes

# Kubernetes Cheat Sheet

- Get Pods
```
kubectl get pods

kubectl get pods -o wide

$ kubectl get services
NAME         TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   5h12m




```

```
kubectl create -f nginx.yaml
```

```
kubectl delete pod nginx

kubectl delete pods --all

kubectl delete -f 
```

- Get namespaces

```
kubectl get --all-namespaces
$ kubectl get -A namespaces
NAME              STATUS   AGE
default           Active   5h9m
kube-node-lease   Active   5h9m
kube-public       Active   5h9m
kube-system       Active   5h9m
```



