<div align="center">

# Brandon Roos McClinton

**Detection Engineering · Cloud Security · Security Automation**

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brandon-roos-mcclinton/)
[![Portfolio](https://img.shields.io/badge/-Portfolio-1a1a1a?style=for-the-badge&logo=github&logoColor=white)](https://brandonroos.github.io)

</div>

---

## 👋 About Me

Security professional with **7 years across IT and security operations**, working at the intersection of **detection engineering, cloud security, and security automation**.

I'm also the **founder of [Cyber Obsidian LLC](https://cyberobsidian.com)** — a Virginia-registered MSSP serving SMB clients, where I run engagements end to end: **security posture reviews** mapped to NIST CSF 2.0 and CIS Controls, **SentinelOne EDR** deployment, **MDM rollout** across mixed Mac/Windows environments, and ongoing **incident response** — phishing and spoofing investigation, anomalous-login analysis, and formal incident reporting with root-cause analysis.

What makes my background unusual: **I write software *and* run security operations.** That combination is why I build detection tooling rather than just operating it.

**Currently:** preparing for CompTIA Security+, and building a virtualized SOC lab on Proxmox for hands-on detection engineering.

---

## 🤖 AI + Security

AI is becoming table stakes in security work, so I build with it rather than around it:

- **AI-augmented detection & triage** — layering LLM-based alert enrichment and summarization on top of my Wazuh SIEM, running a **local model on-prem** so log data (auth events, internal IPs, hostnames) never leaves the network
- **Deterministic-first architecture** — events are matched against known ATT&CK signatures and IOC patterns *before* anything reaches a model. Rule-based logic handles the known cases; AI handles the ambiguous tail. Cheaper, testable, and better engineering
- **Security automation** — Python-based pipelines for data collection, enrichment, and workflow automation, including an Apify → Notion scraping and aggregation pipeline
- **Daily practitioner** — I use AI tooling in real workflows and understand where it fails, which is the part most security teams are still figuring out

---

## 🎯 What I'm Looking For

**SOC Analyst** · **Cloud Security Engineer** · **DevSecOps Engineer**

Roles where the work rewards building systems, not just monitoring them. Open to the **Northern Virginia / DC cleared contractor market** and relocating for the right fit.

---

## 🚀 Projects

| Project | Description |
|---|---|
| [🏠 Home Lab & SOC Detection Lab](https://github.com/BrandonRoos/Home-Lab) | Segmented VLAN network on pfSense with Twingate zero-trust access and Quad9 DNS filtering — paired with a virtualized SOC lab on Proxmox running Wazuh SIEM, adversary emulation via Atomic Red Team, and custom MITRE ATT&CK-mapped detection rules |
| [🔎 HashDetect — Hash Type Identifier](https://github.com/BrandonRoos/hashdetect) | Python CLI that identifies hash types (MD5, SHA-1/256/512, bcrypt, NTLM, and more) by length, charset, and pattern with confidence scoring, JSON export, and batch processing — built for IR and threat-hunting workflows |
| [🎣 Phishing Campaign Analysis](https://github.com/BrandonRoos/Mastercard-SIM-Phishing-) | Phishing email analysis and campaign-results interpretation — identifying at-risk teams and building a targeted security-awareness training plan |
| [🔑 Keystroke Logging & Detection Study](https://github.com/BrandonRoos/Keystroke-Forensics-AES) | Security research analyzing input-capture techniques (MITRE ATT&CK T1056.001) with a focus on detection via Sysmon and SIEM telemetry |
| [🔐 AES Encryption & Decryption Tool](https://github.com/BrandonRoos/Encryption-and-Decryption-PY-AES) | Python Fernet (AES-128-CBC + HMAC) encryption tool for secure data transmission and storage |
| [🛡️ Secure Password Generator](https://github.com/BrandonRoos/Python_GeneratePassword) | Python password generator using the `secrets` CSPRNG, enforcing complexity rules and security best practices |

---

## 🛠️ Tools & Technologies

**SIEM & Detection**

![Splunk](https://img.shields.io/badge/-Splunk-000000?&style=for-the-badge&logo=Splunk&logoColor=white)
![Wazuh](https://img.shields.io/badge/-Wazuh-005C99?style=for-the-badge)
![Elastic](https://img.shields.io/badge/-Elastic%20(ELK)-005571?&style=for-the-badge&logo=Elastic&logoColor=white)
![Microsoft Sentinel](https://img.shields.io/badge/-Microsoft%20Sentinel-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Sigma](https://img.shields.io/badge/-Sigma%20Rules-8A2BE2?style=for-the-badge)
![MITRE ATT&CK](https://img.shields.io/badge/-MITRE%20ATT%26CK-E11B22?style=for-the-badge)

**Network Security & Analysis**

![Wireshark](https://img.shields.io/badge/-Wireshark-1679A7?&style=for-the-badge&logo=Wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/-Nmap-4682B4?style=for-the-badge)
![pfSense](https://img.shields.io/badge/-pfSense-333333?style=for-the-badge&logo=pfsense&logoColor=white)
![Suricata](https://img.shields.io/badge/-Suricata-EF3B2D?style=for-the-badge)

**Identity & Cloud Security**

![Microsoft Entra ID](https://img.shields.io/badge/-Microsoft%20Entra%20ID-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Microsoft 365](https://img.shields.io/badge/-Microsoft%20365-D83B01?style=for-the-badge&logo=microsoft365&logoColor=white)
![Google Workspace](https://img.shields.io/badge/-Google%20Workspace-4285F4?style=for-the-badge&logo=googleworkspace&logoColor=white)

**Endpoint & Vulnerability Management**

![SentinelOne](https://img.shields.io/badge/-SentinelOne-6B0AEA?style=for-the-badge)
![Sysmon](https://img.shields.io/badge/-Sysmon-0078D4?style=for-the-badge)
![Nessus](https://img.shields.io/badge/-Nessus-00A3E0?style=for-the-badge)
![OpenVAS](https://img.shields.io/badge/-OpenVAS-4B8BBE?style=for-the-badge)

**AI & Automation**

![Claude](https://img.shields.io/badge/-Claude-D97757?style=for-the-badge&logo=claude&logoColor=white)
![ChatGPT](https://img.shields.io/badge/-ChatGPT-74AA9C?style=for-the-badge&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/-Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Ollama](https://img.shields.io/badge/-Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Apify](https://img.shields.io/badge/-Apify-FF9013?style=for-the-badge&logo=apify&logoColor=white)
![Notion](https://img.shields.io/badge/-Notion-000000?style=for-the-badge&logo=notion&logoColor=white)

**Programming & Scripting**

![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PowerShell](https://img.shields.io/badge/-PowerShell-5391FE?style=for-the-badge&logo=powershell&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![Java](https://img.shields.io/badge/-Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/-C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)

**Web Development**

![Next.js](https://img.shields.io/badge/-Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/-React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white)

**Infrastructure & Cloud**

![Proxmox](https://img.shields.io/badge/-Proxmox%20VE-E57000?style=for-the-badge&logo=proxmox&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Portainer](https://img.shields.io/badge/-Portainer-13BEF9?style=for-the-badge&logo=portainer&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Microsoft Azure](https://img.shields.io/badge/-Microsoft%20Azure-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Kali Linux](https://img.shields.io/badge/-Kali%20Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)

---

## 🧠 Core Competencies

**Security Operations** — Incident Response · Threat Hunting · Log Analysis · Phishing & Spoofing Analysis · Anomalous-Login Investigation · Root-Cause Analysis · Security Reporting

**Detection Engineering** — SIEM Operations · Detection-as-Code (Sigma) · Adversary Emulation (Atomic Red Team) · Rule Tuning & False-Positive Reduction

**Cloud & Identity** — Identity & Access Management (IAM) · Cloud Threat Defense · MFA/SSO · Endpoint Management (MDM)

**Governance & Frameworks** — MITRE ATT&CK · NIST Cybersecurity Framework (CSF 2.0) · CIS Controls · Vulnerability Management · Security Posture Assessment

**Engineering** — Security Automation · Python Tooling · Infrastructure & Virtualization · Network Security (TCP/IP, Firewalls, IDS/IPS)

---

## 🎓 Education

**M.S., Information Technology** — Software Design & Management
Liberty University

**B.S., Information Technology** — Data Networking & Security
Liberty University · *NSA/DHS CAE in Cyber Defense-designated program*

---

## 📜 Certifications & Training

| Credential | Focus | |
|:---|:---|:---|
| **Google Cybersecurity Certificate** | Incident response, SIEM tools, network security fundamentals | [Verify ↗](https://www.credly.com/badges/3e648525-b2f8-404c-b6ac-276163e10eb7/public_url) |
| **Google Data Analytics Certificate** | Data analysis, SQL, visualization, and reporting | [Verify ↗](https://www.credly.com/badges/1308cc78-207a-41c0-8cbd-64caeb317d02/public_url) |

**In progress:** CompTIA Security+ (SY0-701) → AWS Solutions Architect – Associate

---

<div align="center">

*Building security systems, not just operating them.*

</div>
