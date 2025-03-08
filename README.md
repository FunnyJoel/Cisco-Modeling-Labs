# Cisco-Modeling-Labs
 Ready-to-use network scenarios for testing
# 🚀 Cisco Modeling Labs (CML) Topologies Repository  

This repository contains **Cisco Modeling Labs (CML) network topologies**, configurations, and documentation for **network engineers, students, and professionals** looking to build and test networking concepts in a **simulated environment**. These labs cover **routing, switching, security, network services, and automation**.

---

## 📂 Files and Labs Included  

### **🖥️ Core Networking Labs**  
These labs focus on **fundamental networking concepts**, including TCP/IP, ACLs, and secure CLI access.  

- **[CIS270B_Wk1_Ex1-TCP-IP_Connections.yaml](CIS270B_Wk1_Ex1-TCP-IP_Connections.yaml)** –  
  🔹 Configures TCP/IP connections between multiple devices to establish network communication.  

- **[CIS270B_Wk1_Ex2-Configure_and_Apply_ACLs.yaml](CIS270B_Wk1_Ex2-Configure_and_Apply_ACLs.yaml)** –  
  🔹 Implements Access Control Lists (ACLs) to **control traffic** flow and **enhance security**.  

---

### **🔄 Routing & Switching Labs**  
These labs cover **Layer 2 and Layer 3 networking**, including VLANs, EtherChannel, IPv4 routing, and OSPF.  

- **[CIS270A_Wk2_Ex1-VLANs_EtherChannel_and_Spanning_Tree.yaml](CIS270A_Wk2_Ex1-VLANs__EtherChannel_and_Spanning_Tree.yaml)** –  
  🔹 Implements **VLAN segmentation**, configures **EtherChannel**, and **Spanning Tree Protocol (STP)** to prevent loops.  

- **[CIS270A_Wk3_Ex1-IPv4_Routing.yaml](CIS270A_Wk3_Ex1-IPv4_Routing.yaml)** –  
  🔹 Configures **static and dynamic IPv4 routing** between routers for inter-network communication.  

- **[CIS270A_Wk4_Ex1-OSPF_LAN-to-Core.yaml](CIS270A_Wk4_Ex1-OSPF_LAN-to-Core.yaml)** –  
  🔹 Deploys **OSPF in a core network**, establishing neighbor relationships between LAN and Core routers.  

- **[CIS270A_Wk4_Ex2-OSPF_LAN-to-LAN.yaml](CIS270A_Wk4_Ex2-OSPF_LAN-to-LAN.yaml)** –  
  🔹 Connects multiple LANs using **OSPF multi-area routing** for scalability and redundancy.  

- **[OSPF_LAN-to-Core.yaml](OSPF_LAN-to-Core.yaml)** –  
  🔹 Another variation of OSPF between **LAN and Core network devices**.  

- **[OSPF_LAN-to-LAN.yaml](OSPF_LAN-to-LAN.yaml)** –  
  🔹 Simulates OSPF routing **between separate LAN segments**.  

---

### **📡 Network Services Labs**  
These labs focus on **network protocols and services**, such as DHCP, CDP, LLDP, and NTP.  

- **[CIS270B_Wk2_Ex1-Implement_DHCP.yaml](CIS270B_Wk2_Ex1-Implement_DHCP.yaml)** –  
  🔹 Configures **DHCP server and clients**, implementing DHCP relay and address allocation.  

- **[CIS270B_Wk2_Ex3-Implement_Port_Security.yaml](CIS270B_Wk2_Ex3-Implement_Port_Security.yaml)** –  
  🔹 Implements **port security on switches**, limiting MAC addresses per port and preventing unauthorized access.  

- **[CIS270B_Wk2_Ex4-Implement_DHCP.yaml](CIS270B_Wk2_Ex4-Implement_DHCP.yaml)** –  
  🔹 Enhances the DHCP lab with **multiple VLANs and subnets**.  

- **[CIS270B_Wk3_Ex1-CDP-LLDP_and_NTP.yaml](CIS270B_Wk3_Ex1-CDP-LLDP_and_NTP.yaml)** –  
  🔹 Configures **Cisco Discovery Protocol (CDP) and Link Layer Discovery Protocol (LLDP)** for device discovery.  
  🔹 Implements **Network Time Protocol (NTP)** to synchronize clocks across network devices.  

- **[CIS270B_Wk3_Ex5-CDP-LLDP_and_NTP.yaml](CIS270B_Wk3_Ex5-CDP-LLDP_and_NTP.yaml)** –  
  🔹 An advanced implementation of **CDP, LLDP, and NTP** across multiple devices.  

---

### **🔐 Security & Management Labs**  
These labs focus on **network security**, CLI hardening, and secure device access.  

- **[Securing_the_CLI.yaml](Securing_the_CLI.yaml)** –  
  🔹 Secures CLI access using **SSH, privilege levels, login banners, and encrypted passwords**.  

- **[Switch_Configurations.yaml](Switch_Configurations%20(2).yaml)** –  
  🔹 Various switch configurations for VLANs, trunking, and inter-switch connectivity.  

---

### **📖 Documentation**  
These files provide **step-by-step guides** for network configuration and troubleshooting.  

- **[CIS270B_Wk2_Ex4-Implement_DHCP.docx](CIS270B_Wk2_Ex4-Implement_DHCP.docx)** –  
  🔹 **Comprehensive guide** on implementing DHCP with VLANs and subnets.  
  🔹 Includes **IP allocation tables, troubleshooting steps, and configuration commands**.  

---

## 🛠 How to Use These Labs  

### **1️⃣ Import the CML Topology**  
1. Open **Cisco Modeling Labs (CML)**.  
2. Click **Import Lab** and select the `.yaml` file.  
3. Start the simulation and test the network.  

### **2️⃣ Modify and Customize**  
- **Edit** `.yaml` files to add/remove devices.  
- **Modify interface configurations** as needed.  
- Use **Python automation** to generate network configurations.  

### **3️⃣ Save and Share Configurations**  
- After making changes, **export the topology** and commit it to GitHub.  
- Share your labs for **learning and collaboration**.  

---

## 📜 License  
This repository is licensed under the **MIT License**. You are free to **use, modify, and share** these labs.  

---

## 🚀 Contributing  
🔹 If you have improvements or new labs, **fork the repository** and submit a **pull request**.  
🔹 Let's build an amazing **CML Lab Collection** together!  

---
