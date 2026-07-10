<div align="center">

# 🌐 Enterprise Network Design & Implementation

### Cisco Packet Tracer Enterprise Campus Network Simulation

<p>
A production-inspired enterprise campus network implementing Cisco's hierarchical design model with secure routing, switching, enterprise services, and network security.
</p>

<p>

![Cisco](https://img.shields.io/badge/Cisco-Packet%20Tracer-1BA0D7?logo=cisco&logoColor=white)
![OSPF](https://img.shields.io/badge/Routing-OSPF-success)
![NAT/PAT](https://img.shields.io/badge/NAT-PAT-orange)
![SSH](https://img.shields.io/badge/Secure-SSH-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

</p>

</div>

---

# 📖 Project Overview

This project simulates a **real-world Enterprise Campus Network** designed using Cisco's three-tier hierarchical architecture.

The implementation demonstrates practical enterprise networking concepts including Layer 3 switching, VLAN segmentation, dynamic routing, centralized services, secure remote management, and Internet connectivity.

The goal of this project is to replicate how medium-sized organizations design and manage scalable, secure, and maintainable campus networks.

---

# 🖼 Enterprise Topology

<p align="center">

<img src="diagrams/enterprise-topology.png" width="95%">

</p>

---

# 🏗 Enterprise Architecture

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
                /               \
       Distribution         Distribution
          Switch               Switch
         /      \             /      \
    Access    Access     Access    Access

             Enterprise Departments
```

---

# ✨ Key Features

## 🌐 Network Infrastructure

- Cisco Three-Tier Architecture
- Layer 3 Core Switching
- Distribution Layer
- Access Layer
- Enterprise Server Farm
- Public Internet Simulation

---

## 🖥 Enterprise Services

- Internal DNS Server
- Public DNS Server
- DHCP
- HTTP
- FTP
- Mail Server
- File Server
- Syslog
- NTP
- Backup Server

---

## 🔐 Security Features

- SSH Remote Management
- Port Security
- PortFast
- BPDU Guard
- ACL
- NAT/PAT
- Disabled Unused Ports
- VLAN Segmentation

---

## 📡 Routing & Switching

- OSPF Dynamic Routing
- Inter-VLAN Routing
- Layer 2 Switching
- Layer 3 Switching
- Trunk Links
- Static Default Route
- DHCP Relay (if applicable)

---

# 🏢 VLAN Design

| VLAN | Department | Network |
|------|------------|----------------|
|10|Management|192.168.10.0/24|
|20|Human Resources|192.168.20.0/24|
|30|Finance|192.168.30.0/24|
|40|IT Department|192.168.40.0/24|
|50|Sales|192.168.50.0/24|
|99|Server Farm|192.168.99.0/24|

---

# 🌍 WAN Addressing

| Link | Network |
|-----------------|----------------|
|Internet ↔ ISP|198.51.100.0/30|
|ISP ↔ Edge|203.0.113.0/30|
|Edge ↔ Core|10.255.255.0/30|

---

# 🖥 Enterprise Server Farm

| Server | Services |
|---------|---------------------------|
|Server-01|DNS, NTP, Syslog|
|Server-02|Web, FTP, File|
|Server-03|Mail, Backup|

---

# 🌎 Public Internet Services

| Service | IP Address |
|----------|----------------|
|DNS|198.51.101.10|
|Web|198.51.101.20|
|FTP|198.51.101.30|

---

# 🧪 Validation & Testing

✔ End-to-End Connectivity

✔ OSPF Neighbor Formation

✔ VLAN Isolation

✔ Inter-VLAN Routing

✔ DHCP Lease Assignment

✔ Internal DNS Resolution

✔ Public DNS Resolution

✔ HTTP Access

✔ FTP Connectivity

✔ NAT/PAT Translation

✔ SSH Login

✔ Port Security

✔ BPDU Guard

---

# 🛠 Technologies Used

| Category | Technologies |
|------------|----------------------------|
|Routing|OSPF|
|Switching|VLAN, Trunking, STP|
|Services|DHCP, DNS, HTTP, FTP, Mail|
|Security|ACL, SSH, NAT/PAT, Port Security|
|Management|Syslog, NTP|
|Platform|Cisco Packet Tracer|

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

# 📸 Screenshots

| Feature | Preview |
|----------|----------|
|Enterprise Topology|✔|
|SSH Login|✔|
|DHCP Test|✔|
|DNS Resolution|✔|
|HTTP Test|✔|
|FTP Test|✔|
|OSPF Neighbor|✔|
|NAT Translation|✔|

---

# 🚀 Future Improvements

- IPv6 Deployment
- HSRP
- EtherChannel
- Wireless Infrastructure
- SNMP Monitoring
- Network Automation (Python)
- Cisco ISE
- VPN Connectivity
- Firewall Integration

---

# 👨‍💻 Author

**Fahad Al Sadat**

M.Sc. in Computer Science & Engineering  
Jahangirnagar University

🌐 GitHub  
https://github.com/Fahad-al-sadat

💼 LinkedIn  
https://linkedin.com/in/fahad-al-sadat

---

<div align="center">

### ⭐ If you found this project useful, consider giving it a star!

</div>
