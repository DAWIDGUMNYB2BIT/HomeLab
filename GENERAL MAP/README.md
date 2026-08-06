# General Map

This section provides an overview of my HomeLab infrastructure.

## Infrastructure Diagram

![HomeLab Infrastructure Diagram](Infrastructure-Diagram.png)

## Network Topology

![HomeLab Network Topology](Network-Topology.png)

## Hardware Overview

### Server
- Dell PowerEdge R740
- Proxmox VE
- RAID storage
- iDRAC Enterprise

### Laptop
- Dell Latitude 7490
- Ubuntu 24.04 LTS

### Routers
- GL.iNet Flint 2
- Teltonika RUT955

### Single-board computer
- Raspberry Pi 5
- Ubuntu Server

### Network devices
- Dell Micro PC
- IP Camera
- Smart Plug

### Virtual Machines
- Ubuntu Server
- Ubuntu Desktop
- Windows Server
- Windows 11

# # Technical Skills & Learning Journey

This section summarizes the technologies I have explored, the practical skills I have developed, and the areas I am currently improving through my HomeLab.

Everything in this repository has been built, configured, tested and documented in my own homelab. My focus is understanding how technologies work together rather than simply following tutorials.

---

## ✅ Completed

### Linux

- Installed and configured Ubuntu Server and Ubuntu Desktop
- Built headless Linux servers for remote administration
- Configured SSH authentication using public keys
- Configured PAM authentication and USB fingerprint login
- Managed software repositories and packages using APT
- Recovered Linux systems using Live USB and GParted
- Configured multi-boot environments for Linux and Windows
- Diagnosed and resolved Linux networking and service issues

### Networking
- Built a multi-site WireGuard VPN infrastructure
- Configured site-to-site VPN tunnels
- Implemented VPN routing through a VPS
- Configured VLAN segmentation
- Configured static routing
- Configured OpenWrt and RutOS routers
- Managed Cisco Catalyst 2960XR and HP ProCurve switches
- Performed network diagnostics and troubleshooting
- Configured secure SSH remote administration

### Virtualization

- Installed and configured Proxmox VE
- Created and managed virtual machines
- Installed and configured Windows Server, Windows 11, Ubuntu Server and Ubuntu Desktop VMs
- Configured GPU Passthrough
- Configured virtual networking and bridges
- Configured Proxmox Firewall
- Managed storage and RAID integration
- Configured secure remote management using iDRAC and VPN
- Managed Proxmox repositories and no-subscription updates

### Remote Infrastructure

- Built and managed a remote HomeLab infrastructure
- Configured Dell PowerEdge R740 as the primary virtualization server
- Configured Dell OptiPlex Micro for remote administration
- Configured Raspberry Pi 5 for headless operation and remote management
- Deployed and managed a Linux VPS for VPN connectivity and infrastructure services
- Configured Wake-on-LAN for remote power management
- Automated power control using Wi-Fi Smart Plugs
- Configured Moonlight / Sunshine for low-latency remote desktop and game streaming
- Integrated scrcpy for Android device management
- Configured Android hotspot (Poco F6) for mobile remote infrastructure access

### Automation

- Developed Bash scripts to automate administrative tasks
- Built automation workflows using Ansible
- Implemented Google Drive API for automated file synchronization
- Configured automated backup solutions for Linux systems and network devices
- Automated SSH-based remote administration and management
- Developed scripts for infrastructure diagnostics and monitoring

### Security

- Configured SSH hardening and public key authentication
- Configured firewall rules for Linux, OpenWrt and Proxmox
- Built secure WireGuard VPN connectivity between multiple locations
- Configured secure remote access to infrastructure
- Performed wireless security testing in a personal lab
- Used Wi-Fi monitor mode for network analysis and security testing


### Documentation

- Created infrastructure diagrams
- Designed network topology diagrams
- Documented HomeLab projects and configurations
- Maintained technical documentation on GitHub
- Documented troubleshooting processes and implemented solutions

---

## 🚧 Currently Learning

- Windows Server administration
- Active Directory
- Group Policy
- Advanced Bash scripting
- Ansible automation
- Docker
- Monitoring and logging
- Infrastructure documentation

---

## 📚 Planned

- Kubernetes
- Terraform
- Prometheus
- Grafana
- CI/CD
- High Availability
- Cloud infrastructure (AWS / Azure)
- Infrastructure as Code
