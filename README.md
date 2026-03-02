# Internee.pk-Cybersecurity-Task1
# Task 1: Endpoint Security & Monitoring (Wazuh EDR)

## 📌 Project Overview
As part of my internship at Internee.pk, I deployed and configured a Wazuh EDR (Endpoint Detection and Response) solution to protect internal devices and servers from unauthorized access and malware.

## 🛠️ Implementation Steps

### 1. EDR Deployment
- **Manager:** Deployed on Ubuntu 24.04.
- **Agent:** Successfully registered a local endpoint using the Wazuh CLI.
- **Verification:** Verified communication via the `agent_control` utility.

![Agent Status](./agent-status.jfif) 
*Caption: Terminal output confirming the agent is "Active".*

---

### 2. File Integrity Monitoring (FIM)
- Configured the `syscheck` engine to monitor critical directories.
- Verified real-time detection by modifying system files and checking the logs.

![FIM Proof](./fim-config.jfif)
*Caption: Command line verification of directory monitoring.*

---

### 3. Automated Alerting & Log Analysis
- Successfully ingested logs and verified automated alerts for suspicious behavior.
- Analyzed `alerts.log` for cryptographic hashes (MD5/SHA256) of modified files.

![Alerts Log](./alerts-log.jfif)
*Caption: Raw log entries showing automated security alerts.*

---

## 🚀 Key Takeaways
- Mastered Wazuh backend management via CLI.
- Understood the importance of real-time telemetry in a SOC environment.
- Configured FIM to detect potential ransomware activities.
