# 🛡️ Benedict Adjei
## 👋🏾 About Me

I go by the name Benedict Adjei, a current Computer Science student at Livingstone College, building my career at the intersection of Security Operations + Software Engineering.

With a strong foundation in network engineering, I am developing hands-on experience across threat detection, alert triage, incident response, SIEM analysis, network traffic analysis, intrusion detection, and Linux security monitoring.

My long-term goal goes beyond responding to alerts. I want to combine AI agents, software engineering, and cybersecurity to build intelligent defense systems that help analysts detect, investigate, and scope threats faster. I am particularly interested in agentic security systems that can correlate signals across network, endpoint, identity, and log data, enrich suspicious activity with context, map attack paths, determine the potential blast radius, and give human analysts the evidence they need to make faster, higher-confidence decisions.

I am building toward that goal from the fundamentals up.

Through hands-on security labs and projects, I work with tools such as Splunk, Snort, Wireshark, TCPDump, KQL, Linux `auditd`, Python, and SQL, alongside network security technologies and controls. My network engineering background also gives me an understanding of the infrastructure behind the alerts—from TCP/IP, routing, VLANs, and ACLs to firewalls and enterprise network architecture.

> What drives me is a simple question: How can we engineer security systems that find the signal in the noise before an attacker can turn an intrusion into an incident?

I want to help build that answer by combining the **investigative mindset of a SOC analyst**, the **engineering discipline of a software engineer**, and the capabilities of **AI agents** to develop scalable security defenses for an increasingly automated threat landscape.

I am currently seeking opportunities where I can **contribute, learn from experienced security teams, investigate real-world threats, and build security systems** that make defenders faster, smarter, and harder to evade.

### 🎯 Areas of Expertise

- 🌐 **Routing & Switching** — Huawei / Cisco
- 🐧 **Linux File Auditing**
- 📡 **Network Traffic Analysis**
- 🔎 **Threat Detection & Alert Triage**
- 🚨 **Incident Response Fundamentals**
- 📝 **Technical Documentation & Report Writing**

**Career Direction:** `SOC Analyst` → `Detection Engineering` → `AI + Security Engineering`

---

## 📑 Table of Contents

- [Technical Skills](#-technical-skills)
- [Certifications](#-certifications)
- [Featured Security Projects](#-featured-security-projects)
- [Hands-On Labs](#-hands-on-labs)
- [Capture the Flag](#-capture-the-flag)
- [Articles & Write-Ups](#-articles--write-ups)
- [Experience](#-experience)
- [Fellowships & Community](#-fellowships--community)
- [Currently Learning](#-currently-learning)
- [Contact](#-contact)

---

## 🧰 Technical Skills

### 🔎 SOC & Threat Detection

![Splunk](https://img.shields.io/badge/Splunk-000000?style=for-the-badge&logo=splunk&logoColor=white)
![Snort](https://img.shields.io/badge/Snort-Detection-red?style=for-the-badge)
![KQL](https://img.shields.io/badge/KQL-Threat_Hunting-0078D4?style=for-the-badge)
![Incident Response](https://img.shields.io/badge/Incident_Response-SOC-blue?style=for-the-badge)
![Threat Hunting](https://img.shields.io/badge/Threat_Hunting-Security-orange?style=for-the-badge)

- Alert triage
- Threat detection
- Incident investigation
- SIEM analysis
- Log analysis
- Detection rule development
- Basic threat hunting

### 🌐 Network Security & Packet Analysis

![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![TCPDump](https://img.shields.io/badge/TCPDump-Packet_Analysis-333333?style=for-the-badge)
![Cisco](https://img.shields.io/badge/Cisco-Networking-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Fortinet](https://img.shields.io/badge/Fortinet-Security-EE3124?style=for-the-badge&logo=fortinet&logoColor=white)

- Wireshark / TCPDump
- PCAP investigation
- TCP/IP
- HTTP / DNS / SMTP
- OSPF
- VLANs
- ACLs
- NAT / PAT
- DHCP
- Cisco ASA
- FortiGate

### 🐧 Systems & Security Auditing

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=for-the-badge)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

- Linux file permissions
- `auditd`
- Access-control auditing
- Principle of Least Privilege
- Windows fundamentals
- Docker
- Bash / CLI

### 💻 Programming & Query Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Database-4479A1?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

`Python` • `SQL` • `KQL` • `Bash` • `JavaScript`

---

## 🎓 Certifications

| Certification | Organization |
|---|---|
| 🛡️ Fortinet Certified Associate in Cybersecurity | Fortinet |
| 🔐 Fortinet Certified Fundamentals in Cybersecurity | Fortinet |
| 🌐 HCIA-Datacom | Huawei |
| 🔎 Google Cybersecurity Course | Google |

---

## 🚀 Featured Security Projects

### 🔴 Directory Traversal Attack Detection & Incident Investigation

**Problem:** A vulnerable file service failed to validate user-supplied paths, creating the risk of unauthorized access to files outside its intended directory.

**Tools:** `Snort 3` • `PCAP` • `TCPDump` • `Linux` • `HTTP Analysis`

**What I did:**
- Investigated directory-traversal behavior in an authorized cybersecurity lab environment.
- Analyzed captured HTTP traffic to identify malicious traversal requests.
- Developed Snort detection logic for suspicious file-access patterns.
- Used packet evidence to determine what resources were targeted.

**Outcome:** Practiced the complete SOC workflow from understanding an attack to **detecting, investigating, and scoping suspicious network activity**.

🔗 **Project:** `[Add GitHub repository link]`

---

### 🛡️ Snort Network Intrusion Detection Lab

**Problem:** Security analysts need a way to identify malicious network activity without generating excessive noise from legitimate traffic.

**Tools:** `Snort 3` • `PCAP` • `TCPDump` • `Linux`

**What I did:**
- Analyzed captured network traffic with Snort.
- Built custom detection rules using protocol, port, flow, and content conditions.
- Detected suspicious HTTP requests and credential-file access attempts.
- Tuned rules to distinguish suspicious behavior from normal traffic.

**Outcome:** Strengthened practical skills in **network intrusion detection, signature development, alert analysis, and false-positive reduction**.

🔗 **Project:** `[Add GitHub repository link]`

---

### 🐧 Linux File Permissions Audit & Access Control

**Problem:** Incorrect Linux file permissions can expose sensitive files or allow unauthorized modification.

**Tools:** `Linux` • `auditd` • `Bash` • `ls` • `chmod`

**What I did:**
- Audited Linux files and directories for inappropriate permissions.
- Applied the **Principle of Least Privilege** to access-control decisions.
- Configured `auditd` rules to monitor changes to selected files.
- Investigated audit events using Linux audit logs.

**Outcome:** Built hands-on experience with **host monitoring, access-control auditing, and Linux security fundamentals** relevant to SOC investigations.

🔗 **Project:** `[Add GitHub repository link]`

---

### 🌐 Multi-Branch Secure Enterprise Network

**Problem:** Multiple branch locations required reliable connectivity while maintaining segmentation and controlled network access.

**Tools:** `Cisco Packet Tracer` • `OSPF` • `VLANs` • `ACLs` • `NAT/PAT` • `DHCP` • `SSH`

**What I did:**
- Designed and configured a multi-branch routed network.
- Implemented OSPF routing between locations.
- Segmented users and services with VLANs.
- Applied ACLs to control traffic between network segments.
- Configured NAT/PAT, DHCP, and SSH administration.

**Outcome:** Demonstrated the networking foundation required to investigate **source/destination IPs, ports, routing behavior, segmentation, and suspicious network activity** in a SOC.

🔗 **Project:** `[Add GitHub repository link]`

---

### 🔍 [Project Name]

**Problem:** `[What security problem were you solving?]`

**Tools:** `[SIEM]` • `[Security Tool]` • `[Operating System]`

**What I did:**
- `[Action + investigation performed]`
- `[Action + detection/analysis performed]`
- `[Action + remediation/recommendation]`

**Outcome:** `[Measurable result or what the investigation demonstrated]`

🔗 **Project:** `[GitHub repository link]`

---

## 🧪 Hands-On Labs

I use security labs to practice the same workflow expected from an entry-level SOC analyst:

**Detect → Triage → Investigate → Scope → Document → Recommend**

| Platform / Lab | Focus | Status |
|---|---|---|
| CodePath CYB102 | SOC & Cybersecurity | In Progress |
| KC7 | Security Investigations / Threat Analysis | In Progress |
| TryHackMe | `[Path / Room]` | `[Status]` |
| Blue Team Labs Online | `[Investigation]` | `[Status]` |
| `[Platform]` | `[Focus]` | `[Status]` |

---

## 🚩 Capture the Flag

I use CTF challenges to improve investigation, log-analysis, networking, and security problem-solving skills.

| Competition | Result | Focus |
|---|---:|---|
| `[CTF Name]` | `[Ranking / Points]` | `[Category]` |
| `[CTF Name]` | `[Ranking / Points]` | `[Category]` |
| `[CTF Name]` | `[Ranking / Points]` | `[Category]` |

> Rankings and results will be added only after participating in each competition.

---

## ✍️ Articles & Write-Ups

I document investigations and labs to demonstrate **how I think through security incidents**, not just which tools I can run.

### Planned / Published Write-Ups

- `[Directory Traversal: From Exploitation to Snort Detection]` — `[Link]`
- `[Building and Tuning My First Snort Detection Rule]` — `[Link]`
- `[Linux File Permission Auditing with auditd]` — `[Link]`
- `[Investigating a PCAP Like an L1 SOC Analyst]` — `[Link]`
- `[Article / Write-Up]` — `[Link]`

---

## 💼 Experience

### IT Intern — Prestige Technology  
**Accra, Ghana**

- Supported enterprise networking and infrastructure deployments involving **Dell PowerEdge servers, Huawei OceanStor storage, CloudEngine switches, and routers**.
- Configured and troubleshot Huawei and Cisco routing and switching environments.
- Assisted with technical documentation and tender preparation for infrastructure projects.
- Built practical understanding of enterprise infrastructure that now supports my transition into **SOC and cybersecurity operations**.

---

## 🤝 Fellowships & Community

### 🚀 The Accelerators Program

`[Add official role, dates, accomplishments, or program description]`

### 🟣 ColorStack

Engaged with the ColorStack community while developing my technical skills, professional network, and preparation for opportunities in technology and cybersecurity.

`[Add specific membership, fellowship, program, or accomplishment if applicable]`

### 🎓 Livingstone College

**B.S. Computer Information Systems — Expected May 2030**

Building foundations across computer information systems, networking, security, and technology while pursuing hands-on cybersecurity projects outside the classroom.

---

## 📚 Currently Learning

```text
SOC Alert Triage
        ↓
SIEM & Log Analysis
        ↓
Network Traffic Analysis
        ↓
Threat Detection
        ↓
Incident Investigation
        ↓
Detection Engineering
        ↓
AI-Assisted Threat Detection
```

Current focus:

- 🔎 SOC L1 investigation workflows
- 📊 SIEM / Splunk
- 🧠 Threat hunting with KQL
- 🌐 PCAP and network traffic analysis
- 🛡️ Snort detection engineering
- 🐧 Linux security monitoring
- 🤖 AI agents for threat detection
- 🚨 Incident response

---

## 🎯 Career Objective

I'm pursuing **SOC Analyst, Cybersecurity Analyst, Security Operations, Network Security, and related internship opportunities** where I can contribute my networking background while continuing to develop as a security analyst.

I am especially interested in teams where I can gain experience investigating **SIEM alerts, suspicious network traffic, endpoint activity, phishing, authentication anomalies, and other security events**.

---

## 📫 Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)]([YOUR-LINKEDIN-URL])
[![GitHub](https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white)]([YOUR-GITHUB-URL])
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:[YOUR-EMAIL])

---

### 🛡️ Open to Cybersecurity Opportunities

**SOC Analyst Internships • Cybersecurity Internships • Network Security • Security Operations • IT Security**

> **Networking taught me how systems communicate. Cybersecurity is teaching me how to detect when that communication becomes malicious.**

⭐ Explore my repositories below to see my security labs, detection rules, investigations, and networking projects.
