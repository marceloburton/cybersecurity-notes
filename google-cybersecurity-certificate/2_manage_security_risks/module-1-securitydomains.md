# Course 2 — Manage Security Risks

## Module 1 — Security Domains

Cybersecurity professionals organize security responsibilities into **domains**, which represent different areas of knowledge and practice. One widely recognized model comes from the Certified Information Systems Security Professional (CISSP) certification, which divides security responsibilities into **eight domains**.

Understanding these domains helps organizations structure their security programs and manage risk effectively.

---

# The 8 CISSP Security Domains

## 1. Security and Risk Management

This domain focuses on establishing security strategies and managing organizational risk.

Key responsibilities include:

* **Defining security goals and objectives**
  Organizations identify critical assets and determine how to protect sensitive data such as Personally Identifiable Information (PII).

* **Risk mitigation**
  Policies and procedures are created to reduce the impact of potential threats, such as data breaches or system failures.

* **Compliance**
  Organizations must follow internal policies as well as external regulations and industry standards.

* **Business continuity planning**
  Plans are developed to ensure operations can continue during incidents or disasters.

* **Legal and regulatory requirements**
  Security professionals must understand laws and ethical expectations that help prevent fraud, negligence, and misuse of data.

---

## 2. Asset Security

Asset security focuses on protecting both **physical and digital resources** that belong to an organization.

Key responsibilities include:

* Managing **data storage**
* Maintaining and protecting stored information
* Establishing retention policies
* Safely destroying data when it is no longer needed

A core concept in this domain is **shared responsibility**, meaning every member of an organization contributes to protecting information and reducing security risks.

Understanding **who has access to specific data** is critical for maintaining a strong security posture.

---

## 3. Security Architecture and Engineering

This domain focuses on designing systems and infrastructure that protect data and organizational assets.

Security professionals ensure that:

* Security tools are properly implemented
* System architectures support strong protections
* Processes and technologies work together to defend against threats

---

## 4. Communications and Network Security

This domain addresses the protection of **network infrastructure and communications systems**.

Security professionals work to secure:

* Local networks
* Wireless networks
* Cloud-based systems
* Remote communication environments

The goal is to ensure that data transmitted across networks remains protected.

---

## 5. Identity and Access Management (IAM)

Identity and Access Management controls **who can access systems and what actions they are allowed to perform**.

IAM includes four main components:

### Identification

A user claims an identity within a system.

Examples include:

* Username
* Access card
* Biometric identifiers such as fingerprints

---

### Authentication

Authentication verifies that the user is actually who they claim to be.

Examples include:

* Passwords
* PIN numbers
* Multi-factor authentication

---

### Authorization

After identity is verified, authorization determines **what level of access the user receives** based on their role.

---

### Accountability

Accountability ensures that user actions are **tracked and recorded**, allowing organizations to audit system activity and investigate incidents.

---

## 6. Security Assessment and Testing

This domain focuses on evaluating the effectiveness of security controls.

Common activities include:

* Testing security systems
* Performing security audits
* Collecting and analyzing security data
* Identifying weaknesses or vulnerabilities

These assessments help organizations improve their defenses against evolving threats.

---

## 7. Security Operations

Security operations involve the **day-to-day management of security incidents and threats**.

Responsibilities include:

* Investigating detected security incidents
* Containing and mitigating attacks
* Implementing preventative security measures

Quick response is essential to prevent attackers from escalating an incident or gaining additional access.

---

## 8. Software Development Security

This domain ensures that **security practices are integrated into the software development lifecycle**.

Security professionals help developers implement:

* Secure coding practices
* Application testing
* Security reviews during development

Security should be incorporated throughout development rather than added after the software is built.

---

# Threats, Risks, and Vulnerabilities

Understanding the relationship between threats, risks, and vulnerabilities is essential in cybersecurity.

---

## Threat

A **threat** is any event or circumstance that could harm an organization's assets.

Example:

A social engineering attack attempting to gain unauthorized access to sensitive data.

---

## Risk

A **risk** represents the potential for loss or damage when a threat exploits a vulnerability.

Risk levels are often categorized as:

* **Low risk** – minimal impact if compromised
* **Medium risk** – moderate financial or operational damage
* **High risk** – severe consequences for operations, finances, or reputation

Examples of risk levels:

* **Low-risk asset:** public website content or research data
* **Medium-risk asset:** internal company financial data
* **High-risk asset:** regulated information such as PII or intellectual property

---

## Vulnerability

A **vulnerability** is a weakness that a threat actor could exploit.

Examples include:

* Outdated software
* Weak passwords
* Misconfigured firewalls
* Unprotected confidential data

Human behavior can also introduce vulnerabilities, making employee awareness and training important.

A **risk exists when both a threat and vulnerability are present.**

---

# Layers of the Web

The internet is commonly divided into three layers based on accessibility.

### Surface Web

The portion of the internet accessible through standard web browsers and search engines.

This is the part most people interact with daily.

---

### Deep Web

Content that is not publicly indexed and typically requires authorization to access.

Examples include:

* Company intranets
* Private databases
* Academic resources

---

### Dark Web

A hidden portion of the internet that requires specialized software to access.

While it has legitimate uses, it is often associated with illegal marketplaces and anonymous activity.

---

# Impacts of Security Threats

Security threats can affect organizations in multiple ways.

## Financial Impact

Incidents may lead to:

* Operational disruptions
* Recovery costs
* Legal penalties for regulatory violations

---

## Identity Theft

When sensitive data is compromised, attackers may sell stolen personal information online.

This can lead to identity fraud and financial harm to affected individuals.

---

## Reputational Damage

Security breaches can reduce customer trust and harm an organization's public image, sometimes causing customers to move to competitors.

---

# NIST Risk Management Framework (RMF)

The National Institute of Standards and Technology developed the **Risk Management Framework (RMF)** to help organizations systematically manage security and privacy risks.

The RMF includes seven steps.

---

## 1. Prepare

Organizations establish strategies and resources needed to manage security and privacy risks.

---

## 2. Categorize

Systems and information are categorized based on the potential impact to **confidentiality, integrity, and availability**.

---

## 3. Select

Appropriate security controls are chosen and documented to protect organizational systems.

---

## 4. Implement

The selected security controls are deployed and integrated into systems and processes.

---

## 5. Assess

Security professionals evaluate whether controls are working properly and identify weaknesses.

---

## 6. Authorize

Leadership reviews the security posture and accepts responsibility for any remaining risks.

---

## 7. Monitor

Systems are continuously monitored to ensure controls remain effective and aligned with security goals.

---

# Risk Management Strategies

Organizations use several strategies to handle security risks.

### Risk Acceptance

Accepting a risk when mitigation would cause excessive disruption or cost.

---

### Risk Avoidance

Changing plans or operations to eliminate the risk entirely.

---

### Risk Transference

Shifting risk responsibility to another party, such as through insurance or outsourcing.

---

### Risk Mitigation

Reducing the likelihood or impact of a risk through security controls.

---

# Types of Security Risks

## External Risks

Threats originating outside the organization, such as cyberattacks from external threat actors.

---

## Legacy Systems

Older technologies that may still operate within an environment but lack modern security protections.

Examples include outdated workstations or legacy payment systems.

---

## Multiparty Risk

Risks introduced when third-party vendors or partners are given access to organizational systems or data.

---

## Software Compliance Risks

Risks caused by outdated software, missing patches, or failure to follow licensing agreements.

---

# Examples of Technical Vulnerabilities

### ProxyLogon

A vulnerability affecting Microsoft Exchange servers that allows attackers to authenticate and execute malicious code remotely.

---

### ZeroLogon

A flaw in Microsoft's Netlogon authentication protocol that can allow attackers to bypass authentication protections.

---

### Log4Shell

A vulnerability in the Log4j logging library that allows attackers to execute remote code on affected systems.

---

### PetitPotam

An attack technique targeting the NTLM authentication protocol in Windows environments.

---

### Security Logging and Monitoring Failures

Insufficient monitoring or logging can allow attackers to exploit vulnerabilities without detection.

---

### Server-Side Request Forgery (SSRF)

A vulnerability that tricks a server into sending unauthorized requests to internal or external systems, potentially exposing sensitive data.
