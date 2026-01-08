# Brute Force Attack Detection – SOC Case Study

## 📌 Scenario Overview
A brute-force attack was simulated against a Windows endpoint to evaluate the SIEM’s ability to detect repeated failed authentication attempts.

The objective was to identify suspicious login behavior and perform SOC-level alert triage and investigation.

---

## 🧪 Attack Simulation
- Multiple failed login attempts were generated from a Kali Linux machine.
- The target system was a Windows endpoint monitored by Wazuh.
- Authentication failures were logged in Windows Security Event Logs.

---

## 🚨 Alert Detection
Wazuh generated multiple alerts indicating repeated failed authentication attempts within a short time frame.

**Relevant Event ID:**
- `4625` – Failed logon attempt

---

## 🔍 Investigation & Analysis
During the investigation, the following indicators were observed:
- High frequency of failed login attempts
- Consistent source IP address
- Same target account
- Short time interval between attempts

This behavior matches common brute-force attack patterns.

---

## 🧠 SOC Assessment
- **Threat Type:** Brute Force Attack
- **Severity:** Medium
- **MITRE ATT&CK:** T1110 – Brute Force
- **False Positive:** No

---

## 🛡 Recommended Response Actions
- Block source IP address
- Reset affected user account password
- Enable account lockout policy
- Continue monitoring for similar activity

---

## 📎 Conclusion
The alert was confirmed as a brute-force attack attempt. Proper detection and analysis validated the SIEM’s effectiveness in identifying authentication-based threats.
