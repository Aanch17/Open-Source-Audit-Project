# Open Source Audit Project

## Student Details

**Name:** Aanchal Rath
**Registration Number:** YOUR_REG_NO
**Course:** Open Source Software (NGMC)
**Software Chosen:** Python

---

##  Project Overview

This project is a structured audit of the open-source software Python. It includes an analysis of its origin, licensing, ethical considerations, Linux implementation, ecosystem, and comparison with proprietary software.

Additionally, five shell scripts have been developed and executed on a Linux environment (WSL Ubuntu) to demonstrate practical understanding of Linux commands and automation.

---

##  Linux Environment

* Platform: Windows Subsystem for Linux (WSL)
* Distribution: Ubuntu
* Kernel Version: (auto-detected in script)

---

## Project Structure

```
oss-audit/
│
├── script1.sh
├── script2.sh
├── script3.sh
├── script4.sh
├── script5.sh
├── README.md
```

---

##  Scripts Description

### Script 1 — System Identity Report

Displays system information such as kernel version, user, uptime, Linux distribution, and date/time using shell commands and variables.

### Script 2 — FOSS Package Inspector

Checks whether Python is installed, displays package details, and provides a short description using conditional statements and case structure.

### Script 3 — Disk and Permission Auditor

Analyzes important system directories and displays their size, permissions, and ownership using loops and system commands.

### Script 4 — Log File Analyzer

Reads a log file, counts occurrences of a keyword (default: "error"), and displays the last matching entries.

### Script 5 — Open Source Manifesto Generator

Takes user input and generates a personalized open-source philosophy statement, saving it to a text file.

---

## How to Run the Scripts

1. Open terminal in the project directory:

```
cd oss-audit
```

2. Make scripts executable:

```
chmod +x script1.sh script2.sh script3.sh script4.sh script5.sh
```

3. Run scripts:

```
./script1.sh
./script2.sh
./script3.sh
./script4.sh /var/log/syslog
./script5.sh
```

---

## Requirements

* Linux Environment (Ubuntu via WSL)
* Basic terminal knowledge
* Python 3 installed

---

## Notes

* All scripts are tested on Ubuntu (WSL).
* Each script includes comments for better understanding.
* Screenshots and explanations are provided in the project report.

---

## Conclusion

This project demonstrates both theoretical understanding and practical implementation of open-source concepts using Python and Linux tools. It highlights the importance of open-source software in modern computing and showcases basic shell scripting skills.

---
