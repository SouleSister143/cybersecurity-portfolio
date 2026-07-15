# Taylor Soule | Cybersecurity Portfolio

## 👤 About Me
Welcome! I'm **Taylor Soule**, a cybersecurity student at Portland Community College pursuing an Associate of Applied Science in Cybersecurity (Expected June 2026). 

I'm passionate about Security Operations (SOC), threat detection, incident response, Windows Server administration, Active Directory, Linux, cloud security, and vulnerability management. This portfolio showcases the hands-on projects I've completed through virtual labs, coursework, and independent learning to prove my readiness for a cybersecurity internship.

---

## 🛠️ Technical Skill Inventory

* **Operating Systems:** Windows Server 2022, Windows 10/11, Ubuntu Linux, Kali Linux
* **Active Directory & GPOs:** ADUC, Group Policy Software Installation, Folder Redirection, GPO Scripts, Administrative/Security Templates
* **Network Security & Tools:** Wireshark, Zenmap, Nmap, TCP/IP troubleshooting, DNS, DHCP, VPNs, Linksys LAPAC1750PRO Emulator
* **Defensive & Security Operations:** Sguil (IDS Alerts Monitoring), Centralized Logging, Phishing Header Analysis, Email Security
* **Public Key Infrastructure (PKI):** CA (Certificate Authority) Installation, Certificate Lifecycle Management, CA Backups
* **Wireless Security & Exploitation:** WEP/WPA analysis, `aircrack-ng` suite, Packet decryption
* **Penetration Testing & Social Engineering:** Social Engineer Toolkit (SET), Web App Attacks (SQLi, XSS), Fingerprinting
* **Scripting & Troubleshooting:** Python (text parsing), Bash, Vim, System Diagnostics Tools

---

## 💻 Featured Technical Projects & Labs

### 1. Advanced Active Directory & Group Policy Management
* **Objective:** Implement advanced domain administration policies to automate software deployment, secure user profiles, and enforce configuration standards.
* **What I Did:**
    * **Automated software deployment** by configuring Group Policies to silently install required packages across domain workstations.
    * **Protected user data with Folder Redirection**, configuring GPOs to sync user desktop and document directories to a central secure server instead of saving them locally.
    * **Standardized system behaviors** using startup/shutdown and logon/logoff GPO scripts.
    * **Enforced organizational security baselines** by deploying Administrative Templates and Custom Security Templates to lockdown user settings and disable unsafe features.
* **Core Skills:** Active Directory, Group Policy Objects (GPOs), Folder Redirection, Security Baselines, Software Deployment

### 2. Public Key Infrastructure (PKI) & Certificate Management
* **Objective:** Install and manage a local Active Directory Certificate Services (AD CS) environment to secure internal network traffic.
* **What I Did:**
    * **Installed a Certificate Authority (CA)** role on Windows Server 2022 to issue and manage cryptographic keys.
    * **Managed certificates throughout their lifecycle**, including generating Certificate Signing Requests (CSRs), approving requests, revoking compromised certificates, and validating CRLs (Certificate Revocation Lists).
    * **Executed CA database maintenance** by performing secure Certificate Authority backups and registry state saves to ensure disaster recovery readiness.
* **Core Skills:** AD CS, Certificate Authority (CA), PKI, Cryptography, Disaster Recovery

### 3. Centralized Patch Management with WSUS
* **Objective:** Install and configure a patch deployment workflow to automate system updates and minimize endpoint vulnerabilities.
* **What I Did:**
    * **Set up a local update server** using the WSUS role on Windows Server 2022 to download and manage Microsoft security patches.
    * **Directed network update traffic** using GPOs so client workstations automatically pull approved updates from the local server instead of the public internet.
    * **Managed patch testing and deployment** by grouping systems, approving critical security fixes, and monitoring compliance reports to ensure no systems were left vulnerable.
* **Core Skills:** WSUS, Patch Management, GPOs, WSUS Administration, System Auditing

### 4. SIEM & IDS Event Monitoring (Sguil & Log Analysis)
* **Objective:** Monitor, parse, and respond to live network intrusion detection system (IDS) alerts using central analyst tools.
* **What I Did:**
    * **Monitored live network alerts** using the Sguil analyst console to identify active indicators of compromise (IOCs).
    * **Investigated triggered events** using raw packet payload inspection inside the alert window to separate true positive threats from benign background noise.
    * **Centralized system log collection** by configuring event forwarding from both Windows and Linux computers into a monitoring console.
* **Core Skills:** Sguil, Security Monitoring, IDS/IPS, Incident Detection, Event Verification

### 5. Wireless Network Security & Penetration Testing
* **Objective:** Configure enterprise wireless infrastructure and analyze vulnerability exposures in legacy Wi-Fi security.
* **What I Did:**
    * **Configured Wi-Fi infrastructure settings** using the Linksys LAPAC1750PRO enterprise access point emulator.
    * **Captured and compared wireless traffic** using Wireshark to inspect the structural difference between unencrypted packets and WEP/WPA encrypted packets.
    * **Simulated key recovery exploits** using the `aircrack-ng` toolkit to capture a WEP handshake, decrypt the traffic stream, and analyze the raw payloads.
* **Core Skills:** Wireless Security, Wireshark, `aircrack-ng`, WEP/WPA Decryption, Network Emulators

### 6. Active Network Fingerprinting & Reconnaissance (Nmap & Zenmap)
* **Objective:** Map active hosts, identify listening ports, and run fingerprinting scans to discover operating systems.
* **What I Did:**
    * **Mapped local network layouts** using Zenmap's graphical interface to visualize connected network nodes and topography.
    * **Discovered host operating systems** by using passive and active OS fingerprinting scans to map the exact patch state of the targets.
    * **Automated vulnerability detection** using Nmap Scripting Engine (NSE) to safely find misconfigured directories and open services.
* **Core Skills:** Zenmap, Nmap, OS Fingerprinting, Reconnaissance, Port Scanning

### 7. Social Engineering & Phishing Simulations (SE Toolkit)
* **Objective:** Perform realistic email-based social engineering tests to assess user susceptibility to phishing.
* **What I Did:**
    * **Built and launched phishing payloads** using the Social Engineer Toolkit (SET) to replicate common credential harvesting sites.
    * **Analyzed phishing email metadata** by dissecting raw SMTP header lines to check SPF, DKIM, and DMARC alignments.
    * **Compiled threat reports** listing indicators of compromise (IoCs), detailing how to trace phishing links, and outlining defensive email filtering strategies.
* **Core Skills:** Social Engineer Toolkit (SET), Social Engineering, Phishing Analysis, Threat Investigation

### 8. Linux Systems Administration, Vim, & Scripting
* **Objective:** Administer user boundaries and configure local files on Linux servers using native CLI editors and tools.
* **What I Did:**
    * **Developed terminal efficiency** by utilizing `Vim` (completed Vim Tutor) to quickly modify configuration files directly from the SSH terminal.
    * **Secured local file directories** using ownership (`chown`) and permission (`chmod`) parameters.
    * **Automated repetitive monitoring tasks** by writing basic Bash shell scripts to audit active system resources and log statuses.
* **Core Skills:** Linux Administration, CLI, Vim, Bash Scripting, File Permissions

### 9. OWASP Top 10 Web Application & Database Attacks
* **Objective:** Attack and defend web applications to evaluate backend code resilience.
* **What I Did:**
    * **Exploited input validation failures** using SQL Injection (SQLi) to bypass login panels and pull hidden database structures.
    * **Simulated cross-site attacks** via Cross-Site Scripting (XSS) to hijack browser sessions in controlled practice environments (like DVWA).
    * **Reviewed backend configurations** to show how input sanitization and parameterized queries fully prevent database exploits.
* **Core Skills:** OWASP Top 10, SQLi, XSS, Database Attacks, AppSec

### 10. Python Security Tool Automation
* **Objective:** Build custom Python utilities to scan files and parse logs automatically.
* **What I Did:**
    * **Developed log parsing scripts** in Python to search large text logs and isolate specific failed authentication events.
    * **Automated file verification workflows** using basic scripting logic (loops, functions, and file I/O operations) to sort system data and flag high-risk entries.
* **Core Skills:** Python Programming, Automation, Log Parsing, Scripting

### 11. Host-Based Security Hardening
* **Objective:** Implement local defensive controls to block system intrusion paths on both Windows and Linux hosts.
* **What I Did:**
    * **Hardened local Windows workstations** by disabling legacy protocols (SMBv1), tightening registry access rules, and managing Windows Defender configurations.
    * **Configured Linux host security** by disabling SSH root logins, changing remote port bindings, and configuring local firewalls (`ufw`) to drop unauthorized inbound traffic.
* **Core Skills:** Endpoint Security, Local Firewalls, Windows Defender, SSH Hardening

### 12. Hypervisor Management & Lab Isolation
* **Objective:** Maintain an isolated virtual network laboratory to safely execute exploits and test administrative tools.
* **What I Did:**
    * **Separated lab traffic** using custom Host-Only and NAT network structures inside VirtualBox and VMware to protect home devices from lab traffic.
    * **Configured lab rollback points** using snapshots, allocating virtual memory, and provisioning clean system images to test target tools efficiently.
* **Core Skills:** VirtualBox, VMware, Virtual Networking, Resource Allocation

---

## ⚡ Current & Upcoming Labs (In Progress)
* [ ] **AWS Identity & Access Management (IAM) Sandbox:** Currently setting up users, groups, and cross-account access roles while writing custom JSON policies to implement the Principle of Least Privilege.
      
---

## 🏆 Certifications & Training
* **CompTIA Security+** *(In Progress)*
* **AWS Academy Cloud Foundations** *(In Progress)*
* **TryHackMe Advent of Cyber** (Defensive & Threat Hunting Path completions)
* **Computer Information Systems Certificate** | Portland Community College
* **Cybersecurity Foundations Certificate** | Portland Community College

---

## 📬 Contact & Professional Links
* **Email:** TaylorSoule143@gmail.com
* **LinkedIn:** [linkedin.com/in/TaylorSouleCybersecurity](https://linkedin.com/in/TaylorSouleCybersecurity)
