# kubernetes

## exam setup

shell 

    alias k=kubectl  # already configured
    export do="--dry-run=client -o yaml"

vim (~/.vimrc)

    set tabstop=2
    set expandtab
    set shiftwidth=2
    

## Exercises and Guides
[Official curriculum](https://github.com/cncf/curriculum)  
[killer shell exam simulator](https://killer.sh/)  

[kubernetes the hard way](https://github.com/kelseyhightower/kubernetes-the-hard-way)  
[CKAD-exercises](https://github.com/dgkanatsios/CKAD-exercises)  

## Documentation Links
[kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)  
[Configure a Pod to Use a Volume for Storage](https://kubernetes.io/docs/tasks/configure-pod-container/configure-volume-storage/)  
[Operating etcd clusters for Kubernetes](https://kubernetes.io/docs/tasks/administer-cluster/configure-upgrade-etcd/#backing-up-an-etcd-cluster)  
[Assign Pods to Nodes using Node Affinity](https://kubernetes.io/docs/tasks/configure-pod-container/assign-pods-nodes-using-node-affinity/)  
[Taints and Tolerations](https://kubernetes.io/docs/concepts/scheduling-eviction/taint-and-toleration/)  
[Upgrading kubeadm clusters](https://kubernetes.io/docs/tasks/administer-cluster/kubeadm/kubeadm-upgrade/)  
[Assigning Pods to Nodes](https://kubernetes.io/docs/concepts/scheduling-eviction/assign-pod-node/#inter-pod-affinity-and-anti-affinity)  
[Volumes](https://kubernetes.io/docs/concepts/storage/volumes/#types-of-volumes)  
[Create static Pods](https://kubernetes.io/docs/tasks/configure-pod-container/static-pod/)  
[JSONPath Support](https://kubernetes.io/docs/reference/kubectl/jsonpath/)  
[Webhook Mode](https://kubernetes.io/docs/reference/access-authn-authz/webhook/)  
[Configure Liveness, Readiness and Startup Probes](https://kubernetes.io/docs/tasks/configure-pod-container/configure-liveness-readiness-startup-probes/)  
[Authorization Overview](https://kubernetes.io/docs/reference/access-authn-authz/authorization/)  
[Expose Pod Information to Containers Through Environment Variables](https://kubernetes.io/docs/tasks/inject-data-application/environment-variable-expose-pod-information/)  
[Secrets](https://kubernetes.io/docs/concepts/configuration/secret/#use-case-as-container-environment-variables)  
[Creating a cluster with kubeadm](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/create-cluster-kubeadm/#join-nodes)  
[kubeadm join](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm-join/)  
[Certificates](https://kubernetes.io/docs/tasks/administer-cluster/certificates/)  
[Operating etcd clusters for Kubernetes](https://kubernetes.io/docs/tasks/administer-cluster/configure-upgrade-etcd/)  
[Configure Service Accounts for Pods](https://kubernetes.io/docs/tasks/configure-pod-container/configure-service-account/)  
[Access Clusters Using the Kubernetes API](https://kubernetes.io/docs/tasks/administer-cluster/access-cluster-api/)  
[Configure a Pod to Use a ConfigMap](https://kubernetes.io/docs/tasks/configure-pod-container/configure-pod-configmap/#populate-a-volume-with-data-stored-in-a-configmap)  
[Network Policies](https://kubernetes.io/docs/concepts/services-networking/network-policies/#sctp-support)  
[Troubleshoot Clusters](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-cluster/)  
[Configure a Pod to Use a PersistentVolume for Storage](https://kubernetes.io/docs/tasks/configure-pod-container/configure-persistent-volume-storage/#create-a-persistentvolume)  
[Accessing the Kubernetes API from a Pod](https://kubernetes.io/docs/tasks/run-application/access-api-from-pod/)  
[Debug Services](https://kubernetes.io/docs/tasks/debug-application-cluster/debug-service/)  
[DNS for Services and Pods](https://kubernetes.io/docs/concepts/services-networking/dns-pod-service/)  
[TLS bootstrapping](https://kubernetes.io/docs/reference/command-line-tools-reference/kubelet-tls-bootstrapping/)  
