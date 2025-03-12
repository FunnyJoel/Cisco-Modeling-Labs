# Cisco-Modeling-Labs
 Ready-to-use network scenarios for testing
# 🚀 Cisco Modeling Labs (CML) - Network Topologies & Automation  

This repository contains a collection of **Cisco Modeling Labs (CML) network topologies, configurations, and automation scripts** designed for **network engineers, students, and IT professionals**. These labs cover a wide range of networking concepts, including **Routing, Switching, Security, Network Services, and Automation**.

> 🛠️ **Use these labs to gain hands-on experience with Cisco networking technologies, test real-world scenarios, and practice for certifications like CCNA, CCNP, and CCIE.**

---

## 📂 Repository Contents  

### **1️⃣ Core Networking Labs**  
These labs cover the **fundamental principles** of networking, including **TCP/IP, ACLs, and Secure CLI access**.

| File | Description |
|------|------------|
| **[CIS270B_Wk1_Ex1-TCP-IP_Connections.yaml](CIS270B_Wk1_Ex1-TCP-IP_Connections.yaml)** | Establishes **basic TCP/IP connectivity** between multiple devices, ensuring successful communication in a routed network. |
| **[CIS270B_Wk1_Ex2-Configure_and_Apply_ACLs.yaml](CIS270B_Wk1_Ex2-Configure_and_Apply_ACLs.yaml)** | Implements **Access Control Lists (ACLs)** to manage traffic, filter packets, and improve network security. |

---

### **2️⃣ Routing & Switching Labs**  
These labs focus on **Layer 2 (Switching) and Layer 3 (Routing) technologies**, including VLANs, EtherChannel, IPv4 Routing, and OSPF.

| File | Description |
|------|------------|
| **[CIS270A_Wk2_Ex1-VLANs_EtherChannel_and_Spanning_Tree.yaml](CIS270A_Wk2_Ex1-VLANs__EtherChannel_and_Spanning_Tree.yaml)** | Configures **VLAN segmentation**, **EtherChannel bundling**, and **Spanning Tree Protocol (STP)** to prevent loops. |
| **[CIS270A_Wk3_Ex1-IPv4_Routing.yaml](CIS270A_Wk3_Ex1-IPv4_Routing.yaml)** | Implements **static and dynamic IPv4 routing** for inter-network communication. |
| **[CIS270A_Wk4_Ex1-OSPF_LAN-to-Core.yaml](CIS270A_Wk4_Ex1-OSPF_LAN-to-Core.yaml)** | Deploys **OSPF in a core network**, establishing neighbor relationships between LAN and Core routers. |
| **[CIS270A_Wk4_Ex2-OSPF_LAN-to-LAN.yaml](CIS270A_Wk4_Ex2-OSPF_LAN-to-LAN.yaml)** | Configures **multi-area OSPF** between different LAN segments for scalability and redundancy. |

---

### **3️⃣ Network Services Labs**  
These labs explore **essential networking services** such as **DHCP, CDP, LLDP, and NTP**.

| File | Description |
|------|------------|
| **[CIS270B_Wk2_Ex1-Implement_DHCP.yaml](CIS270B_Wk2_Ex1-Implement_DHCP.yaml)** | Configures **DHCP server and clients**, implementing **DHCP relay** for multiple subnets. |
| **[CIS270B_Wk2_Ex3-Implement_Port_Security.yaml](CIS270B_Wk2_Ex3-Implement_Port_Security.yaml)** | Implements **Port Security** on switches to prevent unauthorized devices from connecting. |
| **[CIS270B_Wk3_Ex1-CDP-LLDP_and_NTP.yaml](CIS270B_Wk3_Ex1-CDP-LLDP_and_NTP.yaml)** | Configures **Cisco Discovery Protocol (CDP) and Link Layer Discovery Protocol (LLDP)** for device discovery. Also sets up **Network Time Protocol (NTP)** to synchronize device clocks. |

---

### **4️⃣ Security & Management Labs**  
These labs focus on **hardening network security** and securing administrative access to Cisco devices.

| File | Description |
|------|------------|
| **[Securing_the_CLI.yaml](Securing_the_CLI.yaml)** | Secures CLI access with **SSH, privilege levels, login banners, and encrypted passwords**. |
| **[Switch_Configurations.yaml](Switch_Configurations%20(2).yaml)** | Includes multiple **switch configurations** for different networking scenarios. |

---

### **5️⃣ Documentation & Guides**  
These files provide **step-by-step instructions** for lab exercises.

| File | Description |
|------|------------|
| **[CIS270B_Wk2_Ex4-Implement_DHCP.docx](CIS270B_Wk2_Ex4-Implement_DHCP.docx)** | A comprehensive **DHCP configuration guide**, including topology diagrams, IP allocation tables, and troubleshooting steps. |

---

## 🛠 How to Use These Labs  

### **1️⃣ Importing a CML Topology**  
1. Open **Cisco Modeling Labs (CML)**.  
2. Click **Import Lab** and select the `.yaml` file.  
3. Start the simulation and test your network configurations.  

### **2️⃣ Modifying and Customizing**  
- **Edit** `.yaml` files to add/remove devices.  
- **Modify interface configurations** as needed.  
- Use **Python automation** to generate network configurations.  

### **3️⃣ Saving and Sharing Configurations**  
- After making changes, **export the topology** and commit it to GitHub.  
- Share your labs for **learning and collaboration**.  

---
**ALL LOWERCASE** username and password for all endpoints is cisco
