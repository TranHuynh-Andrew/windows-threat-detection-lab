# windows-threat-detection-lab
A hands-on SOC lab simulating multi-stage Windows attacks (MITRE ATT&amp;CK) with Sysmon logging, Wazuh XDR detection, and real-time Telegram alerts.
# Windows Threat Detection & Attack Simulation Lab

## Overview
An end-to-end SOC laboratory environment demonstrating threat detection, adversary simulation (MITRE ATT&CK), and real-time security monitoring using a Windows 11 Endpoint, Sysmon, Wazuh XDR/SIEM, and Telegram integration.

## Architecture
- **Target Endpoint:** Windows 11 Pro/Enterprise (Sysmon + Audit Policy)
- **SIEM / XDR Manager:** Wazuh Manager (Ubuntu Server)
- **Alert Channel:** Telegram SOC Operations Group
- **Attack Simulation:** PowerShell / Atomic Red Team

## Progress Checklist
- [x] Phase 1: Environment Architecture & Repository Initialization
- [ ] Phase 2: Windows 11 Deployment & Sysmon Configuration
- [ ] Phase 3: Wazuh Agent Integration & Sysmon Log Routing
- [ ] Phase 4: Attack Simulation & Rule Validation
