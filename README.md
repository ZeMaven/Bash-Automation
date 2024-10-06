# Bash Automation

## Overview

**Bash Automation** This repository aims to simplify my repetitive tasks, enhance productivity, and ensure consistent results across different projects I'm working on -- to help streamline my day to day processes.

## Features

- **Git Workflow Automation**: Automate branch creation, merging, and repository management tasks in Git (GitHub/GitLab).
- **System Monitoring**: Monitor CPU, memory usage, and other system metrics.
- **Backup and Restore**: Automated backup and restore functionality for directories or databases.
- **API Interaction**: Bash scripts that interact with APIs to fetch data or automate cloud services.
- **File and Directory Management**: Efficiently handle file operations such as copying, moving, and cleanup tasks.

## Scripts Included

- `airthmatic.sh`: Performs basic arithmetic operations like addition, subtraction, multiplication, and division using Bash.
- `ami_backup.sh`: Automates the process of creating backups of Amazon Machine Images (AMI) in AWS for disaster recovery or snapshot management.
- `bye.sh`: A simple script to display a goodbye message and possibly perform cleanup tasks before exiting a session or script.
- `filemodified.sh`: Checks for files in a specific directory that have been modified recently and lists them.
- `filemodified1.sh`: Similar to filemodified.sh, likely with a variation in functionality, such as filtering or additional options for identifying modified files.
- `getallrepos.sh`: Fetches and lists all repositories from a remote source (like GitHub) and displays them for further automation or processing.
- `jobspull.sh`: Pulls job or task-related data from a source (possibly a CI/CD pipeline or task management system) for monitoring or reporting.
- `jump.sh`: Automates jumping between directories or environments, simplifying navigation in a multi-directory setup.
- `profile.sh`: Sets up or modifies environment profiles by configuring paths, environment variables, or system settings.
- `run_loop.sh`: Executes a loop that repeatedly runs a command or script until a certain condition is met or until manually stopped.
- `s3_file_fetcher.py`: A Python script to fetch and download files from an AWS S3 bucket, automating file retrieval from cloud storage.
- `s3export.sh`: Exports data or files to an AWS S3 bucket, enabling automated data backup or transfer to the cloud.
- `s3files_fetch.sh`: Similar to s3_file_fetcher.py, but implemented as a Bash script to fetch files from an S3 bucket.
- `ssh_agent.sh`: Manages SSH keys and agents, helping to set up or reuse SSH sessions for secure, password-less remote connections.

## Prerequisites

- **Bash** (v4.0 or higher)
- **Git** (for Git automation scripts)
- **curl** or **wget** (for API interaction scripts)
- **jq** (for processing JSON data from APIs)

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/<your-username>/bash-automation.git
   cd bash-automation
