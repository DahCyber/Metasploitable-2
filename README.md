# Metasploit Exploitation with Metasploitable 2

## Overview
This project demonstrates the use of **Kali Linux** and **Metasploit** to exploit known vulnerabilities in **Metasploitable 2**, a purpose-built vulnerable VM. The goal was to gain unauthorized access, escalate privileges, and understand common exploitation techniques used in penetration testing.

## Objectives
- Set up a virtual penetration testing lab using VirtualBox.
- Discover vulnerable services using Nmap.
- Exploit vulnerabilities using Metasploit.
- Escalate privileges from user to root.
- Understand the attack lifecycle in a controlled environment.

## Lab Setup

### 1. Tools Used
- **Kali Linux** (Attacker VM)
- **Metasploitable 2** (Target VM)
- **VirtualBox** for virtualization
- **Nmap**, **Metasploit Framework**

### 2. Network Configuration
- Both VMs connected via **Host-Only Adapter** for isolated testing.
- Verified connectivity with `ping` and `nmap` scans.

---

## Exploitation Steps

### 1. Reconnaissance with Nmap
```bash
nmap -sS -sV -O 192.168.56.101
