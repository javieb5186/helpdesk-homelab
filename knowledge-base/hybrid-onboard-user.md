# Hybrid User Onboarding Procedure (AD DS + Microsoft 365)

## Summary

This knowledge base article outlines the standard onboarding procedure for provisioning a new employee account in both Active Directory Domain Services (AD DS) and Microsoft 365 environments. The workflow includes Active Directory account creation, Microsoft Entra ID provisioning, license assignment, MFA enrollment, and validation of organizational resource access.

---

## Scope

This procedure applies to:
- New employee onboarding
- Standard user account provisioning
- Microsoft 365 user provisioning
- Initial organizational access configuration

---

## Requirements

### Required Tools
- Active Directory Users and Computers (ADUC)
- RSAT Tools
- Microsoft 365 Admin Center
- Microsoft Entra Admin Center
- Spiceworks Help Desk

### Required Access
- Helpdesk Administrator role
- User Administrator role
- Delegated Active Directory permissions
- Global Administrator access for license assignment if required

---

## Active Directory Onboarding Procedure

### 1. Open ADUC
Launch:
```text
dsa.msc
```

---

### 2. Navigate to User OU
Navigate to the appropriate organizational unit for standard employee accounts.

Example:
```text
Standard Users
```

---

### 3. Create New User Account
Create a new Active Directory user account.

Example:
```text
LAB\asmith
```

Configure:
- First Name
- Last Name
- Username
- Temporary password

---

### 4. Configure Password Policy
Enable:
```text
User must change password at next logon
```

to enforce standard onboarding security practices.

---

### 5. Configure User Information
Populate standard user information fields:
- Department
- Job Title

---

### 6. Verify Group Memberships
Verify the user has appropriate standard access and required security group memberships.

---

## Microsoft 365 Onboarding Procedure

### 7. Sign Into Microsoft Entra Admin Center
Access:
```text
entra.microsoft.com
```

using the Helpdesk Administrator account.

---

### 8. Create Microsoft Entra ID User
Create a new cloud user account.

Example:
```text
asmith@helpdeskhomelab.onmicrosoft.com
```

Configure:
- Display name
- Username
- Temporary password

Enable:
```text
Require password change at first sign-in
```

---

### 9. Assign Microsoft 365 License
Assign:
```text
Microsoft 365 Business Premium
```

If licensing permissions are restricted:
- escalate to the Global Administrator account

---

### 10. Verify Account Provisioning
Verify:
- successful cloud account creation
- license assignment
- cloud service availability

---

## User Onboarding Tasks

### 11. Initial User Sign-In
Have the user sign into Microsoft 365 services.

---

### 12. Password Change
Verify the user changes the temporary password during initial sign-in.

---

### 13. MFA Enrollment
Guide the user through Multi-Factor Authentication enrollment using an Authenticator.

---

### 14. Verify Cloud Services
Verify successful access to:
- Outlook Web
- Microsoft Teams
- OneDrive

---

## Validation

Verify:
- Active Directory account exists and is enabled
- Microsoft Entra ID account exists successfully
- Microsoft 365 license assigned successfully
- MFA enrollment completed successfully
- Outlook access verified
- Teams access verified
- OneDrive access verified

---

## Escalation Notes

Help Desk personnel may encounter permission restrictions for:
- Microsoft 365 license assignment
- advanced cloud administrative actions
- tenant-wide configuration changes

These tasks should be escalated according to role-based administrative boundaries.

---
