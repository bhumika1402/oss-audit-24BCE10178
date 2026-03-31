# OSS Audit — Capstone Project

Student Name: Bhumika Gupta  
Registration Number: 24BCE10178  
Course: Open Source Software (OSS NGMC)  
University: VIT Bhopal University  
Chosen Software: Python  

---

## About This Project
This repository contains a set of five Bash scripts developed as part of the Open Source Software (OSS) capstone project. The aim of this project is to explore open-source concepts through practical scripting tasks such as system inspection, package checking, permission auditing, log analysis, and generating open-source philosophy statements.

The project demonstrates the use of Linux commands, shell scripting techniques, and automation to analyze and interact with system-level components.

---

## Repository Structure
oss-audit-24BCE10178/  
├── README.md  
├── script.sh  
├── script2.sh  
├── script3.sh  
├── script4.sh  
└── script5.sh  

---

## Scripts

### Script 1 — script.sh (System Identity Report)
This script displays basic system information similar to a system report. It includes details such as the kernel version, logged-in user, system uptime, current date, and Linux distribution.

Concepts used:
- Variables  
- Command substitution `$()`  
- System commands (`uname`, `whoami`, `date`)  
- Reading OS information  

Run:
chmod +x script.sh
./script.sh


---

### Script 2 — script2.sh (Package Inspector)
This script checks whether a particular software (Python) is installed on the system. It also displays version information and provides additional details using conditional statements.

Concepts used:
- `if-else` conditions  
- Package checking  
- Command pipelines  
- Functions (if implemented)  

Run:
chmod +x script2.sh
./script2.sh


---

### Script 3 — script3.sh (Disk & Permission Auditor)
This script analyzes important directories and displays their permissions, ownership, and disk usage. It helps in understanding file system security and storage usage.

Concepts used:
- Arrays  
- Loops (`for`)  
- File permission commands (`ls -ld`)  
- Disk usage (`du`)  
- Text processing  

Run:
chmod +x script3.sh
./script3.sh


---

### Script 4 — script4.sh (Log File Analyzer)
This script reads a log file, counts the number of occurrences of a specific keyword, and displays the last 5 matching lines. The keyword can be passed as a command-line argument (default is "error").

Concepts used:
- Command-line arguments (`$1`, `$2`)  
- Default values (`${2:-error}`)  
- `while read` loop  
- `grep` and `tail`  
- Counters  

Run:
chmod +x script4.sh
./script4.sh <filename> [keyword]


---

### Script 5 — script5.sh (Manifesto Generator)
This script interactively takes input from the user and generates a personalized open-source philosophy statement. The output is saved to a text file.

Concepts used:
- User input (`read`)  
- String handling  
- File writing (`>`, `>>`)  
- Variables  

Run:
chmod +x script5.sh
./script5.sh


---

## Dependencies
These scripts require a basic Linux or Unix environment. They can also run on Git Bash or WSL with limited functionality.

Required tools:
- Bash shell  
- Core utilities (`grep`, `awk`, `cut`, `ls`, `du`, `tail`)  
- System commands (`uname`, `whoami`, `date`)  

---

## How to Run (Quick Start)
git clone https://github.com/bhumika1402/oss-audit-24BCE10178.git

cd oss-audit-24BCE10178

chmod +x *.sh

./script.sh
./script2.sh
./script3.sh
./script4.sh log.txt error
./script5.sh


---

## Notes
- Script 4 requires a valid input file, otherwise it will display an error  
- Some Linux-specific commands may not work fully in Git Bash  
- Ensure proper file permissions before execution  

---

## Conclusion
This project provides hands-on experience with Bash scripting and demonstrates how open-source tools can be used to automate system-level tasks efficiently.
