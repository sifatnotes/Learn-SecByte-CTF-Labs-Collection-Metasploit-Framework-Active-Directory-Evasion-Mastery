# Learn-SecByte-CTF-Labs-Collection-Metasploit-Framework-Active-Directory-Evasion-Mastery
A curated collection of hands-on cybersecurity CTF labs covering the Metasploit Framework Capstone, Custom Module Development, AV Evasion, Active Directory Exploitation, Pivoting &amp; Tunneling, and Social Engineering from Learn SecByte.
# Learn SecByte CTF & Cybersecurity Labs Collection

Welcome to the **Learn SecByte CTF & Cybersecurity Labs Collection**. This repository is a structured, searchable index of hands-on Metasploit Framework exploitation, custom module development, `msfvenom` automation, Active Directory exploitation, AV/EDR evasion, multi-tier network pivoting, client-side social engineering, and Linux/network foundations designed for cybersecurity students, CTF players, penetration testers, red team operators, and security researchers.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Mastering offensive security testing requires deep familiarity with industry-standard exploitation frameworks, automated payload engineering, evasive delivery mechanisms, and post-exploitation mechanics. Hosted on [Learn SecByte](https://learn.secbyte.org/), this comprehensive collection of CTF challenge labs provides rigorous, practical training across full-spectrum penetration testing workflows.

From learning Linux OS mechanics and network fundamentals to writing custom Ruby modules for the Metasploit Framework, generating obfuscated payloads with `msfvenom`, bypassing antivirus defenses, compromising Active Directory domains, pivoting through internal network subnets, executing client-side browser attacks, and completing full-scope penetration test capstones, these labs establish job-ready exploitation expertise.

---

## Lab Collection & Index

Below is the complete, searchable index of all Metasploit Framework, Active Directory, evasion, network pivoting, and offensive security foundation challenges in this collection:

| # | Lab / Challenge Name | Category | Focus / Key Topics | Lab Link |
|---|----------------------|----------|---------------------|----------|
| 1 | **Linux for Cybersecurity** | Offensive Foundations & Career Paths | Shell environment, POSIX permissions, user/group management, process auditing, security CLI utilities | [Access Lab](https://learn.secbyte.org/ctf/linux-for-cybersecurity) |
| 2 | **Network Fundamentals for Security Professionals** | Offensive Foundations & Career Paths | OSI model, TCP/IP handshake, ARP/DNS resolution, routing tables, subnetting, network packet flow | [Access Lab](https://learn.secbyte.org/ctf/network-fundamentals-for-security-professionals) |
| 3 | **Cybersecurity Career Paths and Roles** | Offensive Foundations & Career Paths | Red Team vs. Blue Team vs. Purple Team, SOC operations, pentesting, cloud security, career progression | [Access Lab](https://learn.secbyte.org/ctf/cybersecurity-career-paths-and-roles) |
| 4 | **Full Penetration Test Using the Metasploit Framework Capstone** | Metasploit & Exploitation Capstone | End-to-end pentest, workspace management, multi-stage exploitation, Meterpreter post-modules, reporting | [Access Lab](https://learn.secbyte.org/ctf/full-penetration-test-using-the-metasploit-framework-capston) |
| 5 | **Evasion Techniques and Antivirus Bypass** | Evasion & Payload Automation | Encoder chaining, shellcode obfuscation, memory injection, AV signature/heuristic evasion | [Access Lab](https://learn.secbyte.org/ctf/evasion-techniques-and-antivirus-bypass) |
| 6 | **Developing and Customizing Metasploit Modules** | Metasploit & Exploitation Capstone | Ruby module syntax, `Msf::Exploit` mixins, writing custom auxiliary scanners and exploit modules | [Access Lab](https://learn.secbyte.org/ctf/developing-and-customizing-metasploit-modules) |
| 7 | **Active Directory Enumeration and Exploitation Mastery** | Active Directory & Advanced Operations | Kerberoasting, AS-REP Roasting, BloodHound graph analysis, token impersonation, DCSync attacks | [Access Lab](https://learn.secbyte.org/ctf/active-directory-enumeration-and-exploitation-mastery) |
| 8 | **Pivoting, Routing & Network Tunneling** | Active Directory & Advanced Operations | Autoroute, `portfwd`, SOCKS4a/SOCKS5 proxying, Chisel, Ligolo-ng, routing across internal subnets | [Access Lab](https://learn.secbyte.org/ctf/pivoting-routing-network-tunneling) |
| 9 | **Privilege Escalation with Metasploit** | Metasploit & Exploitation Capstone | `local_exploit_suggester`, Token manipulation (`incognito`), UAC bypass modules, SYSTEM access | [Access Lab](https://learn.secbyte.org/ctf/privilege-escalation-with-metasploit) |
| 10 | **Automating Tasks with Resource Scripts and msfvenom** | Evasion & Payload Automation | Automated Metasploit resource scripts (`.rc`), `msfvenom` payload generation, custom stagers | [Access Lab](https://learn.secbyte.org/ctf/automating-tasks-with-resource-scripts-and-msfvenom) |
| 11 | **Client-Side Attacks, Social Engineering & Browser Trust** | Evasion & Payload Automation | Malicious document generation, HTA attacks, spear-phishing payload delivery, browser exploitation | [Access Lab](https://learn.secbyte.org/ctf/client-side-attacks-social-engineering-browser-trust) |
| 12 | **Exploiting Web Applications with Metasploit** | Metasploit & Exploitation Capstone | Web scanner integration, CMS exploitation (WordPress/Drupal), SQLi/RCE web modules | [Access Lab](https://learn.secbyte.org/ctf/exploiting-web-applications-with-metasploit) |

---

## Categories

### 1. Metasploit Framework, Custom Modules & Capstone
Master the industry-standard exploitation framework, develop custom Ruby modules, automate tasks with resource scripts, and execute full-scope pentesting capstones.
- [Exploiting Web Applications with Metasploit](https://learn.secbyte.org/ctf/exploiting-web-applications-with-metasploit)
- [Privilege Escalation with Metasploit](https://learn.secbyte.org/ctf/privilege-escalation-with-metasploit)
- [Developing and Customizing Metasploit Modules](https://learn.secbyte.org/ctf/developing-and-customizing-metasploit-modules)
- [Full Penetration Test Using the Metasploit Framework Capstone](https://learn.secbyte.org/ctf/full-penetration-test-using-the-metasploit-framework-capston)

### 2. Antivirus Evasion, Payload Automation & Social Engineering
Generate custom payload stagers, automate execution with `msfvenom`, bypass antivirus defenses, and craft client-side social engineering vectors.
- [Automating Tasks with Resource Scripts and msfvenom](https://learn.secbyte.org/ctf/automating-tasks-with-resource-scripts-and-msfvenom)
- [Evasion Techniques and Antivirus Bypass](https://learn.secbyte.org/ctf/evasion-techniques-and-antivirus-bypass)
- [Client-Side Attacks, Social Engineering & Browser Trust](https://learn.secbyte.org/ctf/client-side-attacks-social-engineering-browser-trust)

### 3. Active Directory Exploitation & Network Pivoting
Map and exploit Active Directory domain structures, harvest domain credentials, and route attack traffic through compromised internal subnets.
- [Pivoting, Routing & Network Tunneling](https://learn.secbyte.org/ctf/pivoting-routing-network-tunneling)
- [Active Directory Enumeration and Exploitation Mastery](https://learn.secbyte.org/ctf/active-directory-enumeration-and-exploitation-mastery)

### 4. Offensive Security Foundations & Industry Roles
Establish essential Linux system mechanics, master TCP/IP networking, and explore career pathways across offensive and defensive domains.
- [Linux for Cybersecurity](https://learn.secbyte.org/ctf/linux-for-cybersecurity)
- [Network Fundamentals for Security Professionals](https://learn.secbyte.org/ctf/network-fundamentals-for-security-professionals)
- [Cybersecurity Career Paths and Roles](https://learn.secbyte.org/ctf/cybersecurity-career-paths-and-roles)

---

## Learning Path

Follow this structured progression path to master penetration testing workflows, Metasploit development, and network pivoting:

1. **Phase 1: Linux, Networking & Career Foundations** — Build command-line fluency and understand network protocol mechanics:
   - [Linux for Cybersecurity](https://learn.secbyte.org/ctf/linux-for-cybersecurity)
   - [Network Fundamentals for Security Professionals](https://learn.secbyte.org/ctf/network-fundamentals-for-security-professionals)
   - [Cybersecurity Career Paths and Roles](https://learn.secbyte.org/ctf/cybersecurity-career-paths-and-roles)

2. **Phase 2: Payload Generation, Scripting & Evasion** — Automate payload creation, bypass AV solutions, and craft social engineering vectors:
   - [Automating Tasks with Resource Scripts and msfvenom](https://learn.secbyte.org/ctf/automating-tasks-with-resource-scripts-and-msfvenom)
   - [Evasion Techniques and Antivirus Bypass](https://learn.secbyte.org/ctf/evasion-techniques-and-antivirus-bypass)
   - [Client-Side Attacks, Social Engineering & Browser Trust](https://learn.secbyte.org/ctf/client-side-attacks-social-engineering-browser-trust)

3. **Phase 3: Metasploit Exploitation & Module Engineering** — Exploit web applications, escalate local privileges, and code custom Metasploit modules:
   - [Exploiting Web Applications with Metasploit](https://learn.secbyte.org/ctf/exploiting-web-applications-with-metasploit)
   - [Privilege Escalation with Metasploit](https://learn.secbyte.org/ctf/privilege-escalation-with-metasploit)
   - [Developing and Customizing Metasploit Modules](https://learn.secbyte.org/ctf/developing-and-customizing-metasploit-modules)

4. **Phase 4: AD Takeover, Pivoting & Full Pentest Capstone** — Pivot across internal networks, compromise Active Directory domains, and complete the end-to-end capstone:
   - [Pivoting, Routing & Network Tunneling](https://learn.secbyte.org/ctf/pivoting-routing-network-tunneling)
   - [Active Directory Enumeration and Exploitation Mastery](https://learn.secbyte.org/ctf/active-directory-enumeration-and-exploitation-mastery)
   - [Full Penetration Test Using the Metasploit Framework Capstone](https://learn.secbyte.org/ctf/full-penetration-test-using-the-metasploit-framework-capston)

---

## How to Use the Labs

1. Select a challenge link from the index or category sections above.
2. Read the scenario requirements and target environment directives on [Learn SecByte](https://learn.secbyte.org/).
3. Deploy penetration testing toolsets (Metasploit Framework `msfconsole`, `msfvenom`, BloodHound, Impacket, Chisel, Ruby, Burp Suite) inside an isolated laboratory environment.
4. Craft obfuscated payloads, run Metasploit exploit modules, route traffic through SOCKS proxies, escalate host/domain privileges, and retrieve target flags.

---

## Disclaimer

This repository and its linked challenge resources are strictly intended for educational, threat research, and authorized technical training purposes. Never execute Metasploit modules, `msfvenom` payloads, or network pivoting tools against unauthorized systems, production infrastructure, or unapproved third-party networks.
