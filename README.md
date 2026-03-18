
# Real-Time Threat Detection and SOC Monitoring using Splunk, Sysmon and Attack Simulation

## Project Description

This project simulates a Security Operations Center (SOC) environment using Splunk SIEM, Sysmon, and Windows logs to monitor and detect cyber attacks in real time.

The lab environment includes attack simulation, log forwarding, alert creation, and dashboard monitoring.

## Tools Used

- Splunk Enterprise
- Sysmon
- Windows 10
- Kali Linux
- VMware

## Architecture

Kali Linux (Attacker)
        ↓
Windows Machine with Sysmon
        ↓
Splunk SIEM Server
        ↓
Dashboard + Alerts

## Attacks Simulated

1. Port Scan Detection (Nmap)
2. Flood / Ping Attack
3. Suspicious Process Execution
4. Registry Modification Activity
5. Brute Force Login Attack

## Detection Methods

- Sysmon Event Logs
- Windows Security Logs
- Splunk Search Queries
- Real-time Alerts
- Dashboard Visualization

## Alerts Created

- Port Scan Alert
- Flood Detection Alert
- Process / Registry Alert
- Brute Force Alert

## Dashboard Panels

- Network Activity
- Process Activity
- Registry Activity
- Failed Logins
- Alerts Panel
- Top Attacker IP

SOC Lab Project for SOC Analyst preparation!
