# Cybersecurity-task-4

# Task 4 — Firewall Configuration (Windows)

## 🔰 Objective
Configure and test basic firewall rules on Windows to understand how firewall controls network traffic.

---

## 🛠 Steps Performed

### 1) Opened Windows Firewall Advanced Settings
- Searched "Windows Defender Firewall"
- Clicked **Advanced settings** to open the management console

### 2) Viewed Existing Inbound Rules
- Navigated to **Inbound Rules**
- Observed existing allow/deny rules applied to ports and apps

### 3) Created Rule to Block Port 23 (Telnet)
- Clicked **New Rule → Port**
- Selected **TCP** and entered port `23`
- Chose **Block the connection**
- Applied rule to **Domain, Private, Public**
- Named rule `Block Telnet Port 23`

### 4) (Optional Test)
- Telnet connection was tested / rule confirmed added

### 5) Deleted the Rule (Restore Original State)
- Located rule `Block Telnet Port 23`
- Right-clicked → **Delete**

---

## 📸 Screenshots Included
1. Firewall Advanced Settings Window
2. Inbound Rules List
3. Rule Created for Port 23
4. Rule Deletion/Final State

---

## 🧠 Key Concepts Learned

### What is a firewall?
A firewall is a security system that monitors and filters network traffic based on rules to protect systems from unauthorized access.

### Why Block Port 23 (Telnet)?
- Telnet is unencrypted and transmits credentials in plaintext
- Hackers often exploit it for remote access
- SSH (port 22) is recommended instead

### Inbound vs Outbound Rules
- **Inbound Rules**: Control traffic coming **into** the device
- **Outbound Rules**: Control traffic **leaving** the device

---

## ✅ Outcome
Successfully created, tested, and removed firewall rule — demonstrating understanding of:
- Traffic filtering
- Ports and protocol control
- Basic security hardening using firewall rules

---
