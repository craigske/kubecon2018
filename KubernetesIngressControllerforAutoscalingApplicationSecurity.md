# Kubernetes Ingress Controller for Autoscaling Application Security

1. Agenda
    * Why k8s at Starbucks
    * Fsast turnaround from idea to market
    * Scalable apps and processes
    * security to build, maint and audit trust
2. Why
    * apigateway -> edge LB -> ingress -> app svc
    * reduce toil
3. DevSecOps team
    * Ingress Orchestrator (native k8s application)
    * Ingres Orch Responsibities include:
      * Config of ingress
      * (missed this)
      * CA and Cert
      * DNS
      * WAF
    * CRD defined: (https://kubernetes.io/docs/tasks/access-kubernetes-api/custom-resources/custom-resource-definitions/)
    * DNS - annotaions for (https://github.com/kubernetes-incubator/external-dns)
    * Sidecar an agent into the ingress controller itself?
4. Going Further
    * be prepared to evolve your ingress controller
    * Dynamic Network Policy (service mesh?)
    * don't build it yourself if you don't have to
    * 