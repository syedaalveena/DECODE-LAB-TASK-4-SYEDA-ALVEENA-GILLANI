# DECODE-LAB-TASK-4-SYEDA-ALVEENA-GILLANI
FOR INTERNSHIP TASKS 4
# Project 4: System Vulnerability Checklist

**Analyst:** Syeda Alveena Gillani
**Organization:** DecodeLabs Cybersecurity Training — Batch 2026
**Skill Badge:** Risk Assessment

---

## Project Overview

This project is a personal system security audit performed on a Windows machine.
The goal was to identify vulnerabilities, fix them, and document the findings
in a professional Vulnerability Report.

---

## What Was Done

- Checked Microsoft account for Multi-Factor Authentication (MFA)
- Verified Windows Defender and system updates
- Audited firewall status across all network profiles
- Checked BitLocker disk encryption status
- Reviewed administrator accounts for unauthorized access
- Verified the Guest account was disabled

---

## Tools Used

- Windows PowerShell
- Microsoft Account Security Portal (account.microsoft.com)
- Windows Settings (Windows Update)

---

## Commands Used

| Check | Command |
|---|---|
| Firewall | Get-NetFirewallProfile |
| Disk Encryption | Get-BitLockerVolume |
| Admin Accounts | Get-LocalGroupMember -Group "Administrators" |
| Guest Account | Get-LocalUser -Name "Guest" |
| Updates | Windows Settings > Windows Update |

---

## Key Findings

| # | Finding | Risk Level | Status |
|---|---|---|---|
| 1 | MFA was not enabled on Microsoft account | High | Fixed |
| 2 | Windows Defender update pending | Medium | Fixed |
| 3 | Firewall all profiles active | Pass | No action needed |
| 4 | BitLocker encryption ON for all drives | Pass | No action needed |
| 5 | No unauthorized admin accounts found | Pass | No action needed |
| 6 | Guest account disabled | Pass | No action needed |

---

## Deliverables

- Vulnerability_Report_Syeda_Alveena_Gillani.docx
- screenshots/ (6 audit screenshots)

---

## Skills Demonstrated

- Vulnerability assessment
- Risk scoring using CVSS scale
- Remediation and hardening
- Security audit documentation
