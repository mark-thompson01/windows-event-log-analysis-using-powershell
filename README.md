# 🧪 Windows Event Log Analysis Using PowerShell

## 📖 Overview

This lab demonstrates how to **analyze, filter, and export Windows Event Logs using PowerShell**, without relying on the Event Viewer GUI.

The goal is to showcase **real-world systems administration and incident response workflows** using console-first techniques that apply to Windows Server environments, remote administration scenarios, and security investigations.

All commands in this lab are designed to be:

- ✅ Practical  
- 🔁 Reproducible  
- 🛠️ Useful in real operational environments  

---

## 💻 Platform

- **Windows Server 2022** (GUI or Core)
- **PowerShell** (run as Administrator)

> While demonstrated on Windows Server 2022, most commands also apply to modern Windows client systems.

<img width="1542" height="874" alt="image" src="https://github.com/user-attachments/assets/9f15757c-9a39-47f4-a19f-aed3291223bf" />


---

## 🎯 Lab Objectives

- Enumerate available Windows event logs
- Query **System** and **Security** logs using PowerShell
- Filter events by:
  - Event ID
  - Time range
  - Severity level
  - Provider
- Identify:
  - Service failures
  - System reboots
  - Failed and successful logons
  - Privileged logons
  - After-hours activity
  - Scheduled task execution
- Export event data to CSV for reporting and documentation
- Simulate real-world troubleshooting and incident response scenarios

---

## ❓ Why This Matters

In many production environments:

- 🖥️ GUI access is limited or unavailable  
- 🌐 Servers are managed remotely  
- ⚡ Administrators need fast, scriptable insight into system behavior  
- 📁 Logs must be collected as **evidence**, not just viewed  

This lab demonstrates how **PowerShell can be used as a primary event analysis tool**, not merely an alternative to Event Viewer.

---

## 🔍 What This Lab Covers

### 🔹 Event Log Enumeration

- Listing all available event logs
- Understanding log size, retention, and record counts

---

### 🔹 System Log Analysis

- Service start/stop activity
- Unexpected shutdowns and reboots
- System uptime tracking
- Error and critical event identification

---

### 🔹 Security Log Analysis

- Failed logon attempts (**Event ID 4625**)
- Successful logons (**Event ID 4624**)
- Privileged logons (**Event ID 4672**)
- Logon and logoff correlation
- After-hours authentication activity

---

### 🔹 Troubleshooting & Investigation Scenarios

- Detecting service crashes
- Identifying reboot causes
- Reviewing system errors
- Tracking scheduled task execution
- Recognizing patterns across event IDs

---

### 🔹 Reporting & Exporting

- Exporting filtered logs to CSV
- Creating artifacts suitable for:
  - 🛡️ Incident response
  - 🔄 Change reviews
  - 📋 Audit support
  - 📊 Management reporting
