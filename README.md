# Rancher-Cluster-Management
This repo consist setting up Rancher &amp; configurations to manage.

### Table of Contents

* [01-What is Rancher?](https://www.rancher.com/why-rancher)
* [02-Instaling Rancher](https://www.rancher.com/quick-start)
* [03-Importing an Existing Cluster](https://ranchermanager.docs.rancher.com/v2.0-v2.4/how-to-guides/new-user-guides/kubernetes-clusters-in-rancher-setup/import-existing-clusters#importing-a-cluster)
* [04-Creating AKS Cluster](https://ranchermanager.docs.rancher.com/how-to-guides/new-user-guides/kubernetes-clusters-in-rancher-setup/set-up-clusters-from-hosted-kubernetes-providers/aks)
* [05-Creating EKS](https://ranchermanager.docs.rancher.com/how-to-guides/new-user-guides/kubernetes-clusters-in-rancher-setup/set-up-clusters-from-hosted-kubernetes-providers/eks)
* [06-Creating GKE](https://ranchermanager.docs.rancher.com/how-to-guides/new-user-guides/kubernetes-clusters-in-rancher-setup/set-up-clusters-from-hosted-kubernetes-providers/gke)
* [07-Official Docs](https://ranchermanager.docs.rancher.com/pages-for-subheaders/new-user-guides)
* [08-Managing AuthN, AuthZ & RBAC](https://ranchermanager.docs.rancher.com/pages-for-subheaders/authentication-permissions-and-global-configuration)
* [09-Managing a Deployment from scratch using Rancher](https://medium.com/omnius/kubernetes-deployment-using-rancher-3a9b8d97e7da)

> **Note:** Make sure to set Rancher Server URL that
Kubernetes cluster can communicate

> - In my current setup I'm running Docker on WSL2
> - Using Kind to create a One-Master Two-Worker Node Cluster
> - So I'm using my **docker network driver's** IP address as Rancher Server's IP
    

