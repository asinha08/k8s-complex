***How to see the storage in minicibe***
```
kubectl get storageclass
```

***How to get persistenet volume & claim***
```
kubectl get pv
kubectl get pvc
```

***How to create SECERET for password****
this command has to be run locally on the machine and in prod also it has to be run
```
kubectl create secret generic pgpassword --from-literal PGPASSWORD=sdds1213
```
***********

***How to enable Ingress***
URL For Details --> 
```
https://kubernetes.github.io/ingress-nginx/deploy/#prerequisite-generic-deployment-command
```

Mandatory Command is required for all deployments. -->
```
kubectl apply -f https://raw.githubusercontent.com/kubernetes/ingress-nginx/master/deploy/static/mandatory.yaml
```
For Minikube -->
```
minikube addons enable ingress
```

************
***How to view minikube dashboard****
```
minikube dashboard
```
