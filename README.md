# HTB-Fawn: Network Reconnaissance & Service Exploitation 🚀

> A comprehensive cybersecurity lab showcasing infrastructure enumeration, active service profiling, and target exploitation using advanced reconnaissance frameworks.

![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-HackTheBox-blue?style=for-the-badge)
![Category](https://img.shields.io/badge/Category-Penetration%20Testing-red?style=for-the-badge)

---

## 📌 Academic Evaluation Details

This laboratory project was executed as part of the security curriculum guidelines under structural academic evaluation:

* [cite_start]**Institution:** Air University, Islamabad [cite: 12]
* [cite_start]**Student Name:** Noor Malik [cite: 7]
* [cite_start]**Roll Number:** 230964 [cite: 8]
* [cite_start]**Section:** BSIT-VI-B [cite: 9]
* [cite_start]**Submitted To:** Sir Ayaz [cite: 11]

---

## 📱 Project Overview

**HTB-Fawn** is an infrastructure auditing project focused on identifying severe data-exposure risks caused by misconfigured organizational services. The lab workflow scales from boundary scanning to unauthenticated system exploitation, supplemented by enterprise-level network mapping.

This lab was built to practice and showcase:
- [cite_start]Active target profiling with **Nmap (Network Mapper)** [cite: 107, 119]
- [cite_start]Vulnerability assessment of legacy application daemons [cite: 139]
- [cite_start]Cross-platform network reconnaissance using **NetBIOS** and **SNMP** utilities [cite: 175, 209]
- [cite_start]Industrial GUI scanning via **SoftPerfect Network Scanner** [cite: 284]

---

## ✨ Key Features

### 🔍 Advanced Boundary Reconnaissance
- [cite_start]Perimeter scanning of target nodes using passive and active banners (`nmap -sV`)[cite: 106, 119].
- [cite_start]Discovered **Port 21/TCP** hosting an exposed File Transfer Protocol (`vsftpd 3.0.3`) instance[cite: 139, 150, 152, 153].

### 💥 Misconfiguration Exploitation (FTP Bypass)
- [cite_start]Leveraged loose security access parameters to bypass implicit authentication protocols[cite: 160].
- [cite_start]Executed an unauthenticated session handshake using `anonymous` access keys to safely query, read, and extract hidden root directory payloads (`flag.txt`)[cite: 160, 165, 173].

### 📡 Enterprise Subnet Mapping & Active Fingerprinting
[cite_start]Extending standard boundaries to inspect localized subnet architectures (`10.10.1.22`) across heterogeneous systems[cite: 190]:
- [cite_start]**NetBIOS Cache Probing:** Leveraged script automation scripts (`--script nbstat.nse`) to map operational domain tags (`TARG_WIN7_27`)[cite: 190, 193].
- [cite_start]**SNMP Trap Analysis:** Queried Simple Network Management Protocol contexts over **Port 161/UDP** utilizing structural string iterations (`snmpwalk` & `snmp-check`) to analyze environment variables, kernel parameters, and infrastructure uptimes[cite: 212, 222, 239, 255].

### 🖥️ GUI-Based Network Share Discovery
- [cite_start]Automated corporate infrastructure mapping across active ranges (`10.10.1.5 - 10.10.1.23`) using **SoftPerfect Network Scanner**[cite: 284, 289].
- [cite_start]Enumerated active corporate domain platforms (**Windows Server 2019**) and localized hidden administrative root directories (`C$`, `Users`)[cite: 373, 374, 376].

---

## 🛠️ Tech Stack

- [cite_start]**Operating Systems:** Kali Linux (VMware Platform), Parrot Security OS [cite: 100, 177]
- [cite_start]**Target OS Enclaves:** Linux Server Base, Windows Server 2019 [cite: 277, 376]
- [cite_start]**Network Scanning Suites:** Nmap Engine, SoftPerfect Network Toolset [cite: 107, 284]

### 📚 Audited Services
- [cite_start]`FTP (vsftpd 3.0.3)` – Port 21 [cite: 139, 150, 152, 153]
- [cite_start]`NetBIOS-NS` – Port 137 [cite: 202]
- [cite_start]`SNMP Agent` – Port 161 [cite: 212, 215, 216]

---

## 🚀 How to Run & Verify

1. **Clone the repository**
   ```bash
   git clone [https://github.com/noormalik33/HTB-Fawn.git](https://github.com/noormalik33/HTB-Fawn.git)


Establish Network Connectivity
Ensure an active tunnel link to the HackTheBox target framework infrastructure via OpenVPN:

Bash
sudo openvpn your_profile.ovpn
Execute Reconnaissance Sequences
Run the initial target port assessment framework using:

Bash
nmap -sV -sC <TARGET_IP>
Test Service Authentication Boundary
Connect to the target vector anonymously:

Bash
ftp <TARGET_IP>
# Username: anonymous | Password: [Leave Blank]
🎯 Learning Outcomes
Implementing structured, multi-tier enumeration plans across corporate networks.

Recognizing internal architectural mapping hazards due to default administration credentialing.

Querying core environmental data tables from open SNMP configuration contexts.

Generating end-to-end security audit logs for deployment inside vulnerability frameworks.

## 📄 License
This project is licensed under the MIT License.
See the LICENSE file for more details.

## Contributing 🤝
Contributions are welcome! Please fork the repository, make changes, and submit a pull request. Report bugs or suggest features via GitHub Issues. 🌟

Contact 📬
For questions, feedback, or collaboration, reach out to:

---

## 👨‍💻 Developer

**Noor Malik**
IT Student | Full-Stack Software Developer | Android App Developer 
  
📍 Islamabad, Pakistan  
📧 Email: noormalik56500@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/noormalik56500/)

Social 📱

📧 Email:coreittech1@gmail.com  
📹 YouTube1: https://www.youtube.com/@CoreITTech1  
📹 YouTube2: https://www.youtube.com/@CoreITTech  
📸 Instagram: https://www.instagram.com/coreit.tech  
📘 Facebook: https://www.facebook.com/share/1AmgLDUnc9/

---


💡 If you like this project, don’t forget to star ⭐ it on GitHub!

Happy hunting! 🚀 Let’s build secure infrastructures together! 💪

⭐ If you found this project helpful, feel free to star the repository!
🧠 Created for educational and portfolio demonstration purposes
