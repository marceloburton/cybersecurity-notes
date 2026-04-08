# 🌐 Network Operations (Module 2)

## 📌 What are Network Protocols?
**Network protocols** are standardized rules that define how devices communicate, including how data is formatted, transmitted, and received.

---

## 🔑 Core Protocols

- **TCP (Transmission Control Protocol)** → Establishes reliable, connection-based communication  
- **ARP (Address Resolution Protocol)** → Maps IP addresses to MAC addresses  
- **HTTPS (Hypertext Transfer Protocol Secure)** → Enables encrypted web communication  
- **DNS (Domain Name System)** → Converts domain names into IP addresses  

---

## 🧩 Categories of Network Protocols

### 1. Communication Protocols
Control how data is transmitted between devices, including timing and error handling.

**Examples:**
- TCP
- UDP
- HTTP
- DNS

---

### 2. Management Protocols
Used to monitor performance and manage network activity.

**Examples:**
- **SNMP** → Monitors and manages network devices  
- **ICMP** → Reports errors and connection issues  

---

### 3. Security Protocols
Protect data during transmission using encryption.

**Examples:**
- **HTTPS** → Secures web traffic using SSL/TLS (port 443)  
- **SFTP** → Secure file transfer using SSH (port 22)  

---

## 🌍 Network Services & Operations

### NAT (Network Address Translation)
- Converts private IP addresses into a public IP address  
- Allows multiple devices to share one public IP  
- Typically configured on routers/firewalls  

---

### DHCP (Dynamic Host Configuration Protocol)
- Automatically assigns IP addresses to devices  
- Provides DNS server and default gateway info  
- Server uses port 67, clients use port 68  

---

### ARP (Address Resolution Protocol)
- Resolves IP addresses into MAC addresses  
- Operates at a lower layer (no port number)

---

## 💻 Remote Access Protocols

### Telnet
- Remote access via command line  
- Sends data in plain text (not secure)  
- Uses port 23  

### SSH (Secure Shell)
- Secure alternative to Telnet  
- Encrypts remote connections  
- Uses port 22  

---

## 📧 Email Protocols

### IMAP (Internet Message Access Protocol)
- Syncs email across multiple devices  
- Allows partial message viewing before download  
- Ports: 143 (unencrypted), 993 (encrypted)  

---

### POP3 (Post Office Protocol)
- Downloads emails to a single device  
- Limited syncing capability  
- Ports: 110 (unencrypted), 995 (encrypted)  

---

### SMTP (Simple Mail Transfer Protocol)
- Sends and routes outgoing email  
- Works with mail servers to deliver messages  
- Ports: 25 (unencrypted), 587 (encrypted)  

---

## 🔌 Ports & Traffic Control

- **Port numbers** tell devices how to handle incoming data  
- Firewalls use ports to allow or block traffic  

---

## 📡 Wireless Standards & Security

### Wi-Fi (IEEE 802.11)
Defines how wireless devices communicate over LANs

---

### Wireless Security Protocols

- **WEP** → Outdated and insecure  
- **WPA** → Improved security but still vulnerable  
- **WPA2** → Uses AES encryption (current standard)  
- **WPA3** → Strongest security, protects against modern attacks  

---

## 🔥 Firewalls

A **firewall** monitors and filters network traffic based on security rules.

### Types:
- **Hardware Firewall** → Physical device filtering traffic  
- **Software Firewall** → Installed on individual systems  
- **Cloud Firewall** → Hosted by cloud providers  

---

### Firewall Behavior

- **Stateful** → Tracks active connections (more secure)  
- **Stateless** → Uses fixed rules only (less secure)  

---

### Advanced Firewall
- **NGFW (Next-Generation Firewall)**  
  Includes deep packet inspection and intrusion prevention  

---

### Port Filtering
- Allows or blocks traffic based on port numbers  
- Example: Only allowing HTTPS (port 443)

---

## 🔐 VPN (Virtual Private Network)

A **VPN** protects privacy by encrypting internet traffic and masking IP addresses.

### Key Features:
- Encryption  
- IP masking  
- Secure communication over public networks  

---

### Encapsulation
Wrapping data inside another packet to protect it during transmission.

---

## 🌍 Network Segmentation

Dividing a network into smaller sections to improve security and control.

---

### Security Zones

#### 1. Uncontrolled Zone
- External networks (e.g., the internet)

#### 2. Controlled Zone
- Internal protected network areas

##### Subsections:
- **DMZ (Demilitarized Zone)** → Public-facing systems  
- **Internal Network** → Private organizational data  
- **Restricted Zone** → Highly sensitive data  

---

## 🧱 Subnetting

- Splits a network into smaller subnetworks  
- Helps isolate issues and improve security  

### CIDR (Classless Inter-Domain Routing)
- Flexible method for assigning IP ranges  
- More efficient than older class-based systems  

---

## 🌐 Proxy Servers

A **proxy server** acts as an intermediary between a client and the internet.

### Types:
- **Forward Proxy** → Controls user access to the internet  
- **Reverse Proxy** → Protects internal servers from external traffic  
- **Email Proxy** → Filters spam and phishing attempts  

---

## 🌍 SD-WAN

**Software-Defined WAN (SD-WAN)** enables secure, flexible connections across large geographic areas using virtual networking.

---

## 🔐 VPN Protocols

### WireGuard
- Fast and modern  
- Strong encryption  
- Simple configuration  

### IPsec
- Well-established and widely supported  
- Encrypts and authenticates data packets  

---

## 🔗 Types of VPNs

### Remote Access VPN
- Connects individual users to a network securely  

### Site-to-Site VPN
- Connects entire networks together  
- Common in large organizations  

---

## 🧩 Key Takeaways
- Protocols define how networks communicate and stay secure  
- Firewalls and VPNs are essential for protecting data  
- Network segmentation limits damage during attacks  
- Modern networks rely on cloud, virtualization, and secure communication standards  
