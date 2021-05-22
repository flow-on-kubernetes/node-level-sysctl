Allows you to configure [node-level sysctls](https://kubernetes.io/docs/tasks/administer-cluster/sysctl-cluster/#setting-sysctls-for-a-pod).
Useful for setting Linux kernel parameters which are not namespaced and so not supported by Kubernetes.

A simpler version of [cluster-node-tuning-operator](https://github.com/openshift/cluster-node-tuning-operator).
