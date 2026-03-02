# Cloud-Based-SOC-Detection-Engineering-Lab
Sysmon + Wazuh | Docker | Hostinger VPS | Windows 11 Endpoint

Project Summary
This project demonstrates the design and deployment of a cloud-hosted SOC monitoring environment using:

Microsoft Sysmon (Windows 11 endpoint telemetry)
Wazuh SIEM (Dockerized deployment)
Hostinger VPS (cloud infrastructure)
Secure remote log forwarding
MITRE ATT&CK-aligned detection engineering
The objective was to simulate a small enterprise SOC environment and implement low-noise, production-oriented endpoint detection.

Log Flow
Windows 11 Endpoint ->Sysmon -> Wazuh Agent -> Encrypted Log Forwarding -> Hostinger VPS (Dockerized Wazuh Stack)
