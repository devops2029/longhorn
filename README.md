# longhorn

Useful commands:

ln -s /var/lib/rancher/rke2/bin/kubectl /usr/local/bin/kubectl

mkdir -p ~/.kube

ln -s /var/lib/rancher/rke2/server/cred/admin.kubeconfig ~/.kube/config

kubectl get nodes -o wide

curl https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-3 | bash



For reference, this page provides examples of Kubernetes resources that use Longhorn storage.
Block volume
CSI persistent volume
Deployment
Pod with PersistentVolumeClaim
Pod with Generic Ephemeral Volume
Restore to file
Simple Pod
Simple PersistentVolumeClaim
StatefulSet
StorageClass

https://longhorn.io/docs/1.7.1/references/examples/

