# Module 4 — Cybersecurity Tools and Programming Languages

Security analysts rely on specialized tools and programming languages to monitor systems, investigate incidents, and automate security tasks. These technologies help organizations detect threats, analyze network activity, and protect sensitive information.

---

# Logs

A **log** is a recorded history of events that occur within a system, application, or network.

Logs allow security professionals to:

* Track system activity
* Detect suspicious behavior
* Investigate potential security incidents
* Identify vulnerabilities within systems

Because logs document what happens inside an environment, they are essential for **incident detection and investigation**.

---

# Security Information and Event Management (SIEM)

A **Security Information and Event Management (SIEM)** tool collects and analyzes log data from many systems in order to monitor an organization's security activity in real time.

SIEM platforms help analysts:

* Aggregate logs from multiple sources
* Identify unusual activity
* Detect potential attacks
* Respond to security incidents more efficiently

Common SIEM platforms include:

* Splunk
* Google Chronicle

---

# Security Playbooks

A **playbook** is a documented guide that outlines how security teams should respond to specific situations or incidents.

Playbooks help organizations:

* Standardize incident response procedures
* Ensure investigations follow proper protocols
* Maintain consistent handling of evidence

## Common Types of Playbooks

### Chain of Custody

The **chain of custody** documents how evidence is collected, handled, and transferred during an investigation.

It records key details such as:

* Who collected the evidence
* What the evidence contains
* When it was collected
* Where it was stored
* Why it was collected

Maintaining a clear chain of custody ensures that digital evidence remains **reliable and legally valid**.

---

### Evidence Preservation

Another important playbook focuses on **protecting and preserving digital evidence** during an investigation.

Investigators must understand the difference between stable data and **volatile data**, which can disappear if a system powers off.

Security teams follow the **order of volatility**, which prioritizes collecting the most fragile data first.

Examples of volatile data include:

* System memory (RAM)
* Running processes
* Active network connections

To protect evidence, investigators usually create copies of the data and perform analysis on those copies rather than the original source.

---

# Network Protocol Analyzers

A **network protocol analyzer** (often called a **packet sniffer**) captures and examines data moving across a network.

These tools help security professionals:

* Monitor network traffic
* Detect suspicious communication
* Troubleshoot connectivity issues
* Investigate security incidents

Common examples include:

* Wireshark
* tcpdump

---

# Programming in Cybersecurity

Programming allows security professionals to create instructions that computers follow to perform tasks.

Automation and scripting can help analysts:

* Analyze large datasets
* Automate repetitive security tasks
* Investigate threats more efficiently

---

# Linux

**Linux** is an open-source operating system widely used in cybersecurity environments.

An **operating system (OS)** acts as the interface between computer hardware and the user.

Linux is commonly used by security professionals because it:

* Provides strong command-line tools
* Offers high flexibility and customization
* Is widely used on servers and security platforms

Many security tools and penetration-testing environments are built on Linux systems.

---

# SQL (Structured Query Language)

**Structured Query Language (SQL)** is used to interact with databases.

A **database** is an organized collection of data that can store millions of records.

SQL allows users to:

* Retrieve data
* Insert new information
* Modify stored records
* Analyze stored datasets

Each individual piece of information stored in a database is called a **data point**.

---

# Python

**Python** is a programming language commonly used in cybersecurity for automation and data analysis.

Security analysts use Python to:

* Automate repetitive tasks
* Process large datasets
* Build security scripts
* Analyze logs and alerts

Python is popular because its syntax is relatively simple and it supports many cybersecurity libraries.

---

# Web Vulnerabilities

A **web vulnerability** is a flaw within a web application that attackers can exploit.

Threat actors may take advantage of these weaknesses to:

* Gain unauthorized access
* Steal sensitive information
* Install malware
* Manipulate web services

Identifying and fixing these vulnerabilities is an important part of maintaining web security.

---

# Antivirus (Anti-Malware) Software

**Antivirus software**, also called **anti-malware**, is designed to detect, prevent, and remove malicious software.

These programs scan systems for patterns or behaviors that indicate the presence of malware.

Common tasks include:

* Scanning files and programs
* Detecting suspicious code
* Removing infected files

---

# Intrusion Detection Systems (IDS)

An **Intrusion Detection System (IDS)** monitors systems or networks for suspicious activity.

IDS tools analyze **network packets**, which are small units of data transmitted across networks.

If unusual behavior is detected, the system generates alerts so security teams can investigate potential threats.

---

# Encryption

**Encryption** is the process of converting readable data into an encoded format so that unauthorized users cannot understand it.

Encryption helps maintain the **confidentiality** of sensitive information.

During encryption:

* **Plaintext** – the original readable data
* **Ciphertext** – the encoded version of that data

Only authorized users with the correct decryption method can convert ciphertext back into plaintext.

---

# Penetration Testing

**Penetration testing** is a controlled simulation of a cyberattack used to evaluate the security of systems.

Security professionals perform these tests to identify weaknesses in:

* Networks
* Applications
* Websites
* Security processes

Penetration tests help organizations understand their risks and strengthen their defenses before real attackers exploit vulnerabilities.
