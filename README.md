# kubernetes-lessons

Somewhere I write my kubernetes fundamental knowledge. Might become a (git)book.


### Ingress and Ingress Controllers

* To give people access to an application inside a kubernetes cluster, you can (must?) use what Kubernetes calls an `Ingress`
* Creating an Ingress inside `Kubernetes`, is useless, if you don't create an `Ingress Controller` first : 

> 
> You must have an ingress controller to satisfy an Ingress. Only creating an Ingress resource has no effect.
> 
> _Source_ : https://kubernetes.io/docs/concepts/services-networking/ingress/#prerequisites
> 

