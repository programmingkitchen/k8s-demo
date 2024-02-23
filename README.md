# Kubernetes Commands


kubectl get pods


kubectl create -f nginx.yaml


kubectl delete pod nginx

kubectl delete pods --all

kubectl delete -f 


kubectl get --all-namespaces
$ kubectl get -A namespaces
NAME              STATUS   AGE
default           Active   5h9m
kube-node-lease   Active   5h9m
kube-public       Active   5h9m
kube-system       Active   5h9m



kubectl get pods -o wide

$ kubectl get services
NAME         TYPE        CLUSTER-IP   EXTERNAL-IP   PORT(S)   AGE
kubernetes   ClusterIP   10.96.0.1    <none>        443/TCP   5h12m


