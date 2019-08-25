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
