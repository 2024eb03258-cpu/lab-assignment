# lab-assignment

## Student Information
- **Name**: Nida Fatima
- **Date**: 31 Dec 2025

## Questions Completed
1. Question 1: User Management
2. Question 2: Process Management
3. Question 3: System Monitoring
4. Question 4: File Operations

## Repository Structure
Each folder contains:
- `commands_executed.txt` - All commands used
- `explanation.txt` - Step-by-step explanations
- `screenshots/` - Visual proof of execution

- ## Question 1: Environment Verification

### Key Tasks Completed:
1. User identity verification (`whoami`, `groups`)
2. Workspace validation (`pwd`, `ls -la`)
3. Environment confirmation file creation (`user_info.txt`)
4. File integrity (`wc -c`)
5. Learning tools (`man mkdir`)
6. Home directory inspection (`ls -la ~ | sort`)
7. Log investigation (`grep "admin" log.txt`)
8. System information check (`uname -r`)
9. Network connectivity test (`curl` alternative to `ping`)
10. System health awareness (`uptime`)

# Note:
- Used `curl` instead of `ping` for network testing (ICMP blocked in Codespaces)


## Question 2: File and Directory Management
### Key Tasks Completed:
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

### Skills used:
- Directory structure creation and management
- File operations (create, copy, move, rename)
- Path navigation and verification
- File organization best practices


## Question 3: Links and Disk Usage
### Key Tasks Completed:
1. File creation (`sample_data.txt`)
2. Hard link creation (`ln`)
3. Symbolic link creation (`ln -s`)
4. Inode verification (`ls -i`)
5. Inode analysis (understanding link types)
6. File metadata inspection (`stat`)
7. Disk usage check (`du -sh`)
8. File size overview (`ls -lh`)
9. Link deletion test (`rm` symbolic link)
10. Disk utility demonstration (`du`, `df`)

### Concepts Understood:
- Difference between hard links and symbolic links
- Inode sharing and file system concepts
- Disk usage analysis and monitoring
- File system hierarchy and space management


## Question 4: Process and System Monitoring
### Key Tasks Completed:
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

### System Administration Skills:
- Process monitoring and management
- System resource analysis (CPU, memory, disk)
- Background job control
- Priority scheduling with nice values
- System report generation

---

## Technical Environment Details
- **Platform:** GitHub Codespaces
- **Default Username:** codespace
- **Shell:** bash
- **Linux Distribution:** Ubuntu-based container
- **Constraints:** No system configuration changes made

---

## Key Learnings
1. **Environment Awareness:** Understanding differences between physical systems and containers
2. **Tool Proficiency:** Mastery of essential Linux commands for system administration
3. **Problem Solving:** Adapting to constraints (e.g., using `curl` when `ping` is unavailable)
4. **Documentation:** Clear explanation of commands and their outputs
5. **Practical Application:** Real-world system administration scenarios

---
