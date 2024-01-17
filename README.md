# argocd-configurations

## Multicluster Configuration

gcloud container clusters list
### get the master node of cluster/try this command on every cluster

kubectl config get-contexts
### Get context on local machine

gcloud container clusters get-credentials west --zone us-west2-b
### Get context configuration on local of cluster/ get credentials for all clusters

kubectl config get-contexts
### The get-credentials configurations should be safed and named locally

kubectl config rename-context gke-xyz new-name
kubectl config get-contexts
### See the new context


