## Commands:
* kubectl create -f `kubectl-file-name`
* kubectl apply -f `kubectl-file-name`
* kubectl delete -f `kubectl-file-name`
* kubectl get `object`  
  Object can be -   
    1. pods
    2. services
    3. deployment

* kubectl describe `object-type` `object-name`  
  eg. kubectl describe pods test  
  Get details information about any object
* kubectl set image `object-type`/`object-name` `container-name` = `image-name`
* eval $(minikube docker-env)  
  Temporarily connect to the docker server in VM



# Cheat Sheet
https://kubernetes.io/docs/reference/kubectl/cheatsheet/