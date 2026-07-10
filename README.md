<div align="center">

# 🌐 Enterprise Network Design & Implementation

### 🚀 Cisco Packet Tracer Enterprise Campus Network

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F62FE,100:00C853&height=180&section=header&text=Enterprise%20Network%20Lab&fontSize=40&fontColor=ffffff&animation=fadeIn"/>

<p>

![Cisco](https://img.shields.io/badge/Cisco-Packet%20Tracer-1BA0D7?logo=cisco&logoColor=white)
![Routing](https://img.shields.io/badge/Routing-OSPF-success)
![Switching](https://img.shields.io/badge/Switching-VLAN-blue)
![Security](https://img.shields.io/badge/Security-ACL%20%7C%20SSH-red)
![NAT](https://img.shields.io/badge/NAT-PAT-orange)
![License](https://img.shields.io/badge/License-MIT-brightgreen)
![Status](https://img.shields.io/badge/Status-Completed-success)

</p>

> **A production-inspired enterprise campus network implementing Cisco best practices for Routing, Switching, Security, Enterprise Services, and Network Management.**

</div>

---

# 📑 Table of Contents

- Overview
- Enterprise Topology
- Network Architecture
- Features
- VLAN Design
- IP Addressing
- Server Infrastructure
- Technologies
- Security
- Testing
- Repository Structure
- Future Improvements
- Author

---

# 📖 Overview

This project simulates a medium-sized enterprise campus network following Cisco's **Three-Tier Hierarchical Design Model**.

The implementation demonstrates practical enterprise networking concepts including:

- Layer 3 Switching
- Dynamic Routing
- Enterprise VLAN Design
- Secure Network Infrastructure
- Internal Server Farm
- Public Internet Services
- Enterprise Security
- Network Management

The primary objective is to build a scalable, secure, and manageable enterprise network similar to those used in real organizations.

---

# 🖼 Enterprise Network Topology

<p align="center">

<img src="diagrams/enterprise-topology.png" width="95%"/>

</p>

---

# 🏗 Architecture

```
                    Internet
                        │
                 Internet Router
                        │
                    ISP Router
                        │
                   Edge Router
                        │
              Layer-3 Core Switch
                 /              \
        Distribution       Distribution
            Switch             Switch
           /      \           /      \
      Access    Access   Access    Access

        Enterprise Campus Network
```

---

# 📊 Project Statistics

| Item | Count |
|------|-------|
| Routers | 3 |
| Layer 3 Switch | 1 |
| Distribution Switches | 2 |
| Access Switches | 4 |
| VLANs | 6 |
| Internal Servers | 3 |
| Public Servers | 3 |
| Departments | 5 |

---

# 🌐 Network Features

## Routing

- OSPF Dynamic Routing
- Static Default Route
- Inter-VLAN Routing
- Layer 3 Switching

---

## Switching

- VLAN Segmentation
- Trunk Links
- STP
- PortFast
- BPDU Guard

---

## Enterprise Services

- DHCP
- Internal DNS
- Public DNS
- HTTP
- FTP
- Mail
- File Server
- Syslog
- NTP
- Backup

---

## Security

- ACL
- NAT/PAT
- SSH
- Port Security
- Disabled Unused Ports
- VLAN Isolation

---

# 🏢 VLAN Design

| VLAN | Department | Network |
|------|------------|----------------|
|10|Management|192.168.10.0/24|
|20|Human Resources|192.168.20.0/24|
|30|Finance|192.168.30.0/24|
|40|IT|192.168.40.0/24|
|50|Sales|192.168.50.0/24|
|99|Server Farm|192.168.99.0/24|

---

# 🌍 WAN Addressing

| Link | Network |
|------|---------------|
|Internet ↔ ISP|198.51.100.0/30|
|ISP ↔ EDGE|203.0.113.0/30|
|EDGE ↔ CORE|10.255.255.0/30|

---

# 🖥 Enterprise Server Farm

| Server | Services |
|---------|--------------------------|
|SERVER-01|DNS, NTP, Syslog|
|SERVER-02|Web, FTP, File|
|SERVER-03|Mail, Backup|

---

# 🌎 Public Internet Services

| Service | IP |
|----------|----------------|
|DNS|198.51.101.10|
|Web|198.51.101.20|
|FTP|198.51.101.30|

---

# 🛠 Technologies Used

| Category | Technologies |
|-----------|------------------------------|
|Routing|OSPF|
|Switching|VLAN, STP, Trunking|
|Security|ACL, SSH, NAT/PAT, Port Security|
|Services|DHCP, DNS, HTTP, FTP, Mail|
|Management|Syslog, NTP|
|Platform|Cisco Packet Tracer|

---

# 🔐 Security Implementation

✅ Access Control Lists

✅ Secure Shell (SSH)

✅ Port Security

✅ BPDU Guard

✅ PortFast

✅ NAT/PAT

✅ Disabled Unused Ports

---

# 🧪 Testing & Validation

| Test | Status |
|------|--------|
|End-to-End Connectivity|✅|
|Inter-VLAN Routing|✅|
|OSPF Neighbor Formation|✅|
|DHCP Address Assignment|✅|
|DNS Resolution|✅|
|HTTP Access|✅|
|FTP Access|✅|
|SSH Login|✅|
|NAT Translation|✅|
|Port Security|✅|

---

# 📂 Repository Structure

```
enterprise-network-lab/

├── assets/
├── configs/
├── diagrams/
├── docs/
├── packet-tracer/
├── screenshots/
├── LICENSE
└── README.md
```

---

# 📸 Project Gallery

| Screenshot | Description |
|------------|-------------|
|Topology|Enterprise Network Diagram|
|SSH|Secure Remote Login|
|DHCP|Automatic Address Assignment|
|DNS|Domain Resolution|
|HTTP|Web Server Access|
|FTP|FTP Server|
|NAT|PAT Translation|
|OSPF|Neighbor Verification|

---

# 📚 Skills Demonstrated

- Enterprise Network Design
- Cisco Switching
- Cisco Routing
- Layer 3 Switching
- OSPF
- VLAN Design
- Enterprise Security
- Server Infrastructure
- Network Documentation
- Troubleshooting

---

# 🚀 Future Improvements

- IPv6
- HSRP
- EtherChannel
- SNMP
- VPN
- Wireless LAN
- Firewall
- Python Automation
- Ansible
- Cisco ISE

---

# 👨‍💻 Author

## Fahad Al Sadat

**Network Engineer | Linux | Python | Network Automation**

🎓 M.Sc. in Computer Science & Engineering  
Jahangirnagar University

🌐 GitHub

https://github.com/Fahad-al-sadat

💼 LinkedIn

https://linkedin.com/in/fahad-al-sadat

---

<div align="center">

## ⭐ If you like this project, please consider giving it a Star.

**Thank you for visiting my repository!**

</div>
