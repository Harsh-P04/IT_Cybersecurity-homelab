# IT Support & Cybersecurity Home Lab

A hands-on enterprise-style IT Support and Cybersecurity home lab built to simulate real-world IT administration, helpdesk operations, endpoint monitoring, vulnerability management, and Security Operations Center (SOC) workflows.

This project demonstrates practical experience with Windows Server administration, Active Directory, Group Policy, Linux administration, helpdesk systems, vulnerability scanning, endpoint monitoring, SIEM deployment, and threat hunting.

---

# Lab Architecture

<img width="1000" alt="Lab Architecture" src="screenshots/lab-architecture.png">

---

# Lab Environment

| System | Role | IP Address |
|---------|------|-------------|
| Windows Server 2022 | Domain Controller / DNS / File Server | 192.168.10.10 |
| Windows 11 | Domain Joined Client | 192.168.10.20 |
| Ubuntu Server | osTicket + Wazuh SIEM | 192.168.10.30 |
| Kali Linux | Security Testing & Enumeration | 192.168.10.40 |

---

# Technologies Used

## Infrastructure & Administration

- Windows Server 2022
- Windows 11
- Ubuntu Server
- Active Directory
- Group Policy Objects (GPO)
- DNS
- SMB File Sharing
- VirtualBox
- PowerShell
- Linux CLI

## IT Support & Helpdesk

- osTicket
- Ticket Management
- User Troubleshooting
- Service Management
- System Administration

## Cybersecurity & Monitoring

- Wazuh SIEM
- Sysmon
- OpenVAS / Greenbone
- Wireshark
- Nmap
- Kali Linux
- Windows Event Logging
- Threat Hunting
- Security Monitoring

---

# Project Modules

## 1. Network Foundation

Configured enterprise-style virtual infrastructure using VirtualBox with static IP addressing and secure communication between endpoints.

### Key Skills

- VM deployment
- Network troubleshooting
- Static IP configuration
- Connectivity troubleshooting
- Virtual networking

📂 Folder: `01-network-foundation`

---

## 2. Active Directory & Group Policy

Built a Windows domain environment using Windows Server 2022 and configured Group Policy Objects (GPOs) to manage users, shared drives, and workstation settings.

### Key Skills

- Active Directory administration
- User management
- OU management
- Group Policy configuration
- Domain join
- Shared drives

📂 Folder: `02-active-directory-gpo`

---

## 3. Helpdesk Ticketing System (osTicket)

Deployed and configured osTicket on Ubuntu Server using Apache and MariaDB to simulate enterprise IT support ticket workflows.

### Key Skills

- Linux server administration
- Apache troubleshooting
- MariaDB configuration
- Helpdesk operations
- Ticket lifecycle management

📂 Folder: `03-helpdesk-osticket`

---

## 4. Network Security & Vulnerability Analysis

Performed host discovery, traffic inspection, and vulnerability assessments using industry-standard security tools.

### Tools Used

- OpenVAS / Greenbone
- Nmap
- Wireshark

### Key Skills

- Vulnerability scanning
- Port scanning
- Packet analysis
- Network reconnaissance
- Security assessment

📂 Folder: `04-network-security-analysis`

---

## 5. Endpoint Monitoring with Sysmon

Configured Sysmon to collect detailed Windows endpoint telemetry for process creation, PowerShell activity, and suspicious system behavior.

### Detection Scenarios

- PowerShell monitoring
- Process creation monitoring
- Event log analysis
- Authentication visibility

📂 Folder: `05-soc-monitoring-sysmon`

---

## 6. Wazuh SIEM Deployment

Implemented centralized security monitoring using Wazuh SIEM and integrated Windows Server and Windows endpoints for event collection and investigation.

### Capabilities Implemented

- Endpoint onboarding
- Centralized log monitoring
- Threat hunting
- Security event analysis
- PowerShell monitoring
- Authentication monitoring

📂 Folder: `06-wazuh-siem`

---

## 7. Attack Simulation & Detection

Simulated attacker behavior and investigated detections using Wazuh SIEM.

### Security Activities

- Failed login monitoring
- PowerShell execution detection
- Reconnaissance activity detection
- Endpoint telemetry analysis
- Threat hunting

### MITRE ATT&CK Concepts

- T1059 – Command & Scripting Interpreter
- T1087 – Account Discovery
- T1110 – Brute Force
- T1053 – Scheduled Task
- T1547 – Registry Run Keys

📂 Folder: `07-attack-detection`

---

# Skills Demonstrated

### IT Support

- Windows Administration
- Active Directory
- Group Policy
- Helpdesk Troubleshooting
- Ticket Management
- Endpoint Support
- DNS Troubleshooting
- SMB File Sharing
- Linux Administration

### Cybersecurity

- SIEM Monitoring
- Threat Hunting
- Sysmon Monitoring
- Windows Event Analysis
- Vulnerability Management
- Security Monitoring
- Incident Investigation
- PowerShell Analysis
- Endpoint Security

---

# Future Enhancements

- Automated alerting
- Detection engineering
- Sigma rules
- Custom Wazuh decoders
- Malware analysis
- Security orchestration

---

# Author

**Harsh Patel**  
Cybersecurity & IT Support Professional  
Ontario, Canada
