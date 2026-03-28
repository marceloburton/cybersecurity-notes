# Module 3 – SIEM Dashboards 📊

## Overview
This module focuses on how **Security Information and Event Management (SIEM)** tools use logs and dashboards to monitor, detect, and respond to security events across an organization.

---

## Logs 📝

**Logs** are records of events that occur within systems and networks.  
They are essential for detecting unusual activity and investigating incidents.

### Common Log Sources

- **Firewall Logs**
  - Track incoming and outgoing network traffic
  - Include both attempted and successful connections

- **Network Logs**
  - Record devices entering and leaving the network
  - Capture communication between systems and services

- **Server Logs**
  - Track activity related to services (websites, email, file sharing)
  - Include login attempts, usernames, and authentication activity

---

## SIEM (Security Information and Event Management)

A **SIEM tool** collects and analyzes log data to monitor an organization’s critical operations.

### Key Benefits
- Centralizes log data from multiple sources  
- Enables real-time monitoring and alerting  
- Improves efficiency in threat detection  
- Provides data visualization for stakeholders  

> ⚠️ SIEM systems must be configured based on an organization’s specific needs.

---

## Metrics 📈

**Metrics** are measurable indicators used to evaluate system performance.

### Examples:
- Response time  
- System availability  
- Failure rate  

Security teams use these metrics in dashboards to assess overall system health and security performance.

---

## SOAR (Security Orchestration, Automation, and Response)

**SOAR** combines tools, processes, and automation to respond to security events more efficiently.

- Automates repetitive tasks  
- Coordinates incident response workflows  
- Reduces manual effort for analysts  

---

## Types of SIEM Deployment

### 1. Self-Hosted
- Managed internally by the organization  
- Requires on-site infrastructure  
- Best for organizations needing full data control  

### 2. Cloud-Hosted
- Managed by external providers  
- Accessible via the internet  
- Reduces infrastructure maintenance  

### 3. Hybrid
- Combines cloud flexibility with on-premise control  
- Balances scalability and data security  

---

## SIEM Tools 🛠️

### Splunk
A platform used for searching, analyzing, and monitoring machine data.

- **Splunk Enterprise**
  - Self-hosted solution  
  - Provides real-time monitoring and alerts  

- **Splunk Cloud**
  - Cloud-based version  
  - Handles data collection and analysis remotely  

---

### Chronicle (Google SecOps)

A cloud-native SIEM tool designed for large-scale data analysis.

- Offers log collection, monitoring, and analysis  
- Built for scalability and high availability  
- Fully managed by external providers  

---

## Open-Source vs Proprietary Tools

### Open-Source Tools
- Free and customizable  
- Community-supported  

Examples:
- **Linux** – widely used operating system with command-line control  
- **Suricata** – network monitoring and threat detection tool  

---

### Proprietary Tools
- Owned by companies  
- Require paid licenses  

Examples:
- Splunk  
- Chronicle  

---

## Splunk Dashboards 📊

### 1. Security Posture Dashboard
- Displays recent security events (typically last 24 hours)  
- Helps analysts monitor threats in real time  

---

### 2. Executive Summary Dashboard
- Provides a high-level overview of security trends  
- Used to communicate insights to stakeholders  

---

### 3. Incident Review Dashboard
- Highlights patterns during security incidents  
- Shows a timeline of related events  

---

### 4. Risk Analysis Dashboard
- Evaluates risk levels for users, systems, or IP addresses  
- Helps prioritize mitigation efforts  

---

## Chronicle Dashboards 📊

### 1. Enterprise Insights Dashboard
- Displays recent alerts and suspicious activity  
- Uses indicators of compromise (IOCs) with confidence scores  

---

### 2. Data Ingestion & Health Dashboard
- Tracks log collection performance  
- Ensures logs are being properly received and processed  

---

### 3. IOC Matches Dashboard
- Identifies top threats and vulnerabilities  
- Helps detect patterns across IPs, domains, and devices  

---

### 4. Main Dashboard
- Provides an overall summary of system activity  
- Helps identify trends like spikes in failed logins  

---

### 5. Rule Detections Dashboard
- Shows alerts triggered by detection rules  
- Helps analyze recurring incidents  

---

### 6. User Sign-In Overview Dashboard
- Tracks user login activity  
- Identifies unusual behavior (e.g., multiple locations)  

---

## Key Takeaways 🔑

- Logs are the foundation of security monitoring  
- SIEM tools centralize and analyze log data  
- Dashboards help visualize threats and system health  
- SOAR enhances response through automation  
- Different SIEM deployments fit different organizational needs  
- Tools like Splunk and Chronicle provide powerful monitoring capabilities  

---
