# Awesome-Cybersecurity-CTF-Labs-Collection-Linux-Windows-Privilege-Escalation
A curated, searchable index of hands-on cybersecurity and CTF labs covering Linux and Windows privilege escalation, persistence, and post-exploitation techniques from Learn SecByte.
# Cybersecurity & CTF Labs: Privilege Escalation & Post-Exploitation Collection

A curated index of hands-on cybersecurity labs and CTF challenges covering Linux and Windows privilege escalation, persistence techniques, and misconfiguration analysis hosted on Learn SecByte.

This collection is designed for cybersecurity students, CTF players, penetration testers, security analysts, and red/blue team practitioners seeking practical, hands-on security training.

---

## Table of Contents
- [Introduction](#introduction)
- [Lab Collection & Index](#lab-collection--index)
- [Categories](#categories)
  - [Linux Privilege Escalation](#linux-privilege-escalation)
  - [Windows Privilege Escalation & Persistence](#windows-privilege-escalation--persistence)
- [Learning Path](#learning-path)
- [How to Use the Labs](#how-to-use-the-labs)
- [Disclaimer](#disclaimer)

---

## Introduction

Privilege escalation and post-exploitation are core components of penetration testing, red teaming, and defensive security. Understanding how misconfigurations lead to system compromise enables security professionals to better audit, defend, and harden operating systems.

This repository organizes hands-on cybersecurity labs from Learn SecByte into logical learning paths covering both Linux and Windows security concepts.

---

## Lab Collection & Index

| Lab Title | Target OS | Primary Category | Access Link |
| :--- | :--- | :--- | :--- |
| **Linux Capabilities Abuse** | Linux | Privilege Escalation / Defense | [Access Lab](https://learn.secbyte.org/ctf/capabilities-abuse-linux-privilege-escalation-defense) |
| **Writable PATH Abuse** | Linux | Privilege Escalation | [Access Lab](https://learn.secbyte.org/ctf/writable-path) |
| **Cron Job Exploitation** | Linux | Misconfigurations | [Access Lab](https://learn.secbyte.org/ctf/cron-job-exploitation-from-misconfiguration-to-root) |
| **SUID Binary Abuse** | Linux | Privilege Escalation | [Access Lab](https://learn.secbyte.org/ctf/suid-abuse-from-enumeration-to-privilege-escalation) |
| **Named Pipe Impersonation** | Windows | Token & Process Abuse | [Access Lab](https://learn.secbyte.org/ctf/named-pipe-impersonation) |
| **Scheduled Task Abuse** | Windows | Persistence & Detection | [Access Lab](https://learn.secbyte.org/ctf/scheduled-task-abuse-from-discovery-to-detection) |
| **UAC Bypass Mechanics** | Windows | Auto-Elevation & Abuse | [Access Lab](https://learn.secbyte.org/ctf/uac-bypass-understanding-windows-auto-elevation-and-abuse-pa) |
| **Token Impersonation Fundamentals** | Windows | Token Abuse | [Access Lab](https://learn.secbyte.org/ctf/token-impersonation-fundamentals-and-abuse) |
| **Registry Autoruns Hunting** | Windows | Persistence | [Access Lab](https://learn.secbyte.org/ctf/registry-autoruns-hunting-persistence) |
| **AlwaysInstallElevated Abuse** | Windows | Privilege Escalation | [Access Lab](https://learn.secbyte.org/ctf/alwaysinstallelevated-windows-privilege-escalation) |
| **Weak Service Permissions** | Windows | Service Exploitation | [Access Lab](https://learn.secbyte.org/ctf/weak-service-permissions-escalation-through-misconfigured-wi) |

---

## Categories

### Linux Privilege Escalation
Hands-on CTF labs focusing on identifying and exploiting Linux system misconfigurations to escalate from low-privilege access to root:

* **Linux Capabilities:** Explores POSIX capabilities abuse and defensive mechanisms.
  * Lab Link: https://learn.secbyte.org/ctf/capabilities-abuse-linux-privilege-escalation-defense
* **Writable PATH Hijacking:** Practical abuse of environment `$PATH` variables for binary execution takeover.
  * Lab Link: https://learn.secbyte.org/ctf/writable-path
* **Cron Job Misconfigurations:** Identifying scheduled jobs running with elevated privileges and vulnerable write permissions.
  * Lab Link: https://learn.secbyte.org/ctf/cron-job-exploitation-from-misconfiguration-to-root
* **SUID Binary Abuse:** System enumeration to identify and exploit misconfigured SUID binaries.
  * Lab Link: https://learn.secbyte.org/ctf/suid-abuse-from-enumeration-to-privilege-escalation

### Windows Privilege Escalation & Persistence
Ethical hacking labs centered on Windows process internal mechanisms, service permissions, auto-elevation, and token manipulation:

* **Named Pipe Impersonation:** Understanding inter-process communication and security context impersonation.
  * Lab Link: https://learn.secbyte.org/ctf/named-pipe-impersonation
* **Scheduled Task Abuse:** From discovery to threat hunting and detection.
  * Lab Link: https://learn.secbyte.org/ctf/scheduled-task-abuse-from-discovery-to-detection
* **UAC Bypass:** Understanding Windows auto-elevation mechanisms and bypass techniques.
  * Lab Link: https://learn.secbyte.org/ctf/uac-bypass-understanding-windows-auto-elevation-and-abuse-pa
* **Token Impersonation:** Core fundamentals of Windows primary/impersonation tokens and access delegation.
  * Lab Link: https://learn.secbyte.org/ctf/token-impersonation-fundamentals-and-abuse
* **Registry Autoruns:** Hunting for startup persistence mechanisms in the Windows Registry.
  * Lab Link: https://learn.secbyte.org/ctf/registry-autoruns-hunting-persistence
* **AlwaysInstallElevated Policy:** Exploiting Windows Installer policies for SYSTEM level execution.
  * Lab Link: https://learn.secbyte.org/ctf/alwaysinstallelevated-windows-privilege-escalation
* **Weak Service Permissions:** Service ACL manipulation and binary path hijacking.
  * Lab Link: https://learn.secbyte.org/ctf/weak-service-permissions-escalation-through-misconfigured-wi

---

## Learning Path

For optimal skill progression, follow this suggested order:

1. **Linux Fundamentals & Misconfigurations**
   - Start with SUID binary enumeration and PATH abuse.
   - Progress to scheduled tasks (Cron Jobs) and advanced capabilities management.
2. **Windows Configuration & Service Abuse**
   - Begin with weak service permissions and AlwaysInstallElevated policy checks.
   - Analyze Registry autoruns for persistence hunting.
3. **Advanced Windows Process & Token Exploitation**
   - Study UAC auto-elevation mechanics.
   - Practice token impersonation and named pipe abuse for token theft.

---

## How to Use the Labs

1. Select a lab link from the index above.
2. Log in or create an account on Learn SecByte to access the practice environment.
3. Follow the guided objectives to perform enumeration, exploitation, and post-exploitation analysis.
4. Analyze defensive logs and remediation strategies to solidify defensive understanding.

---

## Disclaimer

This repository is strictly intended for educational and authorized testing purposes. All concepts, techniques, and lab environments are provided to help cybersecurity students, researchers, and defensive practitioners understand vulnerability mechanics and improve system defenses. Do not perform security testing or exploitation against systems without explicit authorization.
