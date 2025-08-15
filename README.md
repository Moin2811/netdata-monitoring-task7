---

## **Project Summary**

This project involves installing and running **Netdata** on an **Ubuntu EC2 instance** using **Docker** to monitor real-time system and container metrics. The setup uses host networking for easy access and displays live dashboards for CPU, memory, disk I/O, network traffic, and Docker container performance. The goal was to explore lightweight server monitoring for DevOps environments.

---

## **Steps Performed**

1. **Pulled the Netdata image** from Docker Hub.
2. **Ran Netdata container** with host networking and necessary mounts
3. **Verified container status** using `docker ps` and `curl` commands.
4. **Opened port 19999** in AWS Security Group for browser access.
5. **Accessed Netdata dashboard** via `http://<EC2-Public-IP>:19999`.
6. **Captured screenshots** of System Overview and Container metrics.

---
