## The State of K8s security

### boundaries

### Control Plane

* API Server
* Kubelet on each node
* etcd
* Dashboard (if installed)

* kube-bench CIS checks

### kube-bench demo

* take home - do this as demo
* 

### Authorization

* Namespace
* RBAC
* TODO: review these slides

### Container Images

* checks to determine image compliance
* trusted images
* USER
* perform scans (plenty of tools)
* private registries
* pin deps

### Running containers

* don't run as root USER
* PodSecurityPolicy (limit volume mounts)
* 

### Secrets Management

* Namespaced objects to store sensative information
* Access via volume or env var. (file is considered more secure as they are temp memory mounts)
* data in tempfs volumes
* per secret size limit of 1MB
* only base64 encoded 

### Additional considerations

* host security
* Container Sandboxing
* Secure TLS connections

[kubernetes-security.info](kubernetes-security.info)