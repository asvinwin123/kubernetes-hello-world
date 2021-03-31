# kubernetes-hello-world
This will give an idea to host a hello world application in minikube cluster

# Pre requisites
```
Minikube setup is already done.
If minikube is not installed kindly follow,
https://gist.github.com/gonzaloplaza/f62fdcfdb6aac3d15a0fe0d750715729
```

# Start minikube
```
minikube start
```

# Open minikube dashboard
```
minikube dashboard
```

# Clone the repository
```
https://github.com/asvinwin123/kubernetes-hello-world.git
cd kubernetes-hello-world
```

# Run deployment
```
kubectl create -f deployment.yaml
```

go to minikube dashboard and check the deployment and pods tab. verify the pods are in running state.

# Verify in cmd line
```
kubectl get pods
kubectl get deployments
kubectl get services
```

# Open the hello world application
```
get the minikube ip using
minikube ip
in browser open to see the hello wrold app, 
http://minikubeip:30001
```
