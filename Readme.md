### Gitops Test Repo
Git is the single source(CI) of truth with AgroCD (CD) to continuously delivery of latest changes in code for the k8s cluster.

#### Install ArgoCD in k8s cluster with this command

`kubectl create namespace argocd`

`kubectl apply -n argocd -f https://raw.githubusercontent.com/argoproj/argo-cd/stable/manifests/install.yaml`
