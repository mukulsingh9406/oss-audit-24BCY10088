# Open Source Audit Project

## Student Details
- Name: Mukul Singh( 24BCY10088 )
- Course: Open Source Software
- Project Title: Open Source Audit

## Chosen Software
Git (Distributed Version Control System)

## Project Description
This project is centered on exploring Git as an open-source software tool. It provides a comprehensive examination of its history, licensing model, ecosystem, and a comparative analysis with proprietary alternatives. The project also incorporates hands-on exercises using Linux shell scripting to demonstrate practical skills with open-source tools and system operations.

The main goal of this project is to gain a deep understanding of both the theoretical concepts and practical applications of open-source software, emphasizing its significance in contemporary computing environments.

## Scripts Overview

### Script 1: System Information Reporter
This script retrieves and displays essential system details, including the kernel version, current user, system uptime, date, and the Linux distribution in use.

### Script 2: Git Status Checker
This script verifies whether Git is installed on the system and provides key information such as the installed version and a brief description of the package.

### Script 3: Disk Usage and Permissions Auditor
This script examines system directories, reporting disk usage and the permissions set for each folder, helping to monitor storage and access controls

### Script 4: Log Keyword Analyzer
This script searches through a log file for a specific keyword, counts the occurrences, and displays all matching lines for further inspection.

### Script 5: Custom Open-Source Manifesto Creator
This script allows users to generate a personalized open-source manifesto by collecting input and formatting it into a structured output.

## How to Run the Scripts

### Step 1: Make Scripts Executable
```bash
chmod +x script1.sh
chmod +x script2.sh
chmod +x script3.sh
chmod +x script4.sh
chmod +x script5.sh

Step 2: Run Scripts
./script1.sh
./script2.sh
./script3.sh
./script4.sh /var/log/syslog error
./script5.sh

Requirements:
Ubuntu (WSL) or Linux Environment
Bash Shell
Git installed

Output:
Scripts display output directly in the terminal
Script 5 generates a text file containing the manifesto

Learning Outcomes:
Understanding of open-source software concepts
Hands-on experience with Linux commands
Knowledge of shell scripting (loops, conditions, variables)
Understanding of Git and its ecosystem

Conclusion:
This project provided a comprehensive understanding of open-source software through both theoretical analysis and practical implementation. Git was studied in detail, and shell scripting skills were developed. The project highlights the importance of open-source tools in modern software development.
