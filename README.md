##Kubectl Commands

Here is the cheatsheet for creating multiple development environments using namespaces in Kubernetes.

###Get Nodes
```	kubectl get nodes ```

###Get Pods
```	kubectl get pods ```

###Get Namespaces
```	kubectl get namespaces ```

###Get Services
```	kubectl get services ```

###Get All Objects
```	kubectl get all ```

###Create namespace
```	kubectl create namespace <namespaceName> ```

###Applying definitions
```	kubectl apply -f <filename.yml> ```

###Applying definitions in a namespace
```	kubectl apply -f <filename.yml> --namespace=<namespaceName> ```

###Get current context
```	kubectl config view --minify ```

###Switching context
```	kubectl config set-context --current --namespace=<namespaceName>```