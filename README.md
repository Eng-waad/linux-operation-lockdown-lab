# Linux Operation Lockdown – Security & Permissions Lab

## Scenario

This lab simulates a real-world security incident at a fictional company (TechNova Corp), where a shared admin account was used to access and destroy the staging environment.

Due to poor access control and 777 permissions, the team could not identify who executed the destructive command.

My task was to:

- Rebuild the entire staging environment
- Investigate logs to identify the breach
- Fix configuration errors
- Apply secure Linux file permissions
- Enforce the Principle of Least Privilege

---

## Environment

- OS: Ubuntu 24.04
- Platform: VMware Workstation
- User: waad
- Access Model: sudo-based privilege escalation

---

## Skills Demonstrated

### 1️⃣ Linux System Assessment
- `whoami`,# Linu# Linux Oper# Linux Op- Environment variables (`export`)
- Shell identification
- Command history analysis

### 2️⃣ Filesystem Navigation
- Absolute & relative paths
- Core Linux directories:a shared# Linux Oper# Linux O# Linux O- Disk & memory inspection (`df -h`, `free -h`)
- File discovery usingo

This 
### 3️⃣ Project Reconstruction
- Built directory structure usingenario

This- Created application files withurity & P- Generated simulated log entries
- Created backups using##  Sce- Created symbolic links usingecurity &
### 4️⃣ Log Analysis & Incident Investigation
- Log filtering usingrio

Thi- Pattern extraction with regex
- Pipelines:  
 ons Lab

##  Scenario

This lab si- Severity counting (INFO, WARN, ERROR, FATAL)
- Generated incident report

### 5️⃣ Configuration Management
- Edited configs usingtional c- Created deployment script usingrity & - Fixed configuration typo (APP_PROT → APP_PORT)
- Handled script execution errors (Permission denied)

### 6️⃣ Linux Permissions & Security Hardening
- Interpreted permission strings (`-rwxr-xr--`)
- Applied secure permission patterns:
  - 750 (directories)
  - 644 (application files)
  - 640 (configs)
  - 600 (sensitive files)
- Removed insecure 777 permissions
- Usedwas to:

(symbolic and numeric modes)
- Demonstrated privilege escalation withio

This- Tested access restrictions intentionally (lockout test)

---

##  Security Improvements Implemented

- Eliminated shared admin model
- Enforced sudo-based access control
- Removed world-writable permissions
- Applied least privilege model
- Ensured sensitive files are owner-restricted
- Verified audit trail viaidentify who executed
---

## 📂 Project Structure
technova-staging/
├── app/
├── config/
├── logs/
├── scripts/
├── backups/
├── incident-report.txt
└── SECURITY.md


