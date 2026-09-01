# 🛡️ Mini SOC Lab – Security Monitoring & Incident Triage

## 📌 Project Overview

This project demonstrates a Mini Security Operations Center (SOC) Lab built for centralized security monitoring, alert detection, and incident triage.

The lab collects and analyzes security events from a Windows endpoint using Sysmon and Wazuh. Security alerts are investigated by analyzing process activity, command lines, parent-child processes, and suspicious behavior.

---

## 🏗️ Architecture

Windows Endpoint
        ↓
Sysmon Event Logs
        ↓
Wazuh Agent
        ↓
Wazuh Manager
        ↓
Wazuh Dashboard
        ↓
Alert Monitoring & Incident Triage

---

## 🛠️ Tools & Technologies

- Wazuh
- Sysmon
- Windows
- Ubuntu
- Wazuh Agent
- Wazuh Manager
- MITRE ATT&CK
- Wireshark
- Linux

---

## 🎯 Project Objectives

- Monitor Windows security events centrally.
- Collect Sysmon logs using Wazuh.
- Detect suspicious activities.
- Perform initial alert triage.
- Analyze process creation events.
- Investigate command-line activity.
- Analyze parent-child processes.
- Map suspicious activity to MITRE ATT&CK techniques.
- Document and escalate security incidents.

---

## 🔍 Monitoring & Detection

The SOC Lab monitors events such as:

- Process Creation
- Suspicious Command Execution
- PowerShell Activity
- File and Directory Discovery
- Windows Security Events
- Sysmon Event ID 1

---

## 🚨 Incident Triage Process

1. Monitor security alerts in the Wazuh Dashboard.
2. Identify suspicious events.
3. Analyze the Event ID.
4. Check the process name and command line.
5. Analyze parent and child processes.
6. Investigate the affected endpoint.
7. Map activity to MITRE ATT&CK.
8. Classify the alert.
9. Escalate suspicious or confirmed incidents.

---

## 📊 Example Investigation

### Alert Type
Suspicious Process Activity

### Investigation Steps

- Check the alert details.
- Identify the affected endpoint.
- Analyze the process image.
- Review the command line.
- Check the parent process.
- Identify suspicious behavior.
- Map the activity to MITRE ATT&CK.
- Document the investigation findings.

---

## 🧠 Skills Demonstrated

- SIEM Monitoring
- Security Log Analysis
- Alert Triage
- Incident Investigation
- Windows Event Analysis
- Sysmon Monitoring
- Wazuh Administration
- MITRE ATT&CK Mapping
- Basic Incident Response

---

## 📸 Screenshots
### Failed Login Alert

![Failed Login Alert](screenshots/screenshots/failed-login-alert.png)

- Wazuh Dashboard
- Connected Windows Agent
- Sysmon Event Logs
- Security Alerts
- Process Creation Events
- Incident Investigation

---

## 📚 Key Learnings

- Understanding SOC workflows.
- Centralized log monitoring using Wazuh.
- Endpoint monitoring using Sysmon.
- Security alert investigation.
- Process and command-line analysis.
- Incident triage and escalation.
- MITRE ATT&CK mapping.

---

## 👨‍💻 Author

**Kishor Kumar K**

Aspiring SOC Analyst | Cybersecurity Student

GitHub: Add your GitHub profile link here  
LinkedIn: Add your LinkedIn profile link here
