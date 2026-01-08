# 🔐 SOC Home Lab – Threat Detection & Incident Response

## 👤 About Me
I am an aspiring **SOC Analyst** with hands-on experience in building and operating a cybersecurity home lab focused on threat detection, log analysis, and incident response using SIEM technologies.

This project demonstrates practical SOC workflows, not just theoretical knowledge.

---

## 🎯 Project Objective
The objective of this lab is to simulate real-world security incidents and analyze them from a **Security Operations Center (SOC)** perspective, including:
- Monitoring security events
- Detecting malicious activity
- Investigating alerts
- Performing basic incident response actions

---

## 🧱 Lab Architecture
**Environment Components:**
- **SIEM:** Wazuh
- **Endpoint:** Windows (Monitored System)
- **Attacker Machine:** Kali Linux
- **Virtualization:** VMware
- **Log Sources:** Windows Event Logs

The lab is designed to replicate a small enterprise SOC environment.

---

## 🔎 Security Scenarios Covered
- Brute-force login attack detection
- Failed authentication analysis (Windows Event ID 4625)
- Alert triage and validation
- Log correlation and investigation
- Basic incident response workflow

---

## 🛠 Tools & Technologies
- Wazuh SIEM
- Windows Event Viewer
- Kali Linux
- Nmap
- Wireshark
- VMware Workstation

---

## 🧪 SOC Workflow Demonstrated
1. **Event Collection** – Logs collected from Windows endpoints via Wazuh agent  
2. **Detection** – SIEM alerts triggered based on suspicious behavior  
3. **Triage** – Initial alert validation and severity assessment  
4. **Investigation** – Log analysis and correlation  
5. **Response** – Recommended containment and mitigation actions  

---

## 📂 Repository Structure
