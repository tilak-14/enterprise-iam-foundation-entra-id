# Enterprise IAM Foundation in Microsoft Entra ID

This project demonstrates the implementation of enterprise identity and access management controls using Microsoft Entra ID.

The implementation includes identity lifecycle management, Conditional Access, RBAC, Dynamic Groups, Self-Service Password Reset (SSPR), and break-glass administrative access following Zero Trust principles.

## What I built:
- 16 users in 4 departments
- Security groups + dynamic groups
- MFA for all users
- SSPR enabled
- Location-based Conditional Access (India only)
- Break-glass accounts with monitoring
- Real-time alerting via Power Automate

## Tech used:
- Microsoft Entra ID
- Conditional Access
- PowerShell + Microsoft Graph
- Power Automate

## Outcome:
- Validated all 10 controls with sign-in & audit logs
- Wrote a security verification report

## 📁 Repository Structure

- `/scripts/` — PowerShell automation scripts
  - `01_BulkCreateUsers.ps1` — Create 16 users
  - `02_CreateGroups.ps1` — Create security groups
  - `03_CreateDynamicGroups.ps1` — Create dynamic groups
  - `04_CreateBreakGlass.ps1` — Emergency admin accounts
  - `05_AuditScript.ps1` — Audit report generator
  - `06_RunTestScenarios.ps1` — Day 9 automated tests
- `/scripts/data/` — CSV files for bulk operations
- `notes.txt` — Project design notes
- `README.md` — This file

## 👤 About Me

**Tilak Kalas** — IAM Engineer, Bengaluru  
Currently learning advanced IAM through hands-on labs in Microsoft Entra ID.

🔗 LinkedIn: https://www.linkedin.com/in/tilak-kalas-66334218a/
🐙 GitHub: https://github.com/tilak-14
