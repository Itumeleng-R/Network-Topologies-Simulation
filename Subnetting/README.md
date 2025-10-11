# 🌐 Subnetting Configurations  
![IPv4](https://img.shields.io/badge/IPv4-Enabled-blue?style=for-the-badge&logo=cisco)
![IPv6](https://img.shields.io/badge/IPv6-Ready-green?style=for-the-badge&logo=internetexplorer)
![Cisco Packet Tracer](https://img.shields.io/badge/Built%20With-Cisco%20Packet%20Tracer-1E90FF?style=for-the-badge&logo=cisco)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge&logo=checkmarx)

---

## 📘 Overview
Subnetting plays a vital role in **dividing large networks** into smaller, more efficient segments.  
This enhances **network performance**, **security**, and **management** across topologies.

The subnetting plan here supports:
- IPv4 and IPv6 configuration  
- VLAN assignments  
- Departmental segmentation within the hybrid topology  

---

## 🧮 IPv4 and IPv6 Planning

| Parameter | IPv4 | IPv6 |
|------------|------|------|
| Address Range | 192.168.10.0 – 192.168.10.255 | 2001:0db8:acad::/64 |
| Subnet Mask / Prefix | /26, /27, /28 | /64, /66, /68 |
| Total Subnets | 3 | 3 |
| Hosts per Subnet | 62–14 hosts | Virtually unlimited |
| Purpose | LAN segmentation | Scalability & IPv6 transition |

---

## 📁 Folder Structure

📦 subnetting/

┣ 📜 README.md

┣ 📄 IPv4_Subnetting_Config.txt

┣ 📄 IPv6_Subnetting_Config.txt

┣ 📊 Subnet_Calculations.xlsx

┣ 🧾 IP_Plan_Report.pdf

┗ 🖼️ Subnet_Plan_Diagram.png

yaml
Copy code

---

## ⚙️ Configuration Steps

1️⃣ Identify required number of subnets  
2️⃣ Apply appropriate subnet masks  
3️⃣ Assign IP ranges to VLANs/departments  
4️⃣ Configure IPv4/IPv6 on routers and switches  
5️⃣ Test reachability using:
   ```bash
   ping 192.168.x.x
   ping 2001:db8::1
🚀 Benefits
✅ Efficient IP utilization

✅ Simplified routing and troubleshooting

✅ Enhanced scalability

✅ Dual-stack (IPv4 + IPv6) support
