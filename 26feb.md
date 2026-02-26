# 🧪 Class Task: 26 February – Multi Container & Scaling

---

# PART 1: Multi Container Scenario (WordPress + MySQL)

## Step 1: Setup Multi Container Application
![Multi Container Setup](theory%20images/26feb/a.png)

This screenshot shows WordPress and MySQL running together using docker-compose.

---

## Step 2: Error Due to Container Already in Use
![Container Error](theory%20images/26feb/b.png)

Error occurred because the container name and port were already in use.

---

## Step 3: Modify docker-compose.yml File
![Modify YML](theory%20images/26feb/c.png)

In this step:
- Removed `container_name: wordpress`
- Removed port `8080`
- Tried scaling again

---

# PART 2: Scaling WordPress Service

## Step 1: Scaling Command
![Scaling WordPress](theory%20images/26feb/d.png)

This shows the scaling command used to increase WordPress containers.

Command:
```bash
docker-compose up --scale wordpress=3
```

---

# PART 3: Web + Worker Setup

## Step 1: nginx.conf Configuration
![Nginx Config](theory%20images/26feb/e.png)

This screenshot shows the nginx.conf configuration file.

---

## Step 2: Updated docker-compose.yml File
![Updated Compose](theory%20images/26feb/f.png)

Updated docker-compose.yml file for web + worker architecture.

---

## Step 3: Scaling Commands Execution
![Scaling Commands](theory%20images/26feb/g.png)

This shows scaling commands executed successfully.

---

## Step 4: Final Output
![Final Output](theory%20images/26feb/h.png)

Final successful execution of multi-container scaled setup.

---







