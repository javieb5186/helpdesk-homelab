# IT Help Desk & Hybrid Identity Homelab

## Overview

This repository documents a hands-on IT help desk and hybrid identity lab environment built to practice real-world support workflows using Active Directory Domain Services (AD DS), Microsoft 365, Microsoft Entra ID, Spiceworks, and remote support tools.

The focus of this lab is operational IT support rather than infrastructure-only setup. Scenarios are designed to simulate realistic Tier 1 and junior systems administration workflows including onboarding, offboarding, password resets, shared resource troubleshooting, remote support, and cloud identity management.

---

## Environment Overview

### Infrastructure
- Windows Server 2025 Domain Controller
- Windows 11 Client Workstations
- VMware Workstation Pro

### Identity & Cloud Platforms
- Active Directory Domain Services (AD DS)
- Microsoft 365 Business Premium
- Microsoft Entra ID
- Microsoft Authenticator / Third Party Authenticators

### Support & Administration Tools
- RSAT (Remote Server Administration Tools)
- Spiceworks Help Desk
- Quick Assist
- Shared Network Folders

---

## Key Skills Demonstrated

- Active Directory Administration
- Microsoft 365 Administration
- Microsoft Entra ID Administration
- User Onboarding & Offboarding
- Password Reset Procedures
- Multi-Factor Authentication (MFA)
- Remote Support
- Shared Folder Permissions
- Mapped Network Drives
- Help Desk Ticketing
- Technical Documentation
- Knowledge Base Development
- Delegated Administration
- Role-Based Access Control (RBAC)
- Identity Lifecycle Management
- Tier 1 Help Desk Operations

---

## Repository Structure

```text
setup/
├── Initial infrastructure and environment configuration

scenarios/
├── Realistic IT support workflows and troubleshooting scenarios

knowledge-base/
├── Internal IT support procedures and operational documentation

tickets/
├── Exported Spiceworks ticket activity

screenshots/
├── Screenshots used for validation and workflow documentation
```

---

## Highlighted Scenarios

### User Onboarding Workflow
Hybrid onboarding process using:
- Active Directory
- Microsoft Entra ID
- Microsoft 365 licensing
- MFA enrollment
- Outlook and Teams verification

File:
```text
scenarios/user-onboarding.md
```

---

### User Offboarding Workflow
Hybrid offboarding process including:
- Active Directory account disablement
- Microsoft 365 sign-in revocation
- License removal
- Administrative escalation procedures

File:
```text
scenarios/offboard-user.md
```

---

### Hybrid Password Reset Workflow
Password reset procedures for:
- Active Directory
- Microsoft 365
- Session revocation
- Identity recovery validation

File:
```text
scenarios/hybrid-password-reset.md
```

---

### Remote Support - Missing Mapped Drive Workflow
Remote troubleshooting workflow using Quick Assist to restore organizational shared drive access.

File:
```text
scenarios/mapped-drive-remote-support.md
```

---

## Knowledge Base Articles

### Current KB Topics
- Hybrid User Onboarding Procedure
- Hybrid User Offboarding Procedure
- Restore Missing Mapped Network Drive
- Reset Active Directory User Password
- Reset Microsoft 365 User Password

---

## Operational Focus

This lab is intentionally focused on:
- realistic help desk workflows
- operational troubleshooting
- role-based administrative boundaries
- escalation procedures
- documentation discipline
- hybrid identity support

rather than infrastructure complexity alone.

---

## Notes

- All users, company names, and organizational data within this repository are fictional and created for educational purposes.
- Sensitive information, personal information, and production credentials have been removed or redacted from screenshots and exported artifacts.
