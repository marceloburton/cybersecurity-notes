# 🌐 Network Architecture (Module 1)

## 📌 What is a Network?
A **network** is a collection of connected devices that communicate either through wired connections or wirelessly.

---

## 🆔 Addressing in Networks
- **IP Address** → Identifies a device’s location on a network  
- **MAC Address** → Identifies the physical hardware of a device  

---

## 🌍 Types of Networks
- **LAN (Local Area Network)**  
  Covers a small area (home, school, office)

- **WAN (Wide Area Network)**  
  Covers large geographic areas (internet)

---

## 🔧 Network Hardware

### 1. Hub
- Sends data to *all* devices on a network  
- Outdated and insecure (easy to intercept data)

### 2. Switch
- Sends data only to the intended device  
- Improves both performance and security  
- Most commonly used in modern networks  

### 3. Router
- Connects different networks together  
- Directs traffic based on IP addresses  

### 4. Modem
- Connects a local network to the internet  
- Acts as a bridge between ISP and router  

---

## ☁️ Virtualization & Cloud Networking

### Virtualization
- Software-based versions of network devices  
- Improves scalability and reduces costs  

### Cloud Computing
Using remote servers instead of local machines

### Cloud Network
A group of remote servers storing and managing data

### Cloud Service Providers (CSPs)
Companies that offer cloud-based services

#### Service Models:
- **IaaS** → Virtual infrastructure (servers, storage)
- **PaaS** → Development platforms and tools
- **SaaS** → Fully managed software applications

#### Cloud Environments:
- **Hybrid Cloud** → Mix of cloud + on-prem systems  
- **Multi-Cloud** → Multiple cloud providers  

#### Benefits:
- Reliability  
- Cost efficiency  
- Scalability  

---

## 🖥️ Servers & Clients

- **Server** → Provides resources/services (e.g., DNS, file storage, email)
- **Client** → Requests services from a server  

---

## 📡 Wireless Networking

- **Wireless Access Point (WAP)** → Enables wireless connections  
- **Wi-Fi** → Standard for wireless communication  

---

## 📦 Data Packets

A **packet** is the basic unit of data sent across a network.

### Packet Structure:
- **Header** → Addressing + instructions  
- **Body** → Actual data  
- **Footer** → End of packet indicator  

---

## ⚡ Network Performance

- **Bandwidth** → Amount of data transferred per second  
- **Speed** → Rate of data transfer  

---

## 🕵️ Packet Sniffing
Capturing and inspecting packets traveling across a network.

---

# 🌐 TCP/IP Model (4 Layers)

## 1. Network Access Layer
- Handles physical transmission (Ethernet, Wi-Fi)  
- Includes hardware devices  
- **ARP** maps IP → MAC addresses  

---

## 2. Internet Layer
- Adds IP addressing to packets  
- Determines routing between networks  

### Key Protocols:
- **IP** → Routes packets  
- **ICMP** → Reports errors and network status  

---

## 3. Transport Layer
- Controls data flow and reliability  

### Protocols:
- **TCP** → Reliable, connection-based  
- **UDP** → Fast, connectionless  

---

## 4. Application Layer
- Interfaces with user applications  

### Examples:
- HTTP (web browsing)  
- SMTP (email)  
- DNS (domain lookup)  
- FTP (file transfer)  
- SSH (secure access)  

---

## 🔌 Ports & Communication

- **Port** → Logical endpoint for communication  
- **Port Number** → Defines service type  

### Common Ports:
- 25 → Email  
- 443 → Secure web traffic  
- 20 → File transfer  

---

# 🧠 OSI Model (7 Layers)

## 7. Application
User-facing services (web, email)

## 6. Presentation
Data formatting, encryption, compression  

## 5. Session
Manages connections between devices  

## 4. Transport
Handles delivery and segmentation  

## 3. Network
Routes data using IP addresses  

## 2. Data Link
Handles communication within a local network  

## 1. Physical
Physical hardware and transmission of bits  

---

## 🌐 IP Addressing

### Types:
- **Public IP** → Visible on the internet  
- **Private IP** → Used within local networks  

### Versions:
- **IPv4** → Older, limited addresses  
- **IPv6** → Newer, supports many more devices  

---

## 🧾 MAC Addressing
- Unique hardware identifier for devices  
- Stored in a **MAC address table** used by switches  

---

## 📦 IPv4 Packet Header (Key Fields)

- Version → Protocol version  
- Header Length → Size of header  
- Total Length → Entire packet size  
- Identification → Packet fragment ID  
- Flags → Fragmentation details  
- TTL → Prevents infinite routing loops  
- Protocol → Indicates TCP/UDP  
- Source IP → Sender  
- Destination IP → Receiver  

---

## 🧩 Key Takeaways
- Networks rely on structured communication (packets + protocols)  
- Hardware (routers, switches) and software (cloud, virtualization) work together  
- TCP/IP and OSI models help standardize networking processes  
- Security and efficiency depend on proper network design  
