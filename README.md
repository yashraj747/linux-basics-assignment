Linux Basics – DevOps Assignment
Student Information

Name: Yashraj

Course: DevOps

Environment Used: Ubuntu (VirtualBox)

Submission Date: 23 February 2026

Project Overview

This repository contains a Linux fundamentals assignment completed as part of the DevOps course.

Linux command-line proficiency is a core skill in DevOps. This assignment demonstrates practical usage of essential Linux commands required for system administration, automation, and infrastructure management.

All commands were executed and verified in an Ubuntu environment.

DevOps-Relevant Linux Tasks Performed
1. File and Directory Management
mkdir test_dir
touch test_dir/example.txt
mv test_dir/example.txt test_dir/renamed_example.txt
echo $?

Created directories, created files, renamed files, and verified command execution.

DevOps Relevance:
File handling is essential for managing configuration files, scripts, logs, and deployments.

2. Viewing System Files
cat /etc/passwd
head -n 5 /etc/passwd
tail -n 5 /etc/passwd

Inspected system user configuration and viewed file contents efficiently.

DevOps Relevance:
Understanding system files is critical for server management and troubleshooting.

3. Searching with grep
grep "root" /etc/passwd

Searched system file for specific patterns.

DevOps Relevance:
Pattern searching is widely used in log analysis, monitoring, and debugging production systems.

4. File Compression and Extraction
zip -r test_dir.zip test_dir
unzip test_dir.zip -d unzipped_dir

Compressed directories and extracted archives.

DevOps Relevance:
Used in packaging applications, backup management, and deployment workflows.

5. Downloading Files from the Internet
wget https://google.com/robots.txt

Downloaded files via terminal.

DevOps Relevance:
Frequently used to fetch installation packages, scripts, and configuration files.

6. File Permission Management
touch secure.txt
chmod 444 secure.txt
ls -l secure.txt

Modified file permissions and verified access control.

DevOps Relevance:
Permission management is essential for securing servers and production environments.

7. Environment Variables
export MY_VAR="Hello World"
echo $MY_VAR

Created an environment variable and accessed its value.

DevOps Relevance:
Environment variables are used extensively in CI/CD pipelines, Docker containers, and application configuration.

Tools and Technologies Used

Ubuntu Linux

Bash Shell

Oracle VirtualBox

Git and GitHub
