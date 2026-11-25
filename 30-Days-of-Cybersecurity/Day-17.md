# Day 17/30 — TryHackMe: Linux Fundamentals Part 1

**Date:** 25 November 2026  
**Academy:** TS Academy  
**Learning Platform:** TryHackMe  
**Room:** Linux Fundamentals Part 1  
**Topic:** Linux Terminal, File System Navigation and Basic Commands

## Overview

Today, I continued my cybersecurity learning journey by exploring the Linux Fundamentals Part 1 room on TryHackMe.

This activity built on my previous TS Academy lesson about Kali Linux and basic Linux commands.

The room introduced the Linux terminal, essential commands, file system navigation and basic command-line operators.

## 1. Understanding the Linux Terminal

The Linux terminal provides a command-line interface (CLI) that allows users to interact with the operating system by typing instructions.

Unlike a graphical user interface (GUI), where users interact mainly through menus and icons, the terminal allows tasks to be performed using commands.

This is especially useful in cybersecurity, where professionals frequently interact with servers and security tools through command-line interfaces.

## 2. Basic Linux Commands

The room introduced several commands and their functions.

| Command | Function |
|---|---|
| `whoami` | Displays the currently logged-in username |
| `pwd` | Shows the current working directory |
| `ls` | Lists files and directories |
| `cd` | Changes the current directory |
| `cat` | Displays file contents |
| `echo` | Prints text or variable values to the terminal |

### Example Commands

```bash
whoami
pwd
ls
cd Documents
cat notes.txt
echo "Hello Linux"
```

These examples demonstrate how Linux commands can be used to identify users, navigate directories and interact with files.

## 3. Navigating the Linux File System

I explored how Linux organises files and directories in a hierarchical structure.

The `pwd` command identifies the current directory, while `ls` displays its contents.

The `cd` command allows users to move between directories.

Understanding file system navigation is important because cybersecurity professionals often need to locate configuration files, investigate system activity and examine logs.

## 4. Command Operators and Output Redirection

The room also introduced operators used to control how commands behave.

| Operator | Purpose |
|---|---|
| `&` | Runs a command in the background |
| `&&` | Runs the next command if the previous one succeeds |
| `>` | Redirects output to a file, replacing its contents |
| `>>` | Appends output to an existing file |

### Example

```bash
echo "Cybersecurity Learning" > notes.txt
echo "Day 17 - Linux Fundamentals" >> notes.txt
cat notes.txt
```

The first command creates or overwrites `notes.txt` with text. The second appends another line, while the third displays the file contents.

These examples demonstrate how output redirection can be used to create and update text files.

## 5. Connection to Cybersecurity

Understanding Linux commands is important because many cybersecurity tools and servers operate in Linux environments.

The commands introduced in this room provide foundational skills for:

- Navigating system directories.
- Identifying the current user.
- Viewing files and their contents.
- Interacting with the operating system through a terminal.
- Understanding basic command execution and output redirection.

## My Key Takeaway

The most important lesson for me was understanding that Linux commands become easier to learn when I focus on their purpose rather than simply memorising them.

Building confidence with basic commands is an important step towards understanding more advanced Linux and cybersecurity operations.

## Next Steps

- Continue practising basic Linux commands.
- Explore more Linux file management operations.
- Improve my understanding of command-line operators.
- Progress to Linux Fundamentals Part 2.

## Learning Resource

[TryHackMe — Linux Fundamentals Part 1](https://tryhackme.com/room/linuxfundamentalspart1)

---

**Day 17/30 — Linux Fundamentals Learning Documentation**
