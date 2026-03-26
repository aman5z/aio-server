
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

<img width="1920" height="967" alt="PX macOS" src="https://github.com/user-attachments/assets/f74f5707-9550-4607-aff1-a274e126a770" />

<img width="1919" height="1079" alt="Screenshot 2026-03-06 130756" src="https://github.com/user-attachments/assets/e132869b-b962-48bf-b9a8-a1b685e3e9af" />

![IMG_20241203_192142](https://github.com/user-attachments/assets/ab26cb7f-4432-414b-a70b-e3d4e3ff6918)

![Screenshot_20251011_192044_Brave](https://github.com/user-attachments/assets/153c0c87-5760-476a-a548-21beae0d7eb3)

![IMG_20241221_134233](https://github.com/user-attachments/assets/6898d2a3-cc35-449b-9129-774f977b7bda)

![IMG_20241203_163119](https://github.com/user-attachments/assets/d2819a77-3652-4fd6-b082-d11e16446a05)

![IMG-20251214-WA0000](https://github.com/user-attachments/assets/f04c9761-c0ec-45e5-a3eb-7c80c0b0c3ef)

![IMG_20241221_134223](https://github.com/user-attachments/assets/6e072507-e5e0-459d-a9ba-e2d8067b9a90)



