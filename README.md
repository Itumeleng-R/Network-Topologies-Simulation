<div align="center">

# 🌐 **Network Topologies Simulation**
Cisco Packet Tracer project – Network Topologies, Hybrid Design, VLAN, Subnetting, and Configurations  
### *Cisco Packet Tracer | IPv4 & IPv6 | VLAN | Subnetting | Hybrid Design*

![Network Animation](https://user-images.githubusercontent.com/74316400/216833854-f9a1e1d2-5481-46e3-89f2-12b2a0a6a65c.gif)

[![Cisco Packet Tracer](https://img.shields.io/badge/Cisco-Packet%20Tracer-blue?logo=cisco&logoColor=white)]()
[![IPv4](https://img.shields.io/badge/IPv4-Configured-brightgreen)]()
[![IPv6](https://img.shields.io/badge/IPv6-Dual--Stack-orange)]()
[![VLAN](https://img.shields.io/badge/VLAN-Segmented-yellow)]()
[![Server](https://img.shields.io/badge/Server-DHCP%2FDNS%2FHTTP-lightblue)]()
[![Security](https://img.shields.io/badge/Security-Firewall%20%26%20Access%20Control-red)]()
[![GitHub](https://img.shields.io/badge/Repository-Active-success)]()

</div>

---

## 📌 **Project Overview**

This project demonstrates the design, simulation, and configuration of multiple **network topologies** using **Cisco Packet Tracer**.  
It includes IPv4/IPv6 configuration, VLAN segmentation, DHCP/DNS/HTTP server setup, and a **hybrid topology** that integrates all designs into one cohesive network.

---

## 🖧 **Implemented Topologies**

| Topology | Devices | VLAN | Department | Status |
|-----------|----------|-------|-------------|--------|
| 🚌 **Bus** | 4 Switches, 4 PCs | VLAN 50 | Staff | ✅ Implemented |
| ⭐ **Star** | 1 Switch, 8 PCs | VLAN 20 | Students | ✅ Implemented |
| 🔄 **Ring** | 5 Switches, 5 PCs | VLAN 10 | Faculty | ✅ Implemented |
| 🔗 **Mesh** | 4 Switches, 4 PCs | VLAN 30 | Guests | ✅ Implemented |
| 🌟 **Extended Star** | 5 Switches, 12 PCs | VLAN 99 | Management/Native | ✅ Implemented |
| ⚡ **Hybrid (IPv4 + IPv6 + VLAN + Server)** | Integrated All | All | All | ✅ Implemented |

---

## ⚙️ **Configured Features**

- 🌍 **Dual-Stack Networking (IPv4 & IPv6)**
- 🧱 **VLAN Segmentation** for department isolation
- 🔐 **Firewall Security (Cisco ASA 5506-X)**
- 🧩 **DHCP, DNS & HTTP** servers configured on Server-PT
- 🧠 **Subnetting** with detailed IP planning
- 🧮 **Inter-VLAN Routing** via Router-on-a-Stick

---

## 🌈 **Repository Structure**

📁 Network-Topologies-Simulation/

├── 📄 README.md  
├── 📁 docs/  # Documentation (IP tables, configs, reports)  
├── 📁 simulations/ # Cisco Packet Tracer .pkt files  
├── 📁 screenshots/ # Network diagrams & results  
├── 📁 subnetting/  # Subnetting plans & configs  
└── 📁 video/       # Demo video link  

---

## 🧩 **Hybrid Network Overview**

The **Hybrid Topology** connects all five topologies through a **core mesh backbone** (6 switches), linked to a **Cisco ASA 5506-X firewall** for DHCP, NAT, and access control.  
A secondary subnet hosts:
- 🖥️ 1 Server-PT (HTTP/DNS/DHCP)
- 🧠 2 Switches connected to a Router
- 💻 2 PCs and 2 Laptops per switch

![Hybrid Topology](./screenshots/hybrid_topology.png)

---

## 🧮 **Subnetting Summary**

| VLAN | Department | Topology | IPv4 Subnet | IPv6 Subnet | Devices |
|------|-------------|-----------|--------------|--------------|----------|
| 10 | Faculty | Ring | 192.168.10.0/24 | 2001:DB8:3C4D:10::/64 | 5 |
| 20 | Students | Star | 192.168.20.0/24 | 2001:DB8:3C4D:20::/64 | 8 |
| 30 | Guests | Mesh | 192.168.30.0/24 | 2001:DB8:3C4D:30::/64 | 4 |
| 50 | Staff | Bus | 192.168.50.0/24 | 2001:DB8:3C4D:50::/64 | 4 |
| 99 | Management | Extended Star | 192.168.99.0/24 | 2001:DB8:3C4D:99::/64 | 12 |

---

## 🗓️ **Project Timeline & PND**

Below is the **Mini-Networking Project 2025** timeline represented through a detailed **Project Network Diagram (PND)**.  
It outlines major milestones, dependencies, and the final submission date (**October 13, 2025**).

#### 📊 Project Network Diagram (PND)
![Mini-Networking Project 2025 PND](./screenshots/4e0e5b53-3cbd-4ad8-95bf-3144c6295a57.jpg)

> **Legend:**
> - 🟦 **Task** – Represents each project stage.  
> - 🔶 **Checkpoint (Milestone)** – Marks completion of a key topology or test.  
> - ❌ **Critical Deadline** – Indicates submission or non-negotiable target dates.  
> - ➡️ **Dependencies** – Show the order and relationship of tasks.

---

## 💾 **Example Configuration Snippets**

```bash
# VLAN Configuration
Switch(config)# vlan 10
Switch(config-vlan)# name Faculty
Switch(config)# interface range fa0/1-5
Switch(config-if-range)# switchport access vlan 10

# Router-on-a-Stick (Dual-Stack)
Router(config)# interface g0/0.10
Router(config-subif)# encapsulation dot1Q 10
Router(config-subif)# ip address 192.168.10.1 255.255.255.0
Router(config-subif)# ipv6 address 2001:DB8:3C4D:10::1/64
✅ Testing & Verification

Test	Result
IPv4 Inter-VLAN Ping	✅ Successful
IPv6 Global Unicast Ping	✅ Successful
DHCP Address Assignment	✅ Working
DNS & HTTP Server Access	✅ Verified
Firewall Security Filter	✅ Configured

📸 Screenshot Highlights

Category	Screenshot	Description
🧩 Hybrid Overview		Full hybrid view
🔌 VLAN Config		VLAN assignments
🌍 IPv6 Setup		Dual-stack setup
🖥️ DHCP Test		Successful IP allocation
📊 Subnet Plan		IPv4/IPv6 subnet tables

🎥 Video Demo
📺 Watch the demo here (To be uploaded)

📑 Documentation
📘 IP Addressing Tables
⚙️ Configurations

👨‍💻 Author
🧑‍💻 Course: CMPG 325 – Computer Networks
🏫 Institution: North-West University
📅 Submission Date: 13 October 2025
👨‍🎓 Student: Itumeleng Twala
✉️ Contact: twalareagile@gmail.com

✨ “Networks connect devices — design connects possibilities.”

</div> ```
