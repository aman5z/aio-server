# AIO-Server-Turning-an-Old-HP-Laptop-into-a-Multi-OS-Virtualization-Platform


<img width="1920" height="967" alt="PX macOS" src="https://github.com/user-attachments/assets/f74f5707-9550-4607-aff1-a274e126a770" />


Objective:

Repurpose old hardware (an HP laptop and Raspberry Pi) to create a fully functional, multi-OS virtualized environment with personal cloud storage, secure IoT integration, VoIP systems, and remote access—all protected by a robust security infrastructure that combines VPN, encryption, firewalls, and intrusion detection.
Project Overview:
I built an integrated solution combining cloud computing, cybersecurity, IoT automation, and private cloud storage using low-cost hardware like a Raspberry Pi 5 and an old HP i3 laptop. The project showcases my skills in virtualization, remote access with Cloudflare Tunnel and Tailscale VPN, cloud services, and penetration testing, all while using open-source tools.
Turning an Old HP Laptop into a Multi-OS Virtualization Platform:
I recently repurposed an old HP i3 laptop that had been idle due to outdated hardware. To bring it back to life, I upgraded the storage with an SSD, increased the RAM, and modified the power button to enable booting without opening the lid (since the laptop does not support Wake-on-LAN (WoL)). Initially, I kept the lid open for video output, but the modification allowed for a sleeker setup.
Installing Proxmox VE and Multiple Operating Systems
After the hardware upgrades, I installed Proxmox VE, a powerful virtualization platform. Using Proxmox, I configured and installed several operating systems including Ubuntu Server, Ubuntu Desktop, Kali Linux, Windows 11, Windows Server, and Android TV OS, along with a few LXC containers. Each virtual machine (VM) was set up with automatic backups and snapshots for easy management and disaster recovery.
I accessed all VMs through Proxmox’s built-in VNC feature, which can be used via any web browser, offering convenient access from anywhere.
Networking Setup
For network connectivity, I connected the HP laptop to my personal laptop using an Ethernet cable, leveraging the internet connection shared by the personal laptop. This ensures that the HP laptop stays consistently online and accessible within the network.
Additionally, I set up a Raspberry Pi 5 running UmbrelOS and CasaOS, connected to my network via both Ethernet and Wi-Fi. Several demo apps were installed on the Pi for testing purposes.
Remote Access with Cloudflare and Tailscale
To enable secure remote access, I installed Cloudflare Tunnel on both the HP laptop and the Raspberry Pi. This allows me to securely access these devices outside my home network through Cloudflare-generated links. I also created subdomains under my existing domain for easy access to each device via dedicated URLs.
I integrated Tailscale, using WireGuard for a seamless VPN solution. By connecting all my devices to Tailscale using my Gmail account, I gained access to my home network through IPv4 addresses assigned via the Tailscale dashboard. This setup was successfully tested across various platforms, including Windows and Android NetHunter, allowing full SSH and ping access to all hosts, such as Proxmox, UmbrelOS, and CasaOS, even when off-network.
Simplifying Access with WebToApp and Blogspot
To simplify access, I used WebToApp to convert IP addresses into APK files for direct access to services via mobile apps. I also created a Blogspot page to organize network links, offering LAN access for low latency and WAN access for remote use.
Virtualization & Cloud Computing:
Using Proxmox VE and multiple VMs, including Ubuntu Server, Kali Linux, Windows 11, macOS, and Android TV OS, alongside LXC containers. This allowed me to experience and run various OS without installing them directly on their hardware or consuming excessive resources from the host OS. I also configured Proxmox for cloud computing tasks, accessible via SSH or VNC from anywhere, ensuring flexibility and efficient resource utilization.

Networking & Remote Access:
I implemented Tailscale VPN (using WireGuard) and Cloudflare Tunnel for secure remote access to all devices, enabling control and monitoring of the system from any location. The network is bridged across Ethernet and Wi-Fi, allowing seamless communication between devices on the LAN and WAN.

Private Cloud Storage:
Attached a 500GB SSD to the Raspberry Pi 5 and set up personal cloud storage using Nextcloud and OpenMediaVault (OMV). This setup allows file access across multiple platforms, including Windows (via SMB), Linux, and Android, offering a private cloud solution with robust, secure data access.

Web Server & IoT Automation:
I configured a web server within the Proxmox environment to host personal projects and demos. For home automation, I used Tasmota to manage IoT devices locally on the LAN, and by integrating Tailscale and Cloudflare Tunnel, I can remotely monitor and control these devices securely.

Media Streaming & Proxy Browsing:
Plex and Jellyfin to stream media collection across devices within the network or remotely. I configured Firefox inside both CasaOS and UmbrelOS to act as a proxy browser for secure web browsing.

VoIP System Setup:
Asterisk and FreePBX, establishing VoIP system for local IVR and telephony. 
All Done for Free!
This project showcases the power of low-cost hardware, leveraging free, open-source software to create a fully functional cloud, virtualization, and automation environment—all done without any extra cost!
