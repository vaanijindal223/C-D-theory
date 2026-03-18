# 📅 Containerization Class – 18 March

## 🎯 Topic: Kubernetes Setup using kubectl & k3d

# 🗓️ Class Task — 18 March: Kubernetes (kubectl & k3d)

---

## Overview
Today we installed `kubectl` and `k3d`, created a lightweight Kubernetes cluster with `k3d`, verified the nodes, and confirmed the cluster was reachable from the local Docker daemon.

---

## Screenshot 1 — Install `kubectl` & `k3d`
Shows the installation commands used to install `kubectl` and `k3d` on the machine.  
![Install kubectl and k3d](theory%20images/18march/a.png)

---

## Screenshot 2 — Create `k3d` cluster
Shows the `k3d cluster create` command used to create the cluster and the creation output (nodes, ports, etc.).  
![Create k3d cluster](theory%20images/18march/b.png)

---

## Screenshot 3 — Verify cluster / nodes
Shows commands and output verifying the cluster and nodes (for example `kubectl get nodes` and `kubectl cluster-info`).  
![Verify cluster and nodes](theory%20images/18march/c.png)

---

## Screenshot 4 — Docker daemon & cluster interaction
Shows starting the Docker daemon (if needed) and a sample `kubectl` command run to confirm workloads / pods are running.  
![Docker daemon + kubectl output](theory%20images/18march/d.png)

---

