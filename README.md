# IT Support & Cybersecurity Home Lab

## Lab Architecture

<img width="1000" alt="Lab Architecture" src="screenshots/Architecture/lab-architecture.png">

A hands-on enterprise-style IT Support and Cybersecurity home lab built to simulate real-world IT administration, helpdesk operations, endpoint monitoring, vulnerability management, and SOC (Security Operations Center) workflows.

This project demonstrates practical experience with Windows Server administration, Active Directory, Group Policy, Linux administration, helpdesk systems, vulnerability scanning, endpoint monitoring, SIEM deployment, and threat hunting.

---

# Lab Overview

## Lab Environment

| System | Role | IP Address |
|---------|------|-------------|
| Windows Server 2022 | Domain Controller / DNS / File Server | 192.168.10.10 |
| Windows 11 | Domain Joined Client | 192.168.10.20 |
| Ubuntu Server | osTicket + Wazuh SIEM | 192.168.10.30 |
| Kali Linux | Security Testing | 192.168.10.40 |

---

# Technologies Used

## Infrastructure & Administration

- Windows Server 2022
- Windows 11
- Ubuntu Server
- Active Directory
- DNS
- SMB File Sharing
- VirtualBox
- PowerShell
- Linux CLI

## IT Support & Helpdesk

- osTicket
- Ticket Troubleshooting
- Service Management
- User Support
- System Administration

## Cybersecurity & Monitoring

- Wazuh SIEM
- Sysmon
- OpenVAS
- Wireshark
- Nmap
- Kali Linux
- Threat Hunting
- Security Monitoring
- Windows Event Logs

---

# Project Modules

## 1. Network Foundation

Configured enterprise-style virtual infrastructure using VirtualBox with networking, remote access, and shared resources.

### Skills Demonstrated

- Network troubleshooting
- Remote access
- Drive mapping
- Connectivity testing
- Virtual networking

### Screenshots

#### Lab Setup

<img width="1000" src="screenshots/1-Network/Lab setup.png">

---

## 2. Active Directory & Group Policy

Built a Windows domain environment using Windows Server 2022 and configured Group Policy Objects (GPOs).

### Skills Demonstrated

- Active Directory administration
- Domain management
- Group Policy
- Drive mapping
- User administration

### Screenshots

#### Drive Mapping

<img width="1000" src="screenshots/2-Active-directory/Hard Drive mapping.png">

#### Remote Connection

<img width="1000" src="screenshots/2-Active-directory/Remote Connection.png">

#### Week Progress

<img width="1000" src="screenshots/2-Active-directory/Week 2.png">

---

## 3. Helpdesk Ticketing System (osTicket)

Deployed and configured osTicket on Ubuntu Server to simulate real enterprise IT support ticket workflows.

### Skills Demonstrated

- Linux Administration
- Apache Troubleshooting
- MariaDB Configuration
- Helpdesk Operations
- Ticket Resolution

### Screenshots

<img width="1000" src="screenshots/3-Osticket/Ticket System Install Software.png">

<img width="1000" src="screenshots/3-Osticket/Ticket System Printer not working.png">

<img width="1000" src="screenshots/3-Osticket/Ticket System Drive missing.png">

<img width="1000" src="screenshots/3-Osticket/Ticket System account lockedout.png">

<img width="1000" src="screenshots/3-Osticket/Ticket System Password reset.png">

---

## 4. Network Security Analysis

Performed vulnerability scanning, traffic analysis, and network enumeration using cybersecurity tools.

### Tools Used

- OpenVAS
- Wireshark
- Nmap

### Skills Demonstrated

- Vulnerability Assessment
- Packet Analysis
- Network Enumeration
- Threat Identification

### Screenshots

<img width="1000" src="screenshots/4-Network-security/Nmap network enumeration report.png">

<img width="1000" src="screenshots/4-Network-security/OpenVAS vulnerability scanning.png">

<img width="1000" src="screenshots/4-Network-security/Wireshark DNS Scan.png">

<img width="1000" src="screenshots/4-Network-security/Wireshark SMB Kerberos and LDAP.png">

---

## 5. Endpoint Monitoring with Sysmon

Configured Sysmon to collect endpoint telemetry for process monitoring, PowerShell analysis, and network visibility.

### Skills Demonstrated

- Windows Event Monitoring
- PowerShell Analysis
- Network Traffic Analysis
- Threat Hunting

### Screenshots

<img width="1000" src="screenshots/5-Sysmon/Sysmon Windows logs.png">

<img width="1000" src="screenshots/5-Sysmon/Sysmon Network Traffic logs.png">

<img width="1000" src="screenshots/5-Sysmon/Sysmon file download investigation.png">

<img width="1000" src="screenshots/5-Sysmon/Sysmon log and powershell analysis report.png">

<img width="1000" src="screenshots/5-Sysmon/Threat hunting and firewall logs.png">

---

## 6. Wazuh SIEM Monitoring

Implemented centralized monitoring and threat hunting using Wazuh SIEM.

### Skills Demonstrated

- SIEM Administration
- Endpoint Monitoring
- Threat Hunting
- Security Event Analysis

### Screenshots

<img width="1000" src="screenshots/6-Wazuh/Wazuh SIEM monitoring and threat hunting.png">

<img width="1000" src="screenshots/6-Wazuh/Wazuh threat hunting dashboard snapshot.png">

---

## 7. Attack Simulation & Detection

Simulated attacker behavior and investigated detections using Wazuh SIEM.

### Detection Scenarios

- Reconnaissance Detection
- Persistence Monitoring
- Lateral Movement Detection
- Threat Investigation

### Screenshots

<img width="1000" src="screenshots/7-Attack-detection/Wazuh Reconnaissance Detection.png">

<img width="1000" src="screenshots/7-Attack-detection/Wazuh Persistence activity detection.png">

<img width="1000" src="screenshots/7-Attack-detection/Wazuh Lateral movement detection.png">

---

# Skills Demonstrated

## IT Support

- Active Directory
- Group Policy
- Helpdesk Troubleshooting
- Ticket Management
- Windows Administration
- Linux Administration
- DNS Troubleshooting
- SMB File Sharing

## Cybersecurity

- SIEM Monitoring
- Threat Hunting
- Sysmon Monitoring
- Vulnerability Management
- Security Event Analysis
- Incident Investigation
- PowerShell Monitoring
- Endpoint Security

---

# Author

**Harsh Patel**  
Cybersecurity & IT Support Professional  
Ontario, Canada
