# 📅 Containerization Class – 20 February

## 📌 Topic: Docker Networking (Swarm, Overlay & IPVLAN)

### 🔗 Reference Link
https://upessocs.github.io/#dir=/Lectures/Containerization%20and%20DevOps/Theory/&file=202%20Networking%20in%20Docker%2021%20-%2022.md

---

## 📝 Class Tasks

### ✅ Task 1: Initialize Docker Swarm
Docker Swarm was initialized to enable cluster mode for managing multiple containers.

![Swarm Initialization](theory%20images/20feb/a.png)

---

### ✅ Task 2: Create Overlay Network & Container Communication
An overlay network was created to allow communication between containers running on different nodes.Containers were deployed on the overlay network and their connectivity was tested.

![Overlay Network Creation](theory%20images/20feb/b.png)

---

### ✅ Task 3:  IPVLAN Setup


IPVLAN networking was also studied to understand how containers can directly connect to the host network for better performance.

![Container Networking and IPVLAN](theory%20images/20feb/c.png)

---

## 📖 Summary

- Initialized Docker Swarm using `docker swarm init`
- Created overlay network
- Deployed containers in Swarm mode
- Tested container-to-container communication
- Studied IPVLAN networking concept
- Learned advanced Docker networking

---

✅ This experiment focused on understanding Swarm, Overlay, and IPVLAN networking.
