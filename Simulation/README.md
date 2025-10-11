<div align="center">

# ⚙️💻 Network Simulation Files 💻⚙️

![PacketTracerAnimation](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExb3cwNDFqb21vYzA2ZmlwN3hkbW9pbnZneTV6ZmR1NG5wdm0zZWR2cyZlcD12MV9naWZzX3NlYXJjaCZjdD1n/fwbzI2kV3Qrlpkh59e/giphy.gif)

**Cisco Packet Tracer Simulations – CMPG325 | North-West University**  
*Hands-on network design and configuration using real-world topologies.*

---

</div>

# 🧩 Overview

This folder contains all **Cisco Packet Tracer (.pkt)** files for the **Network Topologies Simulation Project**.  
Each topology was individually designed, configured, and tested to demonstrate proper connectivity, VLAN segmentation, and dual-stack (IPv4/IPv6) communication.

---

## 🗂️ Folder Contents

| File Name | Description |
|------------|--------------|
| 🚌 **Bus_Topology.pkt** | Simulates the Bus topology with 4 switches and 4 end-user PCs connected in sequence. VLAN 50 (Staff). |
| ⭐ **Star_Topology.pkt** | Demonstrates centralized Star topology with 8 end-user PCs connected to a single switch. VLAN 20 (Students). |
| 🔄 **Ring_Topology.pkt** | Implements Ring topology with 5 switches and 5 PCs forming a circular link. VLAN 10 (Faculty). |
| 🔗 **Mesh_Topology.pkt** | Shows full Mesh interconnection between 4 switches and 4 PCs. VLAN 30 (Guest). |
| 🌟 **Extended_Star_Topology.pkt** | Extended Star design with 5 interconnected switches and 12 end-user PCs. VLAN 99 (Management & Native). |
| ⚡ **Hybrid_Topology.pkt** | Integrates all 5 topologies into a single hybrid design with dual-stack (IPv4/IPv6), VLANs, DHCP, and firewall configuration. |

---

## 🌐 Configuration Highlights

- **IPv4 Range:** `192.168.1.1 – 192.168.1.35/24`  
- **IPv6 Range:** `2001:DB8:3C4D::1 – 2001:DB8:3C4D::12/64`  
- **VLANs Configured:**
  - VLAN 10 – Faculty  
  - VLAN 20 – Students  
  - VLAN 30 – Guests  
  - VLAN 50 – Staff  
  - VLAN 99 – Management & Native  
- **DHCP Configured Firewall:** Cisco ASA 5506-X  
- **Servers:** HTTP, DNS, and DHCP enabled for hybrid subnet  
- **Connectivity:** Verified via ping tests (IPv4 & IPv6)

---

## 🧠 How to Use These Files

1. Open **Cisco Packet Tracer**.  
2. Go to `File → Open` and load any `.pkt` file.  
3. View device labels and connections.  
4. Enter configuration mode for routers, switches, or PCs to verify settings.  
5. Test connectivity using **Command Prompt → ping / ping6** commands.

---

## 📸 Suggested Screenshots

For GitHub visuals and your video:
- Topology overview  
- IP configuration (IPv4 & IPv6)  
- VLAN table view  
- Successful ping test results  

---
🔒 Security Features
🔐 Password protection (console, VTY)

🧱 Firewall (Cisco ASA 5506-X)

🚫 Disabled unused ports

🧾 Network banner warnings

## 🎓 Project Information

**👨‍💻 Author:** Itumeleng  
**🏫 University:** North-West University  
**📚 Course:** CMPG325 – Computer Networks  
**📅 Project Due:** 13 October 2025  
**✉️ Contact:** [twalareagile@gmail.com](mailto:twalareagile@gmail.com)

---

<div align="center">

> 💡 *“Networks that simulate today, build tomorrow’s infrastructure.”* 💡  

![Switch Animation](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExNnRqZ2oyY3g1YXhtdXQ3aXJ5YWcxbmhjcWc2YzFwZnZ4aGt1bjlzNCZlcD12MV9naWZzX3NlYXJjaCZjdD1n/Bzzb7RTu9O3bW/giphy.gif)

</div>
