# oss-audit-24MEI1012

Open Source Software Audit Project

## Project Overview

This repository presents my Open Source Software audit project completed as part of the Open Source Software course at VIT Bhopal. The goal of this project is to study how open-source software functions within a Linux environment and to understand the philosophy, ecosystem, and technical structure behind commonly used FOSS tools.

For this audit, I chose Python as the primary open-source software. Python is among the most widely used programming languages globally and is recognized for its readability, simplicity, and strong support from the open-source community.

Through this project, I explored Python’s presence in a Linux system and developed a series of shell scripts to analyze system information, software installation, file permissions, log files, and open-source philosophy.

## Selected Open Source Software

Software Name: Python
Category: Programming Language
License: Python Software Foundation License (Open Source)

Python was developed by Guido van Rossum and was first released in 1991. It was created with a focus on code readability and developer efficiency. Over time, Python has become a key tool in areas such as:

1. Software development
2. Data science
3. Artificial intelligence
4. Web development
5. Automation and scripting

Since Python is open-source, developers worldwide can contribute to its growth and enhance its ecosystem.

## Project Objectives

1. The primary objectives of this project were:
2. To understand the philosophy of open-source software.
3. To analyze how an open-source tool exists and functions within a Linux environment.
4. To gain practical experience with Linux shell scripting.
5. To examine system information, packages, logs, and directories using automation scripts.
6. To document observations and understand how open-source ecosystems operate.

## Repository Structure

This repository includes multiple shell scripts that carry out different auditing and analysis tasks.

1. README.md
2. script1_system_identity.sh
3. script2_package_inspector.sh
4. script3_disk_auditor.sh
5. script4_log_analyzer.sh
6. script5_manifesto_generator.sh

## Script Descriptions

### Script 1 – System Identity Report

This script collects fundamental details about the Linux system and presents them in a structured format.

It gathers information such as:

1. Current user
2. Linux distribution
3. Kernel version
4. System uptime
5. Current date and time

This script shows how basic shell commands can be combined to produce a quick system overview.

### Script 2 – FOSS Package Inspector

The second script verifies whether Python is installed on the system.

It performs tasks including:

1. Detecting the Python installation
2. Displaying the installed version
3. Printing a brief description of Python

This confirms the availability of the selected open-source software in the Linux environment.

### Script 3 – Disk and Permission Auditor

This script examines several key Linux directories and reports details such as:

1. Directory permissions
2. Owner and group
3. Directory size

The directories analyzed include:
/etc
/var/log
/home
/usr/bin
/tmp

### Script 4 – Log File Analyzer

The log analyzer script reviews Linux log files and searches for specific keywords like "error".

The script:

1. Reads a log file line by line
2. Counts keyword occurrences
3. Displays the most recent matching log entries

This illustrates basic log monitoring methods used in system administration.

### Script 5 – Open Source Manifesto Generator

The final script is interactive and generates a short open-source philosophy statement.

It asks the user three questions:

1. An open-source tool they use regularly
2. What “freedom” means to them
3. Something they would build for the community

Based on the responses, the script creates a brief Open Source Manifesto and saves it as a text file.

This script emphasizes the collaborative and philosophical side of open-source software.

## How to Run the Scripts

First, make the scripts executable:
`chmod +x *.sh`

Then run any script using:
`./script_name.sh`

## Technologies Used

1. Linux (Ubuntu / WSL)
2. Bash Shell Scripting
3. Python (audited software)
4. Git & GitHub for version control

## Key Learnings

Working on this project helped me understand several important concepts, including:

1. The structure of Linux file systems
2. How open-source software is installed and managed
3. The significance of automation using shell scripting
4. Basic system auditing techniques
5. The collaborative nature of open-source communities

It also enhanced my familiarity with GitHub and version control, which are essential tools in modern software development.

## Conclusion

Open-source software plays a crucial role in today’s technological landscape. Projects like Python show how collaborative development can produce powerful tools used across various industries.

This audit project provided hands-on experience with Linux systems, scripting, and open-source principles. It also highlighted the transparency and flexibility that make open-source software highly valuable.
