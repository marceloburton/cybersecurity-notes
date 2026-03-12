# Module 2: Security Frameworks and Controls
**Google Cybersecurity Certificate – Course 2: Manage Security Risks**

---

# Biometrics

**Biometrics** are unique physical characteristics that can be used to verify a person's identity.

### Examples
- Fingerprints
- Eye or retina scans
- Palm scans
- Facial recognition

### Security Consideration
Biometric systems can still be targeted through **social engineering attacks**.

**Example: Vishing (Voice Phishing)**  
A social engineering attack that uses phone or voice communication to impersonate trusted sources and trick individuals into revealing sensitive information.

---

# Authorization

**Authorization** is the process of granting users permission to access specific resources or perform certain actions within a system.

Authorization determines **what an authenticated user is allowed to do**.

---

# Security Frameworks

A **security framework** is a set of structured guidelines used to help organizations manage and reduce cybersecurity risks.

Frameworks help organizations:

- Develop cybersecurity strategies
- Protect sensitive data
- Meet legal and regulatory requirements

**Example:**  
Healthcare organizations use frameworks to comply with **HIPAA regulations**.

---

# Security Controls

**Security controls** are safeguards designed to reduce security risks and protect systems, networks, and data.

Controls are typically divided into **three categories**:

---

## Physical Controls

Controls that prevent unauthorized **physical access** to systems or facilities.

### Examples
- Gates, fences, and locks
- Security guards
- CCTV or surveillance cameras
- Motion detectors

---

## Technical Controls

Technology-based safeguards that protect systems and networks.

### Examples
- Firewalls
- Multi-Factor Authentication (MFA)
- Antivirus software

---

## Administrative Controls

Policies and procedures that guide how an organization manages security.

### Examples
- Separation of duties
- Authorization policies
- Asset classification

---

### Key Idea
Security frameworks provide the **structure and strategy**, while security controls are the **tools used to enforce that strategy**.  
Together they shape an organization’s **security posture**.

---

# CIA Triad

The **CIA Triad** is a foundational cybersecurity model used to guide security policies and risk management decisions.

It includes three core principles:

- **Confidentiality**
- **Integrity**
- **Availability**

---

## Confidentiality

Confidentiality ensures that **only authorized users can access sensitive information**.

### Least Privilege Principle
A security concept where users are given **only the minimum level of access required to perform their job duties**.

This reduces potential damage if an account becomes compromised.

---

## Integrity

Integrity ensures that data remains **accurate, authentic, and reliable**.

### Cryptography
A method used to protect data by transforming it so that unauthorized users cannot read or modify it.

### Encryption
The process of converting readable data into an encoded format that cannot be accessed without authorization.

---

## Availability

Availability ensures that **authorized users can access systems and data when needed**.

### Example
Organizations may allow remote employees secure access to internal networks so they can perform their job responsibilities.

---

### Key Idea
Maintaining confidentiality, integrity, and availability is essential for a strong **security posture**.

---

# NIST Security Frameworks

The **National Institute of Standards and Technology (NIST)** provides widely used cybersecurity frameworks.

Two commonly used frameworks include:

- **NIST Cybersecurity Framework (CSF)**
- **NIST Special Publication 800-53**

---

# NIST Cybersecurity Framework (CSF)

The **NIST CSF** is a voluntary framework that provides standards and best practices for managing cybersecurity risk.

It helps organizations:

- Identify cybersecurity risks
- Protect systems and data
- Detect security incidents
- Respond to threats
- Recover from attacks

---

## Six Core Functions

### 1. Govern
Focuses on establishing cybersecurity leadership, policies, and risk management strategies across the organization.

**Examples**
- Defining cybersecurity goals
- Ensuring leadership involvement
- Developing risk management strategies

---

### 2. Identify
Focuses on understanding and managing cybersecurity risks related to systems, assets, and personnel.

**Example**
- Monitoring network systems and devices to identify potential vulnerabilities.

---

### 3. Protect
Implements safeguards that help reduce the likelihood or impact of cybersecurity threats.

**Examples**
- Security policies
- Employee security training
- Security tools and technologies

---

### 4. Detect
Develops capabilities to identify cybersecurity incidents quickly.

**Example**
- Security monitoring tools that classify alerts based on risk severity.

---

### 5. Respond
Defines procedures used to contain and manage security incidents.

This may include:

- Investigating attacks
- Documenting incidents
- Improving security procedures

---

### 6. Recover
Focuses on restoring systems and operations after a cybersecurity incident.

**Examples**
- Restoring data from backups
- Rebuilding compromised systems
- Returning services to normal operation

---

# NIST Special Publication 800-53

**NIST SP 800-53** is a framework used primarily by the **U.S. federal government** to protect information systems.

It provides detailed security controls designed to maintain the **CIA Triad**.

---

# OWASP Security Principles

The **Open Web Application Security Project (OWASP)** provides security principles used to strengthen application and system security.

---

## 1. Minimize Attack Surface Area

Reduce the number of potential vulnerabilities attackers could exploit.

### Examples
- Disabling unnecessary software features
- Restricting access to sensitive systems
- Strengthening password policies

### Attack Vectors
Attack vectors are **pathways attackers use to compromise systems**.

**Examples**
- Phishing emails
- Weak passwords

---

## 2. Principle of Least Privilege

Users should only have the access necessary to perform their job responsibilities.

**Example**

An employee may be allowed to **view log files** but not modify them.

---

## 3. Defense in Depth

Organizations should implement **multiple layers of security controls**.

Examples include:

- Firewalls
- Multi-Factor Authentication
- Intrusion detection systems
- Access control permissions

This ensures that if one layer fails, others still provide protection.

---

## 4. Separation of Duties

Critical responsibilities should be divided among multiple individuals to prevent fraud or misuse.

**Example**

The employee who prepares payroll should not also approve payroll payments.

---

## 5. Keep Security Simple

Security systems should avoid unnecessary complexity.

Overly complicated security solutions can become difficult to manage and may introduce new vulnerabilities.

---

## 6. Fix Security Issues Correctly

When a security issue occurs:

1. Identify the root cause
2. Fix the vulnerability
3. Test systems to confirm the issue is resolved

**Example**

Weak password policies should be replaced with stronger authentication requirements.

---

# Additional OWASP Security Principles

### Establish Secure Defaults
Applications should start in the **most secure configuration by default**.

Users should have to intentionally change settings to reduce security.

---

### Fail Securely
If a system fails, it should default to the **most secure state**.

**Example**

If a firewall fails, it should block all traffic instead of allowing unrestricted access.

---

### Do Not Trust Services
Organizations should not automatically trust external vendors or third-party services.

External systems should always be validated and verified.

---

### Avoid Security by Obscurity
Security should not rely on hiding system details.

Instead, strong security should come from:

- Authentication controls
- Secure network architecture
- Monitoring and auditing systems

---

# Security Audits

A **security audit** is an evaluation of an organization's security policies, controls, and procedures.

Audits compare current practices against established standards or expectations.

---

## Key Audit Questions

- What is the objective of the audit?
- Which assets are most at risk?
- Are existing controls sufficient?
- What compliance requirements must be met?

---

# Types of Security Audits

## Internal Audits

Internal audits are conducted by members of the organization, such as:

- Compliance officers
- Security managers
- Security analysts

### Purpose

- Identify organizational risks
- Evaluate existing security controls
- Ensure regulatory compliance

---

# Common Elements of Internal Audits

## 1. Establish Scope and Goals

### Scope
The scope defines what areas of the organization will be evaluated.

This may include:

- Personnel
- Systems
- Security policies
- Technologies

### Examples
- Reviewing user permissions
- Identifying existing security policies
- Documenting technologies currently in use

### Goals
Goals describe what the organization hopes to achieve through the audit.

Examples include:

- Aligning with the **NIST Cybersecurity Framework**
- Strengthening system controls
- Ensuring regulatory compliance

---

## 2. Conduct a Risk Assessment

A **risk assessment** identifies threats, vulnerabilities, and risks affecting organizational assets.

This helps determine which security measures should be implemented or improved.

---

## 3. Perform a Controls Assessment

This step evaluates whether current security controls are effective.

Controls are often categorized as:

- Administrative controls
- Technical controls
- Physical controls

---

## 4. Assess Compliance

Organizations must verify that their systems follow applicable laws, regulations, and security standards.

---

## 5. Communicate Results

Audit findings should be shared with stakeholders.

Reports typically include:

- Summary of audit scope and goals
- Identified risks
- Priority levels for addressing risks
- Compliance requirements
- Recommendations for improving security posture

---

✔ **Key Takeaway**

Security frameworks, controls, and audits work together to help organizations manage cybersecurity risks and maintain a strong security posture.
