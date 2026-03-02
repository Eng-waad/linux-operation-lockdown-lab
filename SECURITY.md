# Security Policy – TechNova Lab

## What Went Wrong
- Shared admin password
- No individual accountability
- Files had 777 permissions
- No audit trail

## What Was Fixed
- Applied 750 to directories
- Applied 640 to config files
- Applied 600 to sensitive files
- Used sudo for controlled privilege escalation

## Security Principles Applied
- Least Privilege
- Individual Access Control
- Permission Hardening
- Auditability via logs

## Future Recommendations
- Never share credentials
- Review permissions before deployment
- Enforce IAM-style access model
