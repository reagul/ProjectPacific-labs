# ProjectPacific-labs

Command to Login to Clusters

kubectl vsphere login –server=192.168.0.65 --vsphere-username=administrator@vsphere.local --insecure-skip-tls-verify


kubectl vsphere login --server=<Supervisor cluster API endpoint> -u <user with proper rights> --tanzu-kubernetes-cluster-name=<Tanzu Kubernetes cluster name> --tanzu-kubernetes-cluster-namespace=<Namespace in which the cluster is created>
Example:
kubectl vsphere login –server=192.168.0.65 --vsphere-username=administrator@vsphere.local --insecure-skip-tls-verify --tanzu-kubernetes-cluster-namespace=sajaldemo1 --tanzu-kubernetes-cluster-name=cluster1
