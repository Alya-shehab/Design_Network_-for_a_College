# College Network Design Project

This project focuses on designing and implementing a secure, scalable, and efficient network for a college using **Cisco Packet Tracer**.  
It combines wired and wireless technologies, VLAN segmentation, and IoT integration to support administrative, academic, and research operations.

Developed as part of **CIS 315 – Communication and Network Fundamentals**.

---

## 🎯 Objective
To create a robust and modular LAN network that supports multiple departments, ensuring:
- Reliable communication between devices
- Segmented VLANs for security
- Scalable architecture for future growth
- Integration of IoT and VoIP components

---

## 🧠 Design Overview
- **Topology:** Hybrid (wired + wireless)
- **Tool:** Cisco Packet Tracer
- **Core Devices:** Routers (2811, 1841), Switches (2960, 2950)
- **Endpoint Devices:** PCs, Laptops, Printers, IP Phones
- **IoT Devices:** Motion detectors & temperature sensors (on isolated WLAN)
- **Protocols:** VLAN, DHCP, OSPF/EIGRP, ACLs, QoS

---

## 🗂 VLAN Allocation
| VLAN | Department | Description |
|------|-------------|-------------|
| 10 | Computer Science | Labs, classrooms, faculty offices |
| 20 | Kindergarten | Smartboards, monitoring devices |
| 30 | Scientific | High-performance labs, 3D printers |
| 40 | English | Language learning & VoIP |
| 50 | Public Relations | Campaign & media workstations |
| 60 | Administration | Sensitive and confidential data |

---

## ⚙️ Implementation Highlights
1. Configured routers and switches for inter-VLAN communication  
2. Assigned IP addressing for each subnet  
3. Enabled routing protocols (EIGRP/OSPF)  
4. Connected IoT & wireless access points via WRT300N  
5. Tested connectivity using ping and traceroute  
6. Verified throughput, latency, and packet loss performance  

---

## 📊 Performance Summary
| Metric | Wired | Wireless |
|--------|--------|-----------|
| Throughput | 1 Gbps | 300–1200 Mbps |
| Latency | ~10 ms | ~20 ms |
| Packet Loss | ~0% | <1% |

---

## 🧩 Key Design Considerations
- **Security:** VLAN isolation and ACLs  
- **Scalability:** Easy to expand with more routers/switches  
- **Reliability:** QoS ensures consistent VoIP and IoT performance  
- **Testing:** Connectivity, throughput, and error rates validated in simulation  

---

## 📘 Results
All departments achieved full connectivity.  
IoT and VoIP operated within separate secure subnets.  
Ping and throughput tests confirmed stable and efficient network communication.

---


## 🛠 Tools Used
- Cisco Packet Tracer  

---

## 📎 Notes
This project simulates a real-world college network for academic purposes.  
The report includes topology diagrams, device configurations, and testing results.

