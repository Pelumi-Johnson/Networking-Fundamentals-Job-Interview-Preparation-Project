# 🌐 Networking Fundamentals | Job Interview Preparation Project

<!-- Source: Project 1 (Networking Interview Presentation) :contentReference[oaicite:0]{index=0} -->

👉 **Full Lab Report with screenshots and detailed steps:**  
[Click here to view the complete project documentation](https://github.com/Pelumi-Johnson/Creating-a-Site-to-Site-VPN-on-AWS/blob/main/Name_%20Pelumi%20Johnson_University%20of%20Maryland%20Global%20Center.pdf)

**Name:** Pelumi Johnson  
**Focus:** Networking Fundamentals (Interview-Style Technical Review)

---

## 📘 Project Overview
This project documents a structured networking fundamentals review presented in an interview-style format. It covers core concepts required for entry-level networking and cybersecurity roles, including network topologies, OSI model layers, networking devices, common protocols and ports, IP addressing classes, subnet masks, and routing concepts such as autonomous systems.

The goal of this project was to demonstrate both theoretical understanding and the ability to clearly explain foundational networking concepts.

---

## 🧠 Networking Scope
- LAN Topologies
- OSI Model (Layers, Functions, PDUs)
- Networking Devices & OSI Layers
- Internet Demarcation Point
- Common Network Protocols & Ports
- IP Address Classes & Subnet Masks
- Autonomous Systems & Routing Protocols

---

## 🔗 Part 1: LAN Topologies

### Basic LAN Topologies
- **Bus Topology**
- **Star Topology**
- **Ring (Circle) Topology**

### Topology Descriptions & Characteristics

**Bus Topology**
- Devices share one main communication cable
- Easy and inexpensive to set up
- Failure of the main cable brings down the entire network

**Star Topology**
- Devices connect to a central hub or switch
- Failure of one device does not affect others
- Failure of the central device stops all communication

**Ring Topology**
- Devices form a closed loop
- Data travels in one direction around the ring
- Failure of one device can disrupt the network

**Mesh Topology**
- Every device connects to every other device
- High reliability and redundancy
- Expensive and complex due to cabling

**Hybrid Topology**
- Combination of multiple topologies
- Flexible and scalable
- More complex to design and maintain

---

## 🧩 Part 2: OSI Model

### OSI Layers (Top to Bottom)
- Layer 7 – Application  
- Layer 6 – Presentation  
- Layer 5 – Session  
- Layer 4 – Transport  
- Layer 3 – Network  
- Layer 2 – Data Link  
- Layer 1 – Physical  

### OSI Layer Functions & Characteristics

**Application (Layer 7)**
- Provides services directly to users and applications  
- PDU: Data  

**Presentation (Layer 6)**
- Translates, encrypts, and compresses data  

**Session (Layer 5)**
- Establishes, manages, and terminates sessions  

**Transport (Layer 4)**
- Ensures reliable delivery through segmentation and flow control  
- PDU: Segment  

**Network (Layer 3)**
- Handles logical addressing and routing  
- PDU: Packet  

**Data Link (Layer 2)**
- Provides node-to-node delivery and error detection  
- PDU: Frame  

**Physical (Layer 1)**
- Transmits raw bits over physical media  
- PDU: Bits  

---

## 🌐 Part 3: Internet Connectivity

### Demarcation Point
The **demarcation point** is where operational control transitions from the Internet Service Provider (ISP) to the organization. Beyond this point, the organization is responsible for network management and security.

---

## 🖧 Part 4: Networking Devices

**Hub**
- Operates at OSI Layer 1 (Physical)
- Broadcasts traffic to all devices
- Inefficient and prone to collisions

**Switch**
- Operates at OSI Layer 2 (Data Link)
- Uses MAC addresses to forward traffic
- Reduces collisions and improves efficiency

**Router**
- Operates at OSI Layer 3 (Network)
- Routes traffic between networks using IP addresses
- Determines best path for packets

**NIC (Network Interface Card)**
- Connects a device to a network
- Converts data into transmittable signals

---

## 🔐 Part 5: Common Protocols & Ports

- HTTP → 80  
- HTTPS → 443  
- SMTP → 25  
- SMTP over TLS → 465 / 587  
- SNMP → 161  
- DNS → 53  
- LDAPS → 636  
- DHCP → 67  
- TELNET → 23  

---

## 📡 Part 6: IP Address Classes

### Class Ranges
- **Class A:** 1.0.0.0 – 126.225.225.225  
- **Class B:** 128.0.0.0 – 191.255.255.255  
- **Class C:** 192.0.0.0 – 223.255.255.255  

### Default Subnet Masks
- **Class A:** 255.0.0.0  
- **Class B:** 255.255.0.0  
- **Class C:** 255.255.255.0  

---

## 🔄 Part 7: Autonomous Systems & Routing

An **Autonomous System (AS)** is a group of IP networks managed under a single administrative authority with a unified routing policy.

- **Interior Routing Protocols (IRPs)** such as OSPF or EIGRP manage routing within an AS
- **Exterior Routing Protocols (ERPs)** such as BGP manage routing between different ASes
- This structure allows independent internal control while maintaining global internet connectivity

---

## 🧾 Key Takeaways
- Networking fundamentals remain critical despite evolving technology
- Understanding structure enables effective defense and troubleshooting
- Clear explanations are as important as technical accuracy
- Strong fundamentals support advanced cybersecurity work

---

## 📚 References
- OSI Model Documentation  
- TCP/IP and Networking Fundamentals  
- ISP & Demarcation Point Concepts  
- Routing Protocol Standards (OSPF, BGP)

