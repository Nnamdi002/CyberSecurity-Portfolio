# Day 13/30 — Linux and Windows Fundamentals

**Date:** 21 November 2026  
**Academy:** TS Academy  
**Tutor:** Favour Onoko  
**Module:** Foundations of Cybersecurity and Computing  
**Topic:** Operating Systems, File Systems and Security Permissions

## Overview

Today, I attended a cybersecurity class at TS Academy focused on Linux and Windows fundamentals.

The session introduced the role of operating systems, their differences, built-in security features and how file permissions help protect information from unauthorised access.

## 1. Understanding Operating Systems

An operating system (OS) is the core software that manages a computer's hardware, applications and system resources.

I learned that an operating system also plays an important role in cybersecurity through:

- **Authentication:** Verifying a user's identity.
- **Permissions:** Controlling what users and applications can access or modify.
- **Process Isolation:** Helping prevent processes from interfering with one another.
- **System Protection:** Protecting important system files and settings from unauthorised changes.

## 2. Windows Operating System

Windows is widely used on personal computers and in business environments.

We explored several Windows security features:

| Security Feature | Purpose |
|---|---|
| User Account Control (UAC) | Requests approval before certain system-level changes. |
| Microsoft Defender | Provides built-in antivirus and malware protection. |
| Windows Firewall | Controls network traffic based on security rules. |
| Administrator Account | Provides elevated permissions for system management. |
| Standard User Account | Restricts privileged actions to reduce security risks. |

**Cybersecurity Connection:** Understanding these features is important when learning to secure Windows computers against malware, unauthorised access and unwanted system changes.

## 3. Linux Operating System

Linux is an open-source operating system widely used in servers, cloud environments and cybersecurity.

We discussed popular Linux distributions, including Ubuntu, Debian and Kali Linux.

One interesting aspect of Linux is its command-line interface, which allows users to interact with the operating system by entering commands.

## 4. Linux File System Structure

The class introduced important Linux directories and their functions.

| Directory | Purpose |
|---|---|
| `/` | Root of the Linux file system hierarchy |
| `/home` | Contains users' personal directories |
| `/etc` | Stores system configuration files |
| `/root` | Home directory of the root user |
| `/var` | Stores variable data, including logs |
| `/bin` | Contains essential command binaries |
| `/usr` | Contains programs, libraries and supporting files |
| `/tmp` | Stores temporary files |

I also learned that Linux paths use forward slashes (`/`), while Windows commonly uses backslashes (`\`).

## 5. Linux File Permissions

One of the most interesting topics for me was understanding how Linux controls access to files.

The three basic permissions are:

- **Read (r = 4):** Permission to view file contents.
- **Write (w = 2):** Permission to modify file contents.
- **Execute (x = 1):** Permission to run a file as a program.

These permissions are assigned to three categories: the **owner**, **group** and **others**.

### Example: `rwxr-xr--`

| User Category | Permissions | Numeric Value |
|---|---|---|
| Owner | Read, Write, Execute | 7 |
| Group | Read, Execute | 5 |
| Others | Read only | 4 |

The numeric representation is **754**.

**Cybersecurity Connection:** File permissions help enforce access control and reduce the risk of unauthorised users viewing or modifying sensitive information.

## 6. Windows vs Linux

| Feature | Windows | Linux |
|---|---|---|
| Interface | Primarily graphical | Command-line and graphical |
| File Paths | `C:\Users\John` | `/home/john` |
| Common Environments | Desktops and businesses | Servers, cloud and security |
| Permissions | Access Control Lists (ACLs) | Read, Write, Execute permissions |
| Customisation | Generally more restricted | Highly customisable |

Both operating systems are important in cybersecurity because organisations use different systems to support their operations.

## My Key Takeaway

Today's lesson helped me understand that protecting a computer begins with understanding how its operating system works.

I found Linux file permissions particularly interesting because they demonstrate how access can be controlled for different users.

I also gained a better appreciation of the security features built into Windows and why learning both operating systems will be useful as I progress in cybersecurity.

## Next Steps

- Practise navigating the Windows and Linux file systems.
- Begin learning basic Linux terminal commands.
- Explore how file permissions work through authorised hands-on exercises.
- Continue strengthening my understanding of operating system security.

## Learning Resource

TS Academy — *Linux and Windows Fundamentals*, taught by Favour Onoko.

---

**Day 13/30 — Learning Documentation**
