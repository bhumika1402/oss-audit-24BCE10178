# OSS Audit Scripts

## Overview
This repository contains a collection of Bash scripts developed as part of an Open Source Software (OSS) lab assignment. The scripts perform system information reporting and log file analysis using basic shell scripting concepts.

## Author
Name: Bhumika Gupta  
Roll No: 24BCE10178  

## Files Included
- script.sh      : System Identity Report
- script2.sh     : (Add description)
- script3.sh     : (Add description)
- script4.sh     : Log File Analyzer
- script5.sh     : (Add description)

## Requirements
- Linux / Unix OR Git Bash / WSL
- Bash shell

## How to Run

1. Clone the repository:
git clone https://github.com/bhumika1402/oss-audit-24BCE10178.git
cd oss-audit-24BCE10178

2. Give execution permission:
chmod +x script.sh
chmod +x script4.sh

3. Run scripts:

System Identity Script:
./script.sh

Log Analyzer Script:
./script4.sh <filename> [keyword]

Example:
./script4.sh log.txt
./script4.sh log.txt warning

## Sample Input (for script4)
echo "Error occurred" > log.txt
echo "All good" >> log.txt
echo "Another error happened" >> log.txt
echo "warning message" >> log.txt

## Sample Output
Keyword 'error' found 2 times in log.txt
Last 5 matching lines:
Error occurred
Another error happened

## Notes
- script4.sh requires a filename argument
- Default keyword is "error"
- Ensure the input file exists before running
- Some commands may not work fully in Git Bash

## License
This project is for educational purposes only.
