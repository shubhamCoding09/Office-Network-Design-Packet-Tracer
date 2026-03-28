# 🏢 Office Network Design using VLAN, DHCP and Inter-VLAN Routing

## 📌 Project Overview
This project simulates a real-world office network using Cisco Packet Tracer.  
The network is divided into multiple departments (HR, IT, Sales) using VLANs for better security and performance.

---

## 🎯 Objectives
- Implement VLAN for network segmentation  
- Configure DHCP for automatic IP assignment  
- Enable inter-VLAN communication using router  
- Understand real-world networking concepts  

---

## 🏗️ Network Topology
- 1 Router (2911)  
- 1 Switch (2960)  
- 6 PCs (2 per department)  

Departments:
- HR → VLAN 10  
- IT → VLAN 20  
- Sales → VLAN 30  

---

## 🌐 IP Addressing Scheme

| Department | VLAN | Network | Gateway |
|------------|------|---------|---------|
| HR         | 10   | 192.168.10.0 | 192.168.10.1 |
| IT         | 20   | 192.168.20.0 | 192.168.20.1 |
| Sales      | 30   | 192.168.30.0 | 192.168.30.1 |

---

## ⚙️ Features
- VLAN segmentation  
- DHCP configuration  
- Inter-VLAN routing (Router-on-a-Stick)  
- Network troubleshooting  

---

## 🧪 Testing
- Devices received IP via DHCP  
- Ping successful between all VLANs  
- Network fully functional  

---

## ⚠️ Issues Faced
- APIPA (169.254.x.x) due to DHCP issue  
- Trunk configuration missing  
- Incorrect default gateway  

---

## 📸 Screenshots
(Add your Packet Tracer screenshots here)

---

## 📚 Learning Outcome
- Practical understanding of VLAN  
- Hands-on routing configuration  
- Troubleshooting real network issues  

---

## 🔗 Tools Used
- Cisco Packet Tracer  
