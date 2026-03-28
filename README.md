# Wazuh - TheHive - Cortex - MISP Threat Intelligence Automation

---

## 📌 Overview

This project demonstrates an end-to-end SOC automation workflow integrating Wazuh, TheHive, Cortex, and MISP for threat detection, case management, and threat intelligence sharing.

The lab simulates credential dumping using Mimikatz and automatically performs alert generation, case creation, IOC enrichment, and incident response.

---

## 🎯 Objectives

- Detect malicious activity using Wazuh + Sysmon
- Trigger automated case creation in TheHive
- Enrich IOCs using Cortex analyzers
- Share threat intelligence with MISP
- Perform incident response workflow
- Automate SOC case management

---

## 🛠️ Tools & Technologies

- Wazuh SIEM
- Sysmon
- TheHive
- Cortex
- MISP
- Windows Endpoint
- Ubuntu Server
- API Integrations

---

## 🏗️ Architecture Diagram
<img src="https://github.com/Prashant42125/Wazuh-TheHive-Cortex-MISP-Threat-Intelligence-Automation/blob/main/Threat-intelligence-and-case-management-diagram.png" width="900px"/>
 ---

## ⚙️ Workflow

1. Mimikatz executed on Windows endpoint
2. Sysmon logs process creation event
3. Wazuh agent detects suspicious activity
4. Custom rule triggers alert
5. Wazuh server sends alert to TheHive
6. TheHive automatically creates incident case
7. Cortex analyzers enrich IOCs
8. Indicators shared with MISP
9. Incident response tasks executed
10. Case documented and closed

---

## 🚨 Detection Scenario

- Malware: Mimikatz
- Attack Type: Credential Dumping
- Detection Method: Sysmon Process Monitoring
- Wazuh Rule ID: 100002
- Severity: Medium

---

## 🔍 Cortex Analyzers Used

- AbuseIPDB
- VirusTotal
- MalwareBazaar

These analyzers enrich:

- IP Address
- File Hash
- Malware Reputation
- Threat Intelligence

---

## 📊 TheHive Case Tasks

- Initial Alert Investigation
- IOC Extraction
- IOC Enrichment using Cortex
- Share Indicators with MISP
- Contain Compromised Endpoint
- Incident Documentation
- Case Closure

---

## 🧠 MISP Threat Intelligence

Event Created: Credential Dumping Malware (Mimikatz)

Attributes:
- SHA256 Hash
- Filename
- Source IP
- Tags
- MITRE ATT&CK Mapping

MITRE ATT&CK:
- T1003 - OS Credential Dumping
- T1003.005 - Cached Domain Credentials

---

## 📈 Data Collected

- Process execution logs
- Source IP
- File hash
- Threat intelligence results
- Malware classification
- Incident timeline
- IOC indicators

---

## 🧠 Skills Demonstrated

- SIEM Detection Engineering
- SOAR Case Management
- Threat Intelligence Integration
- Incident Response Workflow
- IOC Enrichment
- SOC Automation
- Blue Team Operations

---

## 🎓 Learning Outcomes

- Wazuh custom rule creation
- TheHive case management
- Cortex analyzer integration
- MISP threat intelligence sharing
- End-to-end SOC automation

---

## 👤 Author

Prashant  
CEHv13 | SOC Analyst | Blue Team | Threat Intelligence Enthusiast
