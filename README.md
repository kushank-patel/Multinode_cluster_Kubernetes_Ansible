# Multinode_cluster_Kubernetes_Ansible
## What is Kubernetes ?
Kubernetes is an open source container orchestration engine for automating deployment, scaling, and management of containerized applications. The open source project is hosted by the Cloud Native Computing Foundation.

* Steps for the configuration of master in kubernetes cluster.
1. Install docker (As we are using Amazon Linux 2 image so we don’t need to configure repo for docker).
2. Start docker.
3. enable docker.
4. Configure Kubernetes Repo.
5. Install Kubeadm (it will automatically install kubectl and kubelet).
6. enable kubelet.
7. pull docker images using kubeadm.
8. change driver of docker from cgroupfs to systemd.
9. restart docker.
10. Installing iproute-tc.
11. Setting bridge-nf-call-iptables to 1.
12. Initializing Master.
13. Creating .kube directory.
14. Copying /etc/kubernetes/admin.conf $HOME/.kube/config.
15. changing owner permission of $HOME/.kube/config.
16. Creating Flannel.
17. Generating Token.


