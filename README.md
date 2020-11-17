# kubernetes-installation
Script to setup kubernetes worker node

***For a more complete documentation, please refer to official documentation [kubernetes](https://kubernetes.io/docs/setup/production-environment/tools/kubeadm/install-kubeadm/).***

# Environment preparation for the Kubernetes

```
git clone https://github.com/skywood123/kubernetes-installation.git
cd kubernetes-installation
sudo bash installation_script.sh
```
Summary tasks done in this script:
- Enable br_netfilter module\n
- Disable swap
- Install container runtime (Docker)
- Install kubeadm,kubectl,kubelet (1.19.3)
- Install NFS client
