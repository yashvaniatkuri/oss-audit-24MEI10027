
# The Open Source Audit — Git (24MEI10027)

## Student Information
**Student Name:** Atkuri Yashvani  
**Registration Number:** 24MEI10027  
**Course:** Open Source Software (OSS NGMC)  
**Project Type:** Open Source Audit Capstone Project  
**Chosen Software:** Git  

---

## About the Project

This project is an academic audit of the open source software **Git**. The purpose of this project is to understand the philosophy, licensing model, Linux integration, ecosystem, and real-world usage of Git.

Git is a distributed version control system used by developers worldwide to track changes in source code. It helps multiple developers collaborate on the same project efficiently.

In addition to the theoretical study, five shell scripts have been created to demonstrate Linux command-line skills and automation concepts.

This repository contains all required shell scripts and documentation needed for submission.

---

## About Git

Git is one of the most widely used open-source tools in software development. It was created in 2005 by Linus Torvalds to support the development of the Linux kernel.

Git allows developers to:
- Track changes in code
- Work collaboratively with teams
- Maintain version history
- Restore previous versions of files
- Work in distributed environments

Git follows the open-source philosophy, allowing anyone to use, modify, and distribute the software freely under the GNU General Public License version 2 (GPLv2).

---
## Repository Structure
<img width="554" height="259" alt="image" src="https://github.com/user-attachments/assets/f3d3670c-ae21-4e43-b781-abcee0199558" />


---

## 🛠️ Setup & Configuration

Follow these steps to set up the environment and run the project from your terminal.

---

### 1. Environment Setup

The project is designed for **Linux environments** such as:

- Ubuntu
- Debian
- CentOS
- RHEL
- Fedora

If you are using **macOS**, the scripts will still run, but some system-level checks (like `/etc/os-release`) may show limited information.

---

### 2. Dependency Installation

Make sure the following tools are installed:

- bash
- git
- coreutils (standard Linux utilities)

---

#### Ubuntu / Debian

```bash
sudo apt update && sudo apt install git -y
```

#### RHEL / CentOS
```bash
sudo yum install git -y
```

#### Fedora
```bash
sudo dnf install git -y
```

### 3. Verify Installation
```bash
git --version
bash --version
```


## Shell Scripts Overview

### Script 1: System Identity Report

This script displays basic information about the Linux system.

It prints:
- Linux distribution name
- Kernel version
- Current logged-in user
- Home directory
- System uptime
- Current date and time
- Open source license message

Concepts used:
- Variables
- echo command
- command substitution
- formatting output


---

### Script 2: FOSS Package Inspector

This script checks whether Git is installed on the system and displays package information.

It prints:
- Whether Git is installed
- Git version
- License information
- Short description using case statement

Concepts used:
- if-else statement
- case statement
- package checking
- grep command


---

### Script 3: Disk and Permission Auditor

This script checks disk usage and permissions of important Linux directories.

Directories checked:
- /etc
- /var/log
- /home
- /usr/bin
- /tmp

It prints:
- directory size
- owner
- permissions

Concepts used:
- for loop
- arrays
- ls command
- du command
- awk command


---

### Script 4: Log File Analyzer

This script reads a log file and counts how many times a keyword appears.

Example keywords:
- error
- warning
- failed

Concepts used:
- while loop
- if condition
- variables
- command line arguments
- grep command


---

### Script 5: Open Source Manifesto Generator

This script creates a personalized open-source philosophy statement based on user input.

The script:
- asks user 3 questions
- generates a short paragraph
- saves output in a text file

Concepts used:
- read command
- variables
- file writing
- date command


---

## Requirements

The scripts require a Linux environment.

Required tools:
- Linux OS
- Bash shell
- Git installed
- basic Linux commands

Commands used in scripts:
- uname
- whoami
- uptime
- grep
- awk
- du
- ls
- date


---
## Run All Scripts (Single Command)

```bash
chmod +x *.sh && \
./script1.sh && \
./script2.sh && \
./script3.sh && \
./script4.sh /var/log/syslog error && \
./script5.sh
```


---

## Learning Outcomes

After completing this project, the following concepts are understood:

- meaning of open source software
- Git software usage
- Linux command line basics
- shell scripting fundamentals
- automation concepts
- open source licensing
- Git importance in software development

---

## Conclusion

Git plays an important role in modern software development. It allows teams to collaborate efficiently and maintain project history properly.

Through this project, both theoretical knowledge and practical Linux skills are developed.

The shell scripts demonstrate automation techniques and help understand how open-source tools work in real systems.

---


Open Source Software Course Project






