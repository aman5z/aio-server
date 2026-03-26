AIO-Server-Turning-an-Old-HP-Laptop-into-a-Multi-OS-Virtualization-Platform
# 🏗️ Unified Infrastructure Project

## Villa Network + Virtualized Home Lab Server (NOC Simulation)

A practical, real-world IT infrastructure project combining **multi-villa network deployment** with a **self-hosted virtualization server and monitoring system**, simulating a small-scale **Network Operations Center (NOC)** using low-cost hardware.

---

## 🌐 Project Overview

Designed and deployed a **cost-effective, scalable network and monitoring solution** across:

* 🏠 3 Villa Compounds
* 🚪 42 Rooms
* 👥 160+ Active Users

At the core of the system, an **old HP laptop was repurposed as a centralized server**, running multiple services including monitoring, virtualization, and internal network tools.

---

## 🖥️ Core Infrastructure (AIO Server)

Repurposed an old HP laptop into a **multi-service infrastructure server**:

### 🔧 Hardware Optimization

* Upgraded to SSD + increased RAM
* Modified power button for headless operation
* Used Ethernet bridging for stable connectivity

### 🧠 Virtualization Platform

* Installed **Proxmox VE**
* Deployed multiple VMs:

  * Ubuntu Server / Desktop
  * Windows 11 & Windows Server
  * Kali Linux
  * Android TV OS
* Configured LXC containers for lightweight services
* Enabled backups, snapshots, and remote VNC access

👉 This server acted as:

* Monitoring backend
* Internal service host
* Testing lab
* Network control point

---

## 📡 Villa Network Deployment

### 🔌 Network Design & Setup

* Configured routers, switches, and access points
* Designed WiFi coverage across multi-floor villas
* Optimized placement for signal strength & load distribution
* Worked under strict budget constraints

### 📊 Results

✔ Improved network stability
✔ Reduced downtime
✔ Better bandwidth distribution
✔ Increased user satisfaction

---

## 🖥️ Custom Network Monitoring Dashboard (Mini NOC)

Developed a **lightweight monitoring dashboard** (Vanilla JavaScript) hosted on the same server.

### 🎯 Objective

Simulate a **real-world NOC interface** without heavy infrastructure.

---

## 🌐 WAN Monitoring (Internet)

* Embedded Fast.com speed test
* Public uptime monitoring
* External network status tracking

👉 Helps detect:

* ISP issues
* Internet slowdowns
* Downtime events

---

## 🏠 LAN Monitoring (Internal Network)

* Local speed test service
* Internal monitoring endpoints
* LAN-only tools (192.168.x.x access)

👉 Provides:

* Internal performance visibility
* Service availability checks
* Network diagnostics within villas

---

## 🎛️ Dashboard Features

* Dark-mode UI
* Floating quick-access menu
* Real-time clock
* Blogger-based lightweight hosting
* Embedded monitoring tools

👉 Built to be:

* Fast
* Lightweight
* Accessible without backend complexity

---

## 🔐 Remote Access & Security

* Implemented **Cloudflare Tunnel** for secure remote access
* Used **Tailscale VPN (WireGuard)** for private network connectivity
* Enabled remote SSH, ping, and service access across devices

---

## ☁️ Additional Services on Server

* Private cloud storage (Nextcloud / OMV)
* Media servers (Plex, Jellyfin)
* IoT control (Tasmota-based devices)
* VoIP system (Asterisk + FreePBX)
* Web server for hosting internal tools

---

## 🧠 Concepts Applied

* LAN vs WAN architecture
* Private vs Public IP segmentation
* Network monitoring & observability
* Virtualization & resource management
* Infrastructure centralization
* Endpoint/service testing
* Secure remote access (VPN + tunnels)

---

## 🔥 Skills Demonstrated

* Networking (routing, subnetting, WiFi design)
* Linux server administration
* Virtualization (Proxmox, VMs, LXC)
* Network monitoring & troubleshooting
* VPN & secure access (WireGuard, Cloudflare)
* Web development (Vanilla JS dashboard)
* IoT integration
* VoIP setup (Asterisk/FreePBX)
* Infrastructure design under budget constraints

---

## 📈 Key Learning Outcomes

* Practical subnetting & IP planning
* Real-world network deployment challenges
* Monitoring system design
* REST API & frontend integration
* Troubleshooting large user environments
* Performance optimization

👉 Most importantly:
**Transitioned from using tools → building complete systems**

---

## 🚀 Future Enhancements

* Prometheus + Grafana monitoring stack
* SNMP-based device monitoring
* Dockerized backend services
* Authentication layer (secure dashboard access)
* Progressive Web App (PWA)
* Cloud deployment (AWS / Azure)

---

## 💡 Project Impact

This project combines:

* **Real deployment (villa network)**
* **Self-hosted infrastructure (server lab)**
* **Custom monitoring system (NOC simulation)**

👉 Making it a **complete end-to-end IT infrastructure project**, not just a lab.



![IMG_20241203_192142](https://github.com/user-attachments/assets/7d128bf0-9e4d-48bf-ac27-666126aae4a8)

<img width="1886" height="881" alt="1GBs" src="https://github.com/user-attachments/assets/da4dba08-e3d8-4d66-9054-2252266a81bb" />

![Screenshot_20251011_192044_Brave](https://github.com/user-attachments/assets/c39c02c7-5532-4db1-b851-0cb5efd89389)

<img width="1920" height="967" alt="PX macOS" src="https://github.com/user-attachments/assets/428d6f5e-89b9-4624-bacb-d1ffd9263634" />

<img width="1916" height="878" alt="Pi-Hole DB 300k Queries" src="https://github.com/user-attachments/assets/70bc7940-0a8b-4969-86e4-a306e6a5c039" />

![IMG-20251214-WA0000](https://github.com/user-attachments/assets/322cdd6c-8658-4ee7-8e38-4e10d752b2b5)

![IMG_20241221_134233](https://github.com/user-attachments/assets/7de9dc22-352d-4f18-a2ae-6241fe41adfd)

![IMG_20241221_134223](https://github.com/user-attachments/assets/34c542d9-32d1-4c73-951d-8b9cee7db5ff)


