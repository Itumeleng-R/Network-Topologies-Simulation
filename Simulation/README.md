## 🖧 **2️⃣ README for `/simulations/` folder (Enhanced Edition)**

```markdown
# 🧠 Network Simulations (Cisco Packet Tracer)
![Cisco Packet Tracer](https://img.shields.io/badge/Simulation-Cisco%20Packet%20Tracer-blue?style=for-the-badge&logo=cisco)
![IPv4 IPv6](https://img.shields.io/badge/IP%20Support-IPv4%20%26%20IPv6-00BFFF?style=for-the-badge&logo=internetexplorer)
![Network Ready](https://img.shields.io/badge/Network%20Design-Ready-green?style=for-the-badge&logo=databricks)
![VLAN](https://img.shields.io/badge/VLAN%20Support-Enabled-orange?style=for-the-badge&logo=ubuntu)

---

## 🎯 Objective
This directory contains all **Cisco Packet Tracer (.pkt)** simulation files representing  
the design and configuration of five major topologies and one hybrid topology.

Each simulation demonstrates:
- Network design  
- Device interconnection  
- VLAN segmentation  
- IPv4 and IPv6 addressing  
- Server configurations (DHCP, DNS, HTTP)  

---

## 🧩 Implemented Topologies

| Topology | Features | File |
|-----------|-----------|------|
| 🚌 **Bus** | Shared backbone communication | `bus_topology.pkt` |
| ⭐ **Star** | Central switch connectivity | `star_topology.pkt` |
| 🔄 **Ring** | Token passing concept | `ring_topology.pkt` |
| 🔗 **Mesh** | Redundant interconnected nodes | `mesh_topology.pkt` |
| 🌟 **Extended Star** | Multi-switch structure | `extended_star_topology.pkt` |
| ⚡ **Hybrid** | IPv4 + IPv6, VLANs, DHCP/DNS/HTTP, Firewall | `hybrid_topology.pkt` |

---

## 🧱 VLAN Configuration Summary

| VLAN | Purpose | Assigned Topology |
|------|----------|------------------|
| 10 | Faculty | Ring |
| 20 | Students | Star |
| 30 | Guests | Mesh |
| 50 | Staff | Bus |
| 99 | Management (Native VLAN) | Extended Star |

---

## ⚙️ How to Use

1️⃣ Open `.pkt` files in **Cisco Packet Tracer v8.2+**  
2️⃣ Explore configurations on switches, routers, and servers  
3️⃣ Test network connectivity:
   ```bash
   ping 192.168.x.x
   ping 2001:db8::2
   show vlan brief
4️⃣ Modify or extend to simulate your own scenarios

🖼️ Visualization
See detailed diagrams and screenshots in the /screenshots/ folder.
Each image represents the topology’s layout, connections, and VLAN color mappings.

🔒 Security Features
🔐 Password protection (console, VTY)

🧱 Firewall (Cisco ASA 5506-X)

🚫 Disabled unused ports

🧾 Network banner warnings
