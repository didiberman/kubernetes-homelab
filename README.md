# 🧪 Kubernetes Homelab (GitOps + Flux)

Welcome to my Kubernetes Homelab!  
This repo is my public learning space for mastering Kubernetes, GitOps, and modern cloud-native DevOps tools.

I'm currently self-training in production-grade deployment practices using:
- 🐳 **K3s** as my lightweight Kubernetes distribution  
- 🚀 **Flux CD** for GitOps-style continuous delivery  
- ☁️ Cloud + local hybrid setup (AWS control plane + remote worker nodes)
- 🛠️ Eventually Argo CD, Helm, and advanced tooling

---

## 🎯 Goals

- Learn Kubernetes deeply by **running a real homelab cluster**
- Use **GitOps best practices** to manage the cluster state
- Deploy real workloads like **n8n**, custom APIs, and more
- Experiment with **multi-node clusters** across cloud & local machines

---

## 📦 Repo Structure

```bash
./clusters/my-cluster/
  └── kustomization.yaml        # Cluster-level configuration
  └── apps/                     # App manifests and Helm releases
      └── n8n/
      └── argocd/
  └── infrastructure/           # Flux, monitoring, networking
      └── flux-system/
