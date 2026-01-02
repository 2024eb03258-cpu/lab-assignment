# lab-assignment

## Student Information
- **Name**: Nida Fatima
- **Course**: BSC Computer Science
- **Subject**: Command Line Interfaces and Scripting
- **University**: BITS Pilani 
- **Submission Date**: January 2, 2026
- **Github Repository**: https://github.com/2024eb03258-cpu/lab-assignment.git

## Assignment Overview
This repository contains complete solutions for the Linux Systems Lab Assignment, consisting of 4 questions (40 total tasks). All work was performed within my user account without making any system configuration changes

## Questions Completed
1. Question 1: User Management(10 tasks)
2. Question 2: Process Management(10 tasks)
3. Question 3: System Monitoring(10 tasks)
4. Question 4: File Operations(10 tasks)
**Total:** 40 tasks completed

## Repository Structure

### Files in This Folder:
1. **`commands_outputs.txt`** - Complete commands with outputs and explanations for all 10 tasks.
2. **`explanation.md`** - Detailed conceptual explanations and analysis of each task.
3. **`screenshots/`** - Directory containing execution screenshots (10 PNG files).

### Screenshot Features:
- Clear terminal output visibility
- Timestamp and username context
- Command and output pairing

### Platform Details:
- **Platform:** GitHub Codespaces (Ubuntu-based container)
- **Shell:** bash (/bin/bash)
- **Kernel:** 6.8.0-1030-azure
- **Distribution:** Ubuntu 22.04.3 LTS
- **Default User:** codespace
- **Constraints:** No system configuration changes made

## Question Summaries

### Question 1: Environment Verification
**Objective:** Verify basic Linux environment and user workspace.

### Key Tasks:
1. User identity verification (`whoami`, `groups`)
2. Workspace validation (`pwd`, `ls -la`)
3. File creation and integrity check
4. Manual page exploration (`man mkdir`)
5. Home directory inspection
6. Log file analysis (`grep`)
7. System information (`uname`)
8. Network connectivity testing (using `curl` instead of `ping`)
9. System health monitoring (`uptime`)

**Files Created:** `user_info.txt`, `log.txt`

# Note:
- Used `curl` instead of `ping` for network testing (ICMP blocked in Codespaces).


## Question 2: File and Directory Management
**Objective:** Demonstrate file system organization skills.

### Key Tasks:
1. Project workspace setup (`mkdir documents`)
2. File creation (`touch plan.txt`)
3. Content addition (project plan text)
4. File metadata verification (`ls -l`)
5. File duplication (`cp`)
6. Directory renaming (`mv`)
7. Archival structure (`mkdir archive`)
8. File organization (`mv` to archive)
9. Recursive listing (`find`)
10. Path verification (`realpath`)

**Files Created:** `plan.txt`, `plan_copy.txt`
**Directories Created:** `project_documents/`, `project_documents/archive/`

### Skills used:
- Directory structure creation and management.
- File operations (create, copy, move, rename).
- Path navigation and verification.
- File organization best practices.

## Question 3: Links and Disk Usage
**Objective:** Understand Linux file linking and storage analysis.

### Key Tasks:
1. Hard link creation (`ln`)
2. Symbolic link creation (`ln -s`)
3. Inode verification (`ls -i`)
4. Inode analysis (understanding link types).
5. File metadata inspection (`stat`)
6. Disk usage check (`du -sh`)
7. File size overview (`ls -lh`)
8. Link deletion test (`rm` symbolic link)
9. Disk utility demonstration (`du`, `df`)

**Files Created:** `sample_data.txt`, `sample_hard.txt`, `sample_soft.txt`

### Concepts Understood:
- Difference between hard links and symbolic links.
- Inode sharing and file system concepts.
- Disk usage analysis and monitoring.
- File system hierarchy and space management.

## Question 4: Process and System Monitoring
**Objective:** Monitor system resources and manage processes.

### Key Tasks:
1. System uptime verification (`uptime`)
2. User process listing (`ps -u`)
3. CPU usage analysis (`ps --sort=-%cpu`)
4. Background process execution (`sleep &`, `jobs`)
5. Process priority management (`renice`)
6. Memory usage monitoring (`free -h`)
7. Disk space inspection (`df -h`)
8. Shell identification (`echo $SHELL`)
9. Output redirection (`>` to `system_report.txt`)
10. Disk usage visualization (`du -h | sort -hr`)

**Files Created:** `system_report.txt`.

---

### System Administration Skills:
- Process monitoring and management.
- System resource analysis (CPU, memory, disk).
- Background job control.
- Priority scheduling with nice values.
- System report generation.

---

## Key Learnings
1. **Environment Awareness:** Understanding differences between physical systems and containers.
2. **Tool Proficiency:** Mastering essential Linux commands for system administration.
3. **Problem Solving:** Adapting to constraints (e.g., using `curl` when `ping` is unavailable).
4. **Documentation:** Clear explanation of commands and their outputs.
5. **Practical Application:** Real-world system administration scenarios.

---
