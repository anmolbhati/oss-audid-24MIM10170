# The Open Source Audit: Capstone Project

**Student Name:**    Anmol Bhati
**Registration Number:**   24MIM10170
**Course:**    Open Source Software (OSS NGMC)
**Chosen Software:**     VLC Media Player

## Project Overview
This repository contains five shell scripts written as part of the Open Source Audit capstone project. These scripts demonstrate practical Linux command-line skills, automation, and an understanding of open-source philosophies. 

## Dependencies
To run these scripts successfully, your Linux environment requires:
* A standard Bash shell (`/bin/bash`)
* Standard core utilities (`grep`, `awk`, `cut`, `df`, `ls`)
* `dpkg` (Debian/Ubuntu package manager) for Script 2 to verify the software installation.

## Script Descriptions & Execution Instructions

Before running any script, you must make them executable. Run this command in your terminal first:
`chmod +x *.sh`

### Script 1: System Identity Report
*  **Description:** Acts as a welcome screen, pulling system details like the Linux kernel version, current logged-in user, and system uptime. 
* **How to run:** `./script1.sh`

### Script 2: FOSS Package   Inspector
* **Description:* * Checks if  VLC Media Player is installed on the system using `dpkg`. It outputs the version details and prints a custom philosophical note about  VLC's origins.
* **How to run:** `./script2.sh`

### Script 3: Disk and Permission Auditor
* **Description:** Loops through critical system directories (like `/etc` and `/var/log`) to report their disk usage size, ownership, and read/write/ execu te permissions.
* **How to run:** `./script3.sh`

### Script 4: Log File Analyzer
* **Description:** Reads a specified log   file line-by-line to count the occurrences of a specific keyword (defaulting to "install" or "error") to simulate system auditing.
* **How to run:** `./script4.sh /var/log/dpkg.log` (or provide any other valid log file path).

### Script 5: The Open Source Manifesto Generator
* **Description:** An interactive script that asks the user three questions about their digital tools and values, then generates a personalissed "manifesto" saved to a text file.
* **How to run:** `./script5.sh`  
