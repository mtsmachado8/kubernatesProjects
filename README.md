## Creating pods and services
	kubectl apply -f client-pod.yaml
	kubectl apply -f client-node-port.yaml

## Getting pods and services
	kubectl get pods
	kubectl get services

## Getting ip of a pod
	minikube ip
	
## Deleting pods 
	kubectl delete pods --all
	kubectl delete pods <pod_name>

## Deleting services 
	kubectl delete services --all
	kubectl delete services <pod_name>
	
## References
kube-apiserver responsible to manage responsabilities like
- Need to be running x instances of multicontainer-client

Try to always use Declarative. its better than imperative commands.


## TODO
problems
- mtsmachado8/multicontainer-client is not working for now.
- put instalation of kubernates in README.md