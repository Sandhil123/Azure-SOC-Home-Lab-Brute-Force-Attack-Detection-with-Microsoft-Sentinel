# Azure-SOC-Home-Lab-Brute-Force-Attack-Detection-with-Microsoft-Sentinel
Built a cloud-based SOC home lab using Microsoft Azure and Microsoft Sentinel to detect, analyse, and visualise real-world brute-force attacks against a Windows virtual machine using SecurityEvent logs, KQL queries, GeoIP enrichment, and Sentinel workbooks.

<img width="940" height="448" alt="image" src="https://github.com/user-attachments/assets/f1e8d210-ef0e-488b-99d0-deb2bdb9d628" />


<img width="940" height="523" alt="image" src="https://github.com/user-attachments/assets/69fc0ca5-057e-4983-8e8e-3763c6dcfdba" />


## Overview

This project demonstrates a cloud-based SOC home lab built using Microsoft Azure and Microsoft Sentinel. The lab simulates real-world brute-force authentication attacks against a Windows virtual machine and analyses them using centralized log collection and SIEM capabilities.


## What Was Implemented

- Deployed a Windows 10 virtual machine in Azure
- Collected Windows SecurityEvent logs using Azure Monitor Agent
- Forwarded logs to a Log Analytics Workspace
- Enabled Microsoft Sentinel for SIEM analysis
- Detected failed login attempts (Event ID 4625) using KQL
- Enriched attacker IPs with GeoIP data using Sentinel watchlists
- Visualised attack origins on a world map using Sentinel workbooks



## Tools & Technologies
- Microsoft Azure
- Microsoft Sentinel
- Log Analytics Workspace
- Azure Monitor Agent
- KQL (Kusto Query Language)


## Purpose

This lab was created for hands-on learning and portfolio demonstration of SOC analyst and blue-team skills, including log analysis, threat detection, and security visualisation.

---


