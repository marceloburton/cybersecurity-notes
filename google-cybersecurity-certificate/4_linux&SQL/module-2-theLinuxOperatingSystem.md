# 🐧 The Linux Operating System (Module 2)

## 📌 What is Linux?
**Linux** is an open-source operating system with hundreds of different versions (called distributions) designed for various use cases.

- Open-source → anyone can view and modify the code  
- Widely used in cybersecurity, servers, and cloud environments  

---

## 🧩 Core Components of Linux

### 1. User
- The person interacting with the system  
- Linux supports multiple users at the same time  

---

### 2. Applications
- Programs that perform specific tasks  
- Installed using **package managers**  

---

### 3. Shell
- Command-line interface (CLI) used to interact with the OS  
- Interprets commands and returns output  

---

### 4. File System Hierarchy Standard (FHS)
- Organizes files and directories in a structured way  
- Helps the system locate and manage data  

---

### 5. Kernel
- Core of the operating system  
- Manages processes, memory, and hardware communication  
- Ensures efficient resource allocation  

---

### 6. Hardware
- Physical components like CPU, RAM, and storage  

---

## 🖥️ Hardware Components

### Internal Hardware
- **CPU** → Executes instructions  
- **RAM** → Temporary memory for active processes  
- **Hard Drive** → Long-term storage  

---

### Peripheral Devices
- External devices like keyboards, monitors, and printers  
- Not required for the system to function  

---

## 💾 Memory Types

- **RAM** → Temporary storage (cleared when powered off)  
- **Hard Drive** → Persistent storage (retains data after shutdown)  

---

## 🧬 Linux Distributions (Distros)

Different versions of Linux tailored for specific purposes.

### Parent Distributions
- **Red Hat Enterprise Linux (RHEL)**
- **Debian**
- **Slackware**

---

### Popular Distributions

#### Kali Linux
- Designed for penetration testing and digital forensics  
- Includes many built-in security tools  
- Best used in a virtual machine  

**Tools:**
- Metasploit → Exploitation framework  
- Burp Suite → Web security testing  
- John the Ripper → Password cracking  

---

#### Ubuntu
- Beginner-friendly  
- Supports both GUI and CLI  
- Common in cloud computing  

---

#### Parrot OS
- Security-focused distro  
- Includes penetration testing and forensic tools  
- Debian-based  

---

#### Red Hat Enterprise Linux (RHEL)
- Enterprise-level OS  
- Paid subscription with support  

---

#### AlmaLinux
- Community-driven replacement for CentOS  
- Compatible with Red Hat-based systems  

---

## 📦 Packages & Package Management

### What is a Package?
- A bundle of software files needed to install an application  
- May include dependencies (supporting files)  

---

### Package Managers
Tools used to install, update, and remove software.

- **RPM** → Used in Red Hat-based systems  
- **dpkg** → Used in Debian-based systems  

---

### Package Management Tools

- **APT (Advanced Package Tool)** → Debian-based systems  
- **YUM** → Red Hat-based systems  

---

## 🧑‍💻 The Shell & Commands

### What is the Shell?
- Interface between the user and the operating system  
- Executes commands and returns results  

---

### Common Shell Types

- **bash** → Most widely used (default in many systems)  
- **zsh** → Modern alternative  
- **ksh, csh, tcsh** → Other variations  

---

### Bash Shell
- Default shell in many Linux distributions  
- Widely used in cybersecurity  

---

## ⌨️ Command Basics

### Command
- Instruction given to the system to perform an action  

---

### Standard Input (stdin)
- Data entered into the system (via keyboard or command line)  

---

### Standard Output (stdout)
- Normal output returned by the system  

---

### Standard Error (stderr)
- Error messages returned when something goes wrong  

---

### Example Command

```bash
echo hello
