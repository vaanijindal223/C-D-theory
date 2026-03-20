# 🗓️ Class Task — 20 March: Kubernetes (Portainer Setup & Volume)

---

## Overview
In this class, we worked with Kubernetes concepts and created a **Portainer volume** to manage container data persistently. This helps in handling container storage and management efficiently.

---

# PART 1: Kubernetes Setup

## Step 1: Kubernetes Environment Setup / Command Execution
![Kubernetes Setup](theory%20images/20march/a.png)

This screenshot shows Kubernetes-related setup/commands executed in the environment.  
It ensures that the cluster is ready and working before performing further operations.

---

# PART 2: Portainer Volume Creation

## Step 1: Create Portainer Volume
![Create Volume](theory%20images/20march/b.png)

This shows the command used to create a volume for Portainer.

Volumes are used to:
- Store persistent data
- Retain data even after container deletion
- Manage container storage efficiently

---

# Useful Commands


# Create Docker volume
docker volume create portainer_data

# List volumes
docker volume ls

# Inspect volume
docker volume inspect portainer_data
