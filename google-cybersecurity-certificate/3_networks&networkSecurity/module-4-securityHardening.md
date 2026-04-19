# 🛡️ Security Hardening (Module 4)

## 📌 What is Security Hardening?
**Security hardening** is the process of strengthening systems to reduce vulnerabilities and minimize the attack surface.

### Systems that can be hardened:
- Hardware  
- Operating systems  
- Applications  
- Networks  
- Databases  

---

## 🎯 Key Concepts

- **Attack Surface** → All possible entry points an attacker could exploit  
- **Penetration Testing** → Simulated attacks used to identify weaknesses  
- **Operating System (OS)** → Interface between hardware and user/software  

---

## 🔄 System Security Practices

### Patch Management
- Regular updates that fix vulnerabilities in software and systems  

### Baseline Configuration
- A secure reference setup used to compare system changes  
- Helps ensure systems remain properly configured  

### Removing Unused Software
- Eliminates unnecessary vulnerabilities from outdated or unused programs  

---

## 🔐 Authentication & Password Security

### Strong Password Policies
- Enforce complexity, expiration, and reuse rules  

### Multi-Factor Authentication (MFA)
Requires multiple forms of verification:

- Something you know → password  
- Something you have → device or ID  
- Something you are → biometrics  

---

## ⚠️ Brute Force Attacks

Attempts to gain access through repeated guessing.

### Types:
- **Simple brute force** → guessing credentials  
- **Dictionary attack** → using lists of common passwords  

---

## 🧪 Secure Testing Environments

### Virtual Machines (VMs)
- Isolated environments for running software safely  
- Prevents threats from affecting the main system  

### Sandbox Environments
- Controlled testing spaces for analyzing code or vulnerabilities  
- Often used for malware testing or patch validation  

---

## 🔒 Prevention Techniques

### Hashing
- Converts data into a fixed, irreversible value  

### Salting
- Adds randomness to hashed data to increase security  

---

### CAPTCHA / reCAPTCHA
- Prevent automated attacks by verifying human users  

---

## 🌐 Network Security Hardening

### Key Techniques:
- Port filtering  
- Access control (user permissions)  
- Encryption of data  

---

### Common Tasks:
- Maintaining firewall rules  
- Monitoring network logs  
- Applying updates  
- Backing up systems  

---

## 📊 Network Monitoring

### SIEM (Security Information and Event Management)
- Collects and analyzes logs from multiple systems  
- Helps detect threats and prioritize risks  

---

## 🔥 Firewalls & Traffic Control

### Port Filtering
- Allows only necessary ports  
- Blocks all unnecessary communication  

---

## 🛠️ Security Tools

- Firewalls  
- Intrusion Detection Systems (IDS)  
- Intrusion Prevention Systems (IPS)  
- Packet capture tools  
- SIEM platforms (e.g., Splunk, Chronicle)  

---

## 🚨 IDS vs IPS

### IDS (Intrusion Detection System)
- Detects suspicious activity  
- Sends alerts only  

### IPS (Intrusion Prevention System)
- Detects AND actively blocks threats  
- Can stop malicious traffic in real time  

---

## 📦 Packet Capture

- Records all network traffic  
- Used for analysis and investigation  

---

## ⚖️ Tool Tradeoffs

### Advantages
- **Firewall** → Controls traffic flow  
- **IDS** → Alerts on threats  
- **IPS** → Stops attacks  
- **SIEM** → Centralized monitoring  

### Limitations
- Firewalls rely only on packet data  
- IDS cannot stop attacks  
- IPS may block legitimate traffic (false positives)  
- SIEM does not take direct action  

---

# ☁️ Cloud Security Hardening

## 📌 Cloud Computing
On-demand access to shared computing resources over the internet.

---

## 🔐 Identity and Access Management (IAM)
- Controls user access to cloud resources  
- Manages digital identities and permissions  

---

## ⚠️ Zero-Day Attacks
- Exploits unknown vulnerabilities  
- Often discovered before organizations can defend against them  

---

## 🤝 Shared Responsibility Model
- **Cloud Provider (CSP)** → Responsible for infrastructure security  
- **Customer** → Responsible for data, access, and configurations  

---

## 🛠️ Cloud Security Tools

- IAM  
- Hypervisors  
- Baselining  
- Cryptography  
- Cryptographic erasure  

---

## 🖥️ Hypervisors

Software that manages virtual machines.

### Types:
- **Type 1** → Runs directly on hardware  
- **Type 2** → Runs on top of an operating system  

### Risk:
- **VM Escape** → Attacker breaks out of a VM to access host or other VMs  

---

## 📏 Baselining (Cloud)

- Establishes a secure standard configuration  
- Used to detect deviations and improve security  

---

## 🔐 Cryptography

- Protects data using encryption  
- Ensures confidentiality and integrity  

---

## 🧹 Cryptographic Erasure

- Deletes encryption keys instead of the data itself  
- Makes stored data permanently unreadable  

### Crypto-Shredding
- Destroys all encryption keys  
- Ensures data cannot be recovered  

---

## 🔑 Key Management

### TPM (Trusted Platform Module)
- Hardware chip for securely storing keys and credentials  

### CloudHSM
- Cloud-based hardware security module  
- Handles encryption and key storage securely  

---

## 🧠 Key Takeaways

- Security hardening reduces vulnerabilities and attack surfaces  
- Strong authentication and system updates are critical defenses  
- Monitoring tools help detect threats, but layered security is essential  
- Cloud security follows a shared responsibility model  
- Encryption and key management are essential for protecting data  
