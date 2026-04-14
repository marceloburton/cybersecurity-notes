# 🛡️ Secure Against Network Intrusions (Module 3)

## ⚠️ Common Network Intrusion Attacks

- **Malware** → Malicious software designed to damage or exploit systems  
- **Spoofing** → Impersonating a trusted source to gain access  
- **Packet Sniffing** → Capturing and analyzing network traffic  
- **Packet Flooding** → Overwhelming systems with excessive traffic  

---

## 📉 Impact of Network Attacks

Attacks can negatively affect organizations by:
- Exposing sensitive or confidential data  
- Damaging reputation and trust  
- Reducing customer retention  
- Causing financial and operational losses  

---

## 🕵️ Network Interception Attacks

These attacks involve intercepting or altering data as it travels across a network.

### Packet Sniffing
- Capturing and inspecting data packets in transit  
- Can be used for both legitimate analysis and malicious purposes  

---

## 🚪 Backdoor Attacks

- **Backdoor** → Hidden method of bypassing normal authentication  
- Originally used for maintenance or troubleshooting  
- Attackers may install backdoors to maintain long-term access  

---

## 💥 Denial of Service (DoS)

A **DoS attack** overwhelms a system with traffic to disrupt normal operations.

### Potential Impacts:
- Financial damage  
- Reputational harm  
- Public safety risks  

---

## 🌐 Distributed DoS (DDoS)

- Uses multiple compromised systems to launch a large-scale attack  
- Harder to detect and mitigate than a standard DoS  

---

## 🔥 Common DoS Attack Types

- **SYN Flood** → Exploits TCP handshake by sending excessive connection requests  
- **ICMP Flood** → Overloads a system with ICMP (ping) traffic  
- **Ping of Death** → Sends oversized packets to crash systems  

---

## 🔍 Network Protocol Analyzers

Tools used to capture and examine network traffic.

### Examples:
- SolarWinds NetFlow Traffic Analyzer  
- ManageEngine OpManager  
- Azure Network Watcher  
- Wireshark  
- tcpdump  

---

## 💻 tcpdump Overview

- Command-line packet analyzer  
- Lightweight and efficient  
- Displays packet data directly in the terminal  

### Key Information in Output:
- Timestamp → When the packet was captured  
- Source IP & Port → Origin of the packet  
- Destination IP & Port → Target of the packet  

---

## 📊 Uses of Network Analyzers

- Monitor traffic patterns and performance  
- Detect suspicious or malicious activity  
- Create alerts for network issues  
- Identify unauthorized devices or traffic  
- (Malicious use) Capture sensitive data like credentials  

---

## 🤖 Botnets

- A group of infected devices controlled by an attacker (**bot-herder**)  
- Often used in large-scale attacks like DDoS  

---

## 🧠 Packet Sniffing Types

- **Passive Sniffing** → Observes traffic without altering it  
- **Active Sniffing** → Intercepts and modifies traffic  

---

## 🔐 Protecting Against Packet Sniffing

- Use a **VPN** to encrypt data  
- Only visit **HTTPS** websites  
- Avoid unsecured public Wi-Fi networks  

---

## 🎭 IP Spoofing

Altering a packet’s source IP address to appear as a trusted entity.

---

## ⚠️ Common Spoofing Attacks

### 1. On-Path (Man-in-the-Middle)
- Attacker intercepts communication between two parties  

### 2. Replay Attack
- Captures and retransmits valid data later  

### 3. Smurf Attack
- Combines spoofing with flooding to overwhelm a target  

---

## 🛡️ Preventing IP Spoofing

- Use encryption for data transmission  
- Configure firewalls to block suspicious traffic  

---

## 🧩 Network Interface Card (NIC)

- Hardware that connects a device to a network  
- Processes incoming packets based on MAC address  
- Sends valid data to the system for further processing  

---

## 🧠 Key Takeaways

- Network attacks target data, availability, and trust  
- Tools like packet analyzers help detect threats  
- Encryption and secure configurations are critical defenses  
- Understanding attack types helps in prevention and response  
