# Incident Response Report – Brute Force Attempt

## 🆔 Incident Summary
- **Incident Type:** Brute Force Login Attempt
- **Detected By:** Wazuh SIEM
- **Affected System:** Windows Endpoint
- **Severity Level:** Medium

---

## ⏱ Timeline
- Alert triggered after multiple failed authentication attempts
- SOC analyst reviewed and validated the alert
- Investigation confirmed malicious behavior

---

## 🔎 Investigation Findings
- Repeated failed logon events (Event ID 4625)
- Single source IP address
- No successful login observed

---

## 🛠 Actions Taken
- Alert triaged and classified
- Attack pattern identified
- Mitigation steps recommended

---

## 📌 Lessons Learned
- Importance of monitoring authentication logs
- SIEM effectiveness in detecting brute-force attacks
- Need for proactive account lockout policies
