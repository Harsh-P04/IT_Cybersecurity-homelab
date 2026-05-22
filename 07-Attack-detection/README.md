# Attack Simulation & Detection

## Objective

Simulate attacker behavior and investigate detections using Wazuh SIEM to develop hands-on SOC analysis, threat hunting, and incident investigation experience.

This phase focused on identifying suspicious activity, attacker reconnaissance, PowerShell abuse, persistence techniques, authentication events, and lateral movement behaviors.

---

## Environment

| System | Role | IP Address |
|---------|------|-------------|
| Ubuntu Server | Wazuh SIEM | 192.168.10.30 |
| Windows Server 2022 | Monitored Endpoint | 192.168.10.10 |
| Windows 11 | Client Endpoint | 192.168.10.20 |

---

## Technologies Used

- Wazuh SIEM
- Sysmon
- PowerShell
- Windows Event Logs
- Windows Server 2022
- Windows 11

---

## Simulated Security Activities

### Reconnaissance Detection

Simulated attacker discovery activity through command execution and system enumeration.

Commands investigated included:

- whoami
- hostname
- net user
- ipconfig /all
- tasklist
- systeminfo
- Get-Process
- Get-LocalUser

---

### Persistence Monitoring

Investigated attacker persistence techniques through scheduled task creation and monitoring.

Examples:

- Scheduled Task creation
- Startup persistence behavior
- Suspicious PowerShell execution

---

### Lateral Movement Detection

Investigated potential lateral movement techniques between systems.

Examples:

- SMB communication
- Remote connectivity
- Cross-system access behavior

---

## Key Skills Demonstrated

- Threat Hunting
- Security Monitoring
- Incident Investigation
- PowerShell Analysis
- Endpoint Security
- MITRE ATT&CK Concepts
- Blue Team Investigation
- SOC Workflow

---

## MITRE ATT&CK Techniques

- T1059 – Command & Scripting Interpreter
- T1087 – Account Discovery
- T1110 – Brute Force
- T1053 – Scheduled Task
- T1021 – Remote Services

---

## Screenshots

### Reconnaissance Detection

<img width="1000" src="../screenshots/7-Attack-detection/Wazuh Reconnaissance Detection.png">

### Persistence Detection

<img width="1000" src="../screenshots/7-Attack-detection/Wazuh Persistence activity detection.png">

### Lateral Movement Detection

<img width="1000" src="../screenshots/7-Attack-detection/Wazuh Lateral movement detection.png">
