# SOC Portfolio

Welcome to my cybersecurity lab! This repo documents my hands-on practice simulating real-world attacks and building detections using Splunk, Windows Event Logs, and common red team tools. My goal is to showcase my explorations and to document my skills gained using the lab.

---

## 🔧 Lab Overview

### 🔹 Blue Team Tools
- **Splunk Enterprise (Ubuntu) :** SIEM for log aggregation, detection, and analysis
- **Tsurugi Linux:** Forensics and secure investigation tasks

### 🔸 Red Team Tools
- **Kali Linux:** Main red team VM for offensive tooling
  - Tools: CrackMapExec, Mimikatz, Impacket, BloodHound, etc.
- **Metasploitable 2 & Chronos:** Vulnerable machines for exploitation practice

### 🧪 Malware Analysis
- **FlareVM (Windows):** Static and dynamic malware analysis
- **REMnux (Linux):** Linux-based malware reverse engineering

### 🏛️ Active Directory Lab
- **Windows Server 2019:** Domain Controller
- **Windows 10 Enterprise (2x Clients):** AD user workstations

### 🌐 Infrastructure & Security
- **pfSense:** Firewall and network segmentation between lab subnets

---

## 📁 Contents

### [attacks/](./attacks)
Step-by-step walkthroughs of simulated attacks 

### [detections/](./detections)
Detection logic, Splunk searches, Sigma rules, baseline event log analysis

### [reports/](./reports)
Mock incident reports and investigation summaries based on lab activity

### [assets/](./assets)
Screenshots and visuals to support documentation

---

## 📌 Goals

- Simulate full attack chains based on MITRE ATT&CK and Unified Kill Chain
- Build detections and investigate attacks
- Document and share my journey exploring the cybersecurity field

---

## 💡 Currently Working on
- Using credentials acquired from AS-REP Roasting to escalate privilege
- Identifying lateral movement opportunities
- Establishing persistence mechanisms for long term access


