# Wazuh SIEM SOC Lab

## 📌 Project Overview
This project demonstrates a basic Security Operations Center (SOC) setup using Wazuh SIEM for real-time security monitoring and log analysis.

## 🧰 Tools Used
- Wazuh SIEM
- Kali Linux
- Ubuntu
- Hydra
- VirtualBox

## ⚙️ Lab Setup
- Kali Linux (Attacker Machine)
- Ubuntu (Victim Machine with Wazuh Agent)
- Wazuh Server (Monitoring Server)

## 🚨 Attack Simulation
- Simulated SSH brute-force attack using Hydra
- Generated multiple authentication attempts on victim system

## 🔍 Detection & Monitoring
- Monitored logs using Wazuh dashboard
- Detected failed login attempts and security alerts
- Analyzed logs using queries like `sshd` and rule-based filters

## 📊 Outcome
Successfully demonstrated how SIEM detects suspicious activities and supports SOC monitoring.
