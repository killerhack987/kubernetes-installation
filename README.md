# kubernetes-installation
Script to setup kubernetes worker node

# Environment preparation for the Kubernetes

```
git clone https://github.com/skywood123/kubernetes-installation.git
cd kubernetes-installation
sudo bash installation_script.sh
```
Summary tasks done in this script:
1)Enable br_netfilter module
2)Disable swap
3)Install container runtime (Docker)
4)Install kubeadm,kubectl,kubelet (1.19.3)
5)Install NFS client
