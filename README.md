# 👨‍💻 Antonnio Macharia — IT Support Portfolio

> Aspiring IT Support Specialist with hands-on experience in data systems, scripting automation, technical documentation, and infrastructure analysis. Passionate about solving technical problems and delivering reliable, user-focused solutions.

---

## 📋 Table of Contents

- [About Me](#about-me)
- [Technical Skills](#technical-skills)
- [Projects](#projects)
  - [🖥️ Project 1: Home Lab — Virtual Machine Environment Setup](#️-project-1-home-lab--virtual-machine-environment-setup)
  - [🌐 Project 2: Network Design & Simulation — Cisco Packet Tracer](#-project-2-network-design--simulation--cisco-packet-tracer)
  - [🎫 Project 3: Help Desk Ticketing System — osTicket Deployment](#-project-3-help-desk-ticketing-system--osticket-deployment)
  - [🔒 Project 4: Active Directory Lab — Windows Server Administration](#-project-4-active-directory-lab--windows-server-administration)
  - [📊 Project 5: Automated Data Pipeline & Anomaly Detection](#-project-5-automated-data-pipeline--anomaly-detection)
  - [📋 Project 6: IT Documentation Hub](#-project-6-it-documentation-hub)
- [Certifications & Learning](#certifications--learning)
- [Contact](#contact)

---

## About Me

I am an aspiring IT Support Specialist with a strong foundation in data analysis, scripting, and system administration. My background includes building automated data pipelines, performing statistical analysis on large datasets, and creating technical documentation for non-technical users.

I am actively building hands-on IT support skills through home lab environments, network simulations, and system administration projects. I am currently pursuing the **Google IT Support Professional Certificate** and working toward **CompTIA A+**.

**What drives me:** I enjoy diagnosing problems, understanding how systems work under the hood, and translating complex technical issues into simple, actionable solutions for end users.

---

## Technical Skills

| Category | Skills |
|---|---|
| **Operating Systems** | Windows 10/11, Windows Server, Ubuntu Linux |
| **Networking** | TCP/IP, DNS, DHCP, VLANs, Subnetting, Cisco Packet Tracer |
| **Scripting & Automation** | Python, PowerShell, Bash |
| **Data & Analysis Tools** | SQL, Excel, R, Hadoop/Hive |
| **IT Support Tools** | osTicket, Active Directory, VirtualBox, VMware |
| **Documentation** | Technical writing, SOPs, troubleshooting guides |
| **Other** | Git, GitHub, Data cleaning, Anomaly detection |

---

## Projects

---

### 🖥️ Project 1: Home Lab — Virtual Machine Environment Setup

**Status:** ✅ Complete  
**Tools:** VirtualBox, Windows 10, Ubuntu 22.04 LTS  
**Folder:** [`/home-lab`](./home-lab/)

#### Overview

Built a fully functional home lab using VirtualBox to simulate a real-world IT environment. This lab is used to practice OS installation, user management, troubleshooting, and system configuration — all core tasks in an IT Support role.

#### What I Did

- Installed and configured **VirtualBox** on a host machine
- Deployed two virtual machines:
  - **Windows 10** — simulating a standard end-user workstation
  - **Ubuntu 22.04 LTS** — simulating a Linux server environment
- Configured **network adapters** (NAT and Host-Only) to test connectivity between VMs
- Practised common IT support tasks including:
  - OS installation from ISO images
  - Driver installation and hardware troubleshooting
  - Creating and managing local user accounts
  - Setting file and folder permissions
  - Simulating common end-user issues (printer errors, connectivity problems, account lockouts) and resolving them

#### Key Takeaways

- Gained confidence with OS-level troubleshooting on both Windows and Linux
- Understood how virtual networks differ from physical ones and how to configure them
- Learned how to snapshot VMs before making changes — a critical habit for safe IT work

#### Screenshots

> *(Screenshots of VM setup, network configuration, and user management available in [`/home-lab/screenshots`](./home-lab/screenshots/))*

---

### 🌐 Project 2: Network Design & Simulation — Cisco Packet Tracer

**Status:** ✅ Complete  
**Tools:** Cisco Packet Tracer, NetAcad  
**Folder:** [`/networking`](./networking/)

#### Overview

Designed and simulated a small office network using Cisco Packet Tracer. This project demonstrates my understanding of fundamental networking concepts that are critical in IT support — including IP addressing, routing, and network troubleshooting.

#### What I Designed

- A **small office network** with the following components:
  - 1 Router
  - 2 Managed Switches
  - 8 End-user PCs across 2 departments (Finance & HR)
  - 1 Printer (network-shared)
  - 1 Server (DNS + DHCP)

#### What I Configured

- **IP Addressing Scheme** — Planned and assigned a `192.168.1.0/24` subnet with static IPs for servers and DHCP for workstations
- **DNS** — Configured a local DNS server so devices can resolve hostnames internally
- **DHCP** — Set up automatic IP assignment for all workstations
- **VLANs** — Separated Finance and HR departments into different VLANs for security
- **Inter-VLAN Routing** — Configured the router to allow controlled communication between VLANs
- **Ping & Traceroute Testing** — Verified connectivity across all devices and documented results

#### Troubleshooting Scenarios Practiced

- Diagnosing and fixing IP conflicts
- Resolving a misconfigured default gateway
- Fixing a VLAN trunk port that was blocking traffic

#### Key Takeaways

- Solidified understanding of the OSI model in practice
- Learned how to systematically isolate and fix network faults
- Understood why VLANs are important for security in business environments

#### Files

> *(Network diagram image and `.pkt` simulation file available in [`/networking`](./networking/))*

---

### 🎫 Project 3: Help Desk Ticketing System — osTicket Deployment

**Status:** ✅ Complete  
**Tools:** osTicket, XAMPP, PHP, MySQL  
**Folder:** [`/helpdesk-ticketing`](./helpdesk-ticketing/)

#### Overview

Deployed and configured **osTicket**, a widely used open-source help desk ticketing system, on a local server. This project simulates the kind of ticketing workflows used in real IT support departments, including ticket intake, assignment, escalation, and resolution.

#### What I Set Up

- Installed **XAMPP** to host a local Apache + MySQL + PHP environment
- Downloaded and installed **osTicket v1.18**
- Configured the following:
  - **Departments:** IT Support, Network Team, Software Support
  - **Help Topics:** Password Reset, Hardware Issue, Software Installation, Network Connectivity, New User Setup
  - **SLA Plans:** Defined response and resolution times (e.g., Critical = 1hr response, 4hr resolution)
  - **Agents:** Created 3 support agent accounts with different permission levels
  - **End-User Portal:** Configured the customer-facing portal for submitting tickets

#### Simulated Ticket Scenarios

| Ticket # | Issue | Priority | Resolution |
|---|---|---|---|
| #001 | User cannot log in — account locked | High | Reset via admin panel, documented steps |
| #002 | Laptop not connecting to office Wi-Fi | Medium | Identified wrong DNS setting, corrected manually |
| #003 | New employee laptop setup request | Low | Created checklist SOP, assigned to onboarding team |
| #004 | Software installation request — Adobe Acrobat | Low | Approved and documented installation steps |

#### Key Takeaways

- Understood how IT tickets are created, triaged, and escalated in a real support environment
- Learned the importance of **SLA management** and keeping users updated
- Practised writing **clear, professional ticket notes** for handoff between agents

#### Files

> *(Setup guide and screenshots available in [`/helpdesk-ticketing`](./helpdesk-ticketing/))*

---

### 🔒 Project 4: Active Directory Lab — Windows Server Administration

**Status:** ✅ Complete  
**Tools:** Windows Server 2019 (Evaluation), VirtualBox, Active Directory, Group Policy  
**Folder:** [`/active-directory`](./active-directory/)

#### Overview

Deployed a **Windows Server 2019** virtual machine and configured **Active Directory Domain Services (AD DS)** to simulate how IT admins manage users, groups, and security policies in a corporate environment.

#### What I Configured

**Domain Setup**
- Installed Windows Server 2019 on a VirtualBox VM
- Promoted the server to a **Domain Controller** for the domain `macharia.local`
- Joined a Windows 10 VM to the domain as a client machine

**User & Group Management**
- Created **Organizational Units (OUs):** IT, Finance, HR, Management
- Created **20+ user accounts** with proper naming conventions (e.g., `a.macharia`)
- Created **Security Groups** and assigned users based on department
- Configured **password policies:** minimum 8 characters, complexity required, 90-day expiry

**Group Policy (GPO)**
- Configured and linked GPOs to OUs:
  - Disabled USB storage for Finance department (security policy)
  - Set desktop wallpaper company-wide via GPO
  - Mapped a shared network drive automatically on login
  - Restricted access to Control Panel for standard users

**Common Admin Tasks Practised**
- Unlocking locked-out user accounts
- Resetting user passwords
- Moving users between OUs
- Disabling accounts for departed employees
- Viewing and interpreting event logs

#### Key Takeaways

- Gained practical experience with the most widely used directory service in enterprise IT
- Understood how Group Policy is used to enforce security and consistency across an organisation
- Learned proper account lifecycle management — from onboarding to offboarding

#### Files

> *(Step-by-step setup guide, GPO screenshots, and OU structure diagram in [`/active-directory`](./active-directory/))*

---

### 📊 Project 5: Automated Data Pipeline & Anomaly Detection

**Status:** ✅ Complete  
**Tools:** Python (pandas, matplotlib, seaborn), R (tidyverse)  
**Folder:** [`/data-pipeline`](./data-pipeline/)

#### Overview

Built an automated data cleaning and anomaly detection pipeline that processes **50,000+ bank transactions**. While this project originated as a data analysis exercise, it directly demonstrates IT-relevant skills including **scripting automation, system monitoring logic, and anomaly/alert flagging** — all applicable to IT operations and security monitoring.

#### What I Built

**Data Cleaning Pipeline (Python)**
- Automated ingestion of raw transaction data (CSV)
- Handled missing values, duplicate records, and formatting inconsistencies
- Standardised date formats and normalised amount fields
- Reduced manual data preparation work by **90%**

**Anomaly Detection Logic**
- Developed rule-based flagging logic to identify suspicious transactions
- Flagged **4.9% of transactions** as high-risk based on:
  - Unusual transaction amounts (statistical outliers using IQR method)
  - Transactions outside normal business hours
  - High-frequency activity from a single account within a short window
- Output: CSV report of flagged records with risk scores

**IT Relevance**
This same logic pattern is used in IT for:
- **Network traffic monitoring** — flagging unusual data spikes
- **Security alerting** — identifying abnormal login attempts
- **System health monitoring** — detecting performance outliers

#### Key Outputs

- Clean, analysis-ready dataset
- Anomaly flag report (4.9% of records flagged)
- 4 EDA visualisations showing transaction patterns

#### Key Takeaways

- Learned how to write reusable, automated scripts — a critical IT skill
- Understood how threshold-based alerting works in monitoring systems
- Strengthened Python scripting ability applicable to IT automation tasks

---

### 📋 Project 6: IT Documentation Hub

**Status:** 🔄 Ongoing  
**Tools:** Markdown, GitHub  
**Folder:** [`/documentation`](./documentation/)

#### Overview

Created a library of clear, detailed IT support documentation written for both technical and non-technical audiences. Good documentation is one of the most valued skills in IT Support — it reduces repeat tickets, speeds up onboarding, and ensures consistent service delivery.

#### Documents Created

| Document | Description |
|---|---|
| `password-reset-guide.md` | Step-by-step guide for resetting user passwords in Active Directory |
| `new-employee-setup-sop.md` | Standard Operating Procedure for onboarding a new employee's workstation |
| `troubleshooting-no-internet.md` | Structured troubleshooting guide for resolving connectivity issues |
| `slow-pc-diagnosis.md` | Checklist and steps for diagnosing and fixing a slow computer |
| `printer-not-printing.md` | Common printer issues and how to resolve them |
| `vpn-setup-guide.md` | End-user guide for setting up a VPN client |

#### Writing Approach

Each document follows a consistent format:
- **Problem statement** — clearly defines the issue
- **Who this is for** — identifies the audience (end user or IT technician)
- **Prerequisites** — what is needed before starting
- **Step-by-step instructions** — numbered, clear, and jargon-free where appropriate
- **Expected outcome** — what success looks like
- **Escalation path** — when to escalate to a senior technician

#### Key Takeaways

- Learned how to write for different audiences (end users vs. technicians)
- Understood the value of SOPs in reducing resolution time and ensuring consistency
- Practised structuring knowledge base articles in a format used by tools like ServiceNow and Confluence

---

## Certifications & Learning

| Certification / Course | Provider | Status |
|---|---|---|
| Google IT Support Professional Certificate | Coursera / Google | 🔄 In Progress |
| CompTIA A+ | CompTIA | 🔄 Studying |
| Cisco Networking Basics | Cisco NetAcad | ✅ Complete |
| TryHackMe — Pre-Security Path | TryHackMe | 🔄 In Progress |

---

## Contact

**Antonnio Macharia**  
🐙 [GitHub: antonnio-macharia](https://github.com/antonnio-macharia)

---

*Last updated: April 2026*
