# Elevate-Labs-Cyber_Internship_Task_4
Firewall Configuration &amp; Traffic Filtering

# CyberSecurity-Task4 - Setup and Use a Firewall on Windows / Linux.

**Name:** RAO JITENDRASINGH KAMLENDRASINGH
**Task:** Firewall Configuration &amp; Traffic Filtering.
**Date:** 20-11-2025

# Tools used
- Windows Defender Firewall (Advanced Settings)
- PowerShell (`Test-NetConnection`)

## Objective
- Configure a firewall on Windows (my system)
- Add and remove firewall rules
- Block a specific port (Port 23 – Telnet)
- Test the firewall configuration
- Understand how firewall traffic filtering works

# Files in this repo
- `Screenshots/` — screenshots of configuration & Filtering
      - Inbound_Rules.png
      - Outbound_Rules.png
      - WF_Advanced_Settings.png
      - WF_New_Rule.png
      - WF_Testing.png
- `README.md` — this file

# **Steps Performed**

## **Checked Current Firewall Status**
### **Windows Firewall**
- Open Windows Defender Firewall
- Click Advanced Settings
- Viewed:
        - Inbound Rules
        - Outbound Rules
- Clicked Inbound Rules → New Rule
  - Selected Port
    - Choosed TCP
    - Entered 23
- Selected Block the connection
- Named it: Telnet
- Testing:-
    - Test-NetConnection -Port 23 -ComputerName localhost
- Output :- TcpTestSucceeded : False
- Restored the blocked port, by Right-clicking on it and deleting it.










