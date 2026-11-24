# Day 16/30 — Introduction to Linux Commands and File Permissions

**Date:** 24 November 2026  
**Academy:** TS Academy  
**Tutor:** Favour Onoko  
**Module:** Foundations of Cybersecurity and Computing  
**Topic:** Kali Linux, Command-Line Navigation and File Permissions

## Overview

Today, I continued my cybersecurity training with TS Academy, focusing on Linux commands and basic file management.

The session introduced important commands used to navigate the Linux file system, create and manage files, and control access permissions.

As a beginner, this helped me better understand how cybersecurity professionals interact with Linux systems through the command-line interface.

## 1. Introduction to Kali Linux

Kali Linux is a Linux distribution designed for security auditing and penetration testing.

Unlike the graphical interface commonly used in Windows, Linux provides a powerful terminal that allows users to interact with the operating system by entering commands.

Understanding the terminal is an important foundation for learning system administration and cybersecurity.

## 2. Basic Linux Commands

The session introduced several commands and their functions.

| Command | Function |
|---|---|
| `whoami` | Displays the current username |
| `pwd` | Shows the current working directory |
| `ls` | Lists files and directories |
| `cd` | Changes the current directory |
| `mkdir` | Creates a new directory |
| `touch` | Creates a new empty file |
| `cat` | Displays file contents |
| `cp` | Copies files |
| `mv` | Moves or renames files |
| `rm` | Deletes files |
| `rmdir` | Removes empty directories |
| `clear` | Clears the terminal screen |

These commands form the foundation for navigating and managing files within a Linux environment.

## 3. Linux File Permissions

Another important topic covered was file permissions.

Linux uses three basic permission types:

- **Read (r = 4):** Allows users to read file contents.
- **Write (w = 2):** Allows users to modify file contents.
- **Execute (x = 1):** Allows users to execute a file.

Permissions are assigned to the file owner, group and other users.

### Example: `chmod 750`

The command:

`chmod 750 filename`

Sets the following permissions:

| Category | Permission | Numeric Value |
|---|---|---|
| Owner | Read, Write, Execute | 7 |
| Group | Read, Execute | 5 |
| Others | No permissions | 0 |

This demonstrated how Linux permissions can be used to restrict access to files.

## 4. File Ownership

I was also introduced to the `chown` command, which is used to change file ownership.

The walkthrough covered how Linux users and groups can be assigned different access rights.

This connects to the cybersecurity principle of least privilege, where users should only receive the permissions necessary to perform their tasks.

## 5. Additional Linux Commands

Other commands introduced during the session included:

| Command | Purpose |
|---|---|
| `ps aux` | Displays running processes |
| `history` | Shows previously entered commands |
| `df -h` | Displays disk space usage |
| `free -h` | Shows memory usage |
| `ping` | Tests network connectivity |
| `man` | Opens command documentation |
| `sudo apt update` | Refreshes package information |

These commands are useful for understanding system activity, troubleshooting and basic administration.

## Connection to Cybersecurity

Linux commands are important in cybersecurity because they help professionals navigate systems, manage files, inspect processes and control access to resources.

Understanding file permissions also helps prevent unauthorised access and accidental changes to sensitive information.

## My Key Takeaway

Today's learning helped me understand that the Linux terminal is not just a collection of commands. It is a way of interacting directly with the operating system.

I am beginning to understand how basic Linux skills support system management, access control and security operations.

Although I am still building confidence with the command line, understanding the purpose of these commands is an important first step.

## Next Steps

- Practise basic navigation commands in an authorised Linux environment.
- Create and organise practice files and directories.
- Explore file permissions using `ls -l` and `chmod`.
- Continue learning how Linux supports cybersecurity operations.

## Learning Resource

TS Academy — *Walkthrough on Linux Commands*, Favour Onoko.

---

**Day 16/30 — Linux Fundamentals Learning Documentation**
