# SOC Monitoring with Sysmon

## Objective

Deploy and configure Sysmon to collect detailed Windows endpoint telemetry and improve security visibility for process monitoring, PowerShell activity, network connections, and suspicious system behavior.

This phase focused on endpoint monitoring, threat hunting, Windows event analysis, and identifying suspicious activity using Sysmon logs.

---

## Environment

| System | Role | IP Address |
|---------|------|-------------|
| Windows Server 2022 | Monitored Endpoint | 192.168.10.10 |

---

## Technologies Used

- Sysmon
- Windows Event Viewer
- PowerShell
- Sysinternals

---

## Tasks Performed

- Installed and configured Sysmon
- Monitored Windows process creation events
- Investigated PowerShell activity
- Monitored network connections and traffic
- Investigated suspicious file downloads
- Analyzed Windows event logs
- Performed threat hunting using Sysmon telemetry

---

## Detection Scenarios

- Process creation monitoring
- PowerShell execution analysis
- Network traffic visibility
- File download investigation
- Threat hunting and log analysis
- Firewall-related event monitoring

---

## Key Skills Demonstrated

- Threat Hunting
- Endpoint Monitoring
- Windows Event Analysis
- PowerShell Investigation
- Process Monitoring
- Network Analysis
- Blue Team Investigation

---

## Screenshots

### Windows Event Monitoring

<img width="1000" src="../screenshots/5-Sysmon/Sysmon Windows logs.png">

### Network Traffic Monitoring

<img width="1000" src="../screenshots/5-Sysmon/Sysmon Network Traffic logs.png">

### File Download Investigation

<img width="1000" src="../screenshots/5-Sysmon/Sysmon file download investigation.png">

### PowerShell Analysis

<img width="1000" src="../screenshots/5-Sysmon/Sysmon log and powershell analysis report.png">

### Threat Hunting & Firewall Analysis

<img width="1000" src="../screenshots/5-Sysmon/Threat hunting and firewall logs.png">
