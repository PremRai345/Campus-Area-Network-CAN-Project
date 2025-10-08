# 🏫 Campus Area Network (CAN) Project

This project demonstrates the design and configuration of a **Campus Area Network (CAN)** in **Cisco Packet Tracer**, integrating multiple departments, VLANs, and traffic types for a realistic enterprise environment. The project focuses on inter-department connectivity, secure management, and multi-service integration using advanced switching concepts.



## 🧩 Network Overview

The CAN topology connects multiple departments across a single campus, each with its own switches, VLANs, and devices. The design enables efficient communication between departments while maintaining network segmentation and security.

### 🌐 Departments:
- **Admin**
- **IT**
- **Business**
- **Server Room**

Each department is connected through **access**, **distribution**, and **core switches**, ensuring redundancy and scalability. The **Core Switch** in the Server Room acts as the central hub for routing and management.



## 🔌 Network Traffic Types

The network supports multiple types of traffic:
- **Internet (wired and wireless)**
- **IP Phones (Voice traffic)**
- **IP Cameras (Video surveillance)**
- **Data (User PCs, printers, etc.)**



## 🧱 Network Architecture

- **Access Layer:** Connects end-user devices such as PCs, IP phones, and printers.  
- **Distribution Layer:** Aggregates multiple access switches and manages VLAN traffic.  
- **Core Layer:** Provides high-speed backbone connectivity between departments and the server room.



## 🖥️ VLAN Configuration

Multiple VLANs are implemented to segment traffic:
- **VLAN 10 – Data**
- **VLAN 20 – Voice (IP Phones)**
- **VLAN 30 – Video (IP Cameras)**
- **VLAN 40 – Management (Telnet & SSH)**

This VLAN segmentation improves performance, security, and traffic management across departments.



## 🔐 Remote Access and Management

- **Telnet and SSH** are configured on network devices for remote access.
- Users in any department can securely access and manage devices in the **Server Room**.
- Centralized control enables easy configuration and monitoring from the server PC.


## ⚙️ Key Configurations

- VLAN creation and assignment on switches  
- Inter-VLAN routing via the **Core Switch**  
- Telnet and SSH for remote device management  
- IP addressing plan for all departments  
- Device configuration for **IP phones, cameras, and PCs**


## 🎯 Learning Outcomes

- Designed a **scalable multi-department network** with hierarchical switching.  
- Implemented **VLAN-based segmentation** for different traffic types.  
- Configured **remote access (Telnet/SSH)** for centralized management.  
- Enhanced understanding of **LAN design, security, and enterprise network topology**.  


## 🖼️ Network Diagram
![Campus Area Network](Screenshot%202025-10-08%20at%204.19.58%E2%80%AFam.png)
