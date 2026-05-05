# Introduction to Linux

## What is Linux?

Linux is an open-source, Unix-like operating system kernel that acts as a bridge between hardware and software. It is widely used in servers, cloud computing, and DevOps environments because of its stability, security, and flexibility.

Linux is not a complete operating system by itself. When combined with system tools and applications, it forms a full operating system known as a Linux distribution.

---

## What is an Operating System?

An Operating System (OS) is system software that manages computer hardware and provides services for applications.

### Key Functions:
- Managing processes (running programs)  
- Managing memory  
- Handling files and storage  
- Controlling hardware devices  
- Providing security and user access  

Examples include Windows, macOS, and Linux.

---

## History of Linux

Linux was created in 1991 by Linus Torvalds as a personal project. It was inspired by Unix, a powerful multi-user operating system.

Because Linux was released as open-source, developers around the world contributed to its improvement. Today, Linux powers servers, cloud platforms, and many modern technologies.

---

## Open Source Concept

Linux is open-source, meaning its source code is freely available for anyone to view, modify, and share.

### Advantages:
- Free to use  
- Highly customizable  
- Supported by a global community  
- Transparent and secure  

### Open Source vs Proprietary:

| Feature        | Open Source (Linux) | Proprietary Software |
|---------------|-------------------|----------------------|
| Source Code   | Available         | Not available        |
| Cost          | Free              | Usually paid         |
| Customization | High              | Limited              |
| Support       | Community-driven  | Company-based        |

---

## Linux Architecture

Linux follows a simple layered structure:

### 1. Kernel  
The core component that interacts directly with hardware.

### 2. Shell  
The interface that allows users to interact with the system.

### 3. System Libraries  
Provide essential functions for applications.

### 4. User Space  
Where user applications and programs run.

<img width="1740" height="589" alt="linux_architecture" src="https://github.com/user-attachments/assets/2ce46399-50ac-46ae-9280-685e7888d2e3" />

---

## Kernel Basics

The kernel is the most important part of Linux. It manages system resources and communicates with hardware.

### Main Responsibilities:
- Process management  
- Memory management  
- Device management  
- Handling system calls  

### Types of Kernels:
- Monolithic Kernel (used in Linux)  
- Microkernel  

---

## Shell and Terminal

The shell is a command-line interface that allows users to interact with the system using commands.

### Common Shells:
- Bash  
- Zsh  
- Sh  

### CLI vs GUI:
- CLI (Command Line Interface): Fast, powerful, widely used in DevOps  
- GUI (Graphical User Interface): Easier for beginners  

---

## Linux File System Overview

Linux uses a hierarchical file system that starts from the root directory `/`. All files and directories are organized under this root.

### Standard Linux Directories

Below are the commonly used directories in Linux:

- `/` → Root directory (starting point of the file system)
- `/bin` → Essential user command binaries
- `/sbin` → System binaries (used by administrators)
- `/boot` → Boot loader files (kernel, init files)
- `/dev` → Device files (hardware representation)
- `/etc` → System configuration files
- `/home` → User home directories
- `/lib` → Essential shared libraries
- `/lib64` → 64-bit libraries
- `/media` → Mount point for removable media (USB, CD)
- `/mnt` → Temporary mount point
- `/opt` → Optional software and packages
- `/proc` → Virtual file system (process and system info)
- `/root` → Home directory of root user
- `/run` → Runtime system information
- `/srv` → Data for services (e.g., web server)
- `/sys` → System and hardware information
- `/tmp` → Temporary files
- `/usr` → User programs and applications
- `/var` → Variable data (logs, cache, spool files)

---

## Users and Permissions

Linux is a multi-user system with built-in security.
## 👤 Types of Users: Root, Local, and Sudo User

Understanding different user roles in Linux is important for system security and access control.

---

### Root User (Superuser)

The **root user** is the highest-level user in Linux with complete control over the system.

#### Key Characteristics:
- User ID (UID) = 0  
- Full access to all files and commands  
- Can modify system configurations  
- Can create, delete, and manage all users  

#### Important:
Using the root user directly is risky because a single incorrect command can affect the entire system.

---

### Local (Regular) User

A **local user** is a standard user created for daily tasks.

#### Key Characteristics:
- Limited permissions  
- Cannot modify critical system files  
- Has a personal home directory (e.g., `/home/username`)  
- Safer for regular usage  

#### Purpose:
Local users help maintain system security by restricting access to sensitive parts of the system.

---

### Sudo User (Privileged User)

A **sudo user** is a regular user who is allowed to perform administrative tasks using the `sudo` command.

#### Key Characteristics:
- Does not have full-time root access  
- Can execute root-level commands using `sudo`  
- Requires password authentication  
- Actions are logged for security  

### Permission Types:
- Read (r)  
- Write (w)  
- Execute (x)  

Permissions help control access and protect the system.

---

## Linux Distributions (Distros)

A Linux distribution is a complete operating system built using the Linux kernel along with additional tools and software.

### Popular Distributions:
- Ubuntu  
- Debian  
- CentOS  
- Fedora  

Each distribution is designed for different use cases such as development, servers, or personal use.

---

## Why Linux for DevOps and Cloud?

Linux is widely used in DevOps and cloud environments because:

- It is stable and reliable  
- It provides strong security  
- It supports automation and scripting  
- Most servers and cloud platforms run on Linux  
- It integrates well with DevOps tools  

---

## Real-World Applications of Linux

Linux is used in many areas, including:

- Web servers  
- Cloud infrastructure  
- Cybersecurity systems  
- Mobile devices (Android)  
- Embedded systems  

---

## Summary

Linux is a powerful and flexible operating system that plays a key role in modern computing. A strong understanding of Linux fundamentals is essential for careers in DevOps, cloud computing, and system administration.

---

## What’s Next?

➡️ Next Topic: **History and Open Source (Detailed Study)**
