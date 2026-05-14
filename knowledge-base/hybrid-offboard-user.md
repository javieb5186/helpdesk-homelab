# Hybrid User Offboarding Procedure (AD DS + Microsoft 365)

## Summary

This knowledge base article outlines the standard procedure for offboarding a user in a hybrid environment using both Active Directory Domain Services (AD DS) and Microsoft 365. The workflow includes disabling local Active Directory access, revoking Microsoft 365 access, removing assigned licenses, and documenting escalation procedures when administrative boundaries are encountered.

---

## Scope

This procedure applies to:
- Employee terminations
- Voluntary departures
- Immediate access revocation requests
- Standard user offboarding workflows

---

## Requirements

### Required Tools
- Active Directory Users and Computers (ADUC)
- RSAT Tools
- Microsoft 365 Admin Center
- Microsoft Entra Admin Center
- Spiceworks Help Desk

### Required Access
- HelpDesk Administrator role
- Delegated Active Directory permissions
- Global Administrator access for license management and cloud account disablement

---

## Active Directory Offboarding Procedure

### 1. Open ADUC
Launch:
```text
dsa.msc
```

from the help desk workstation.

---

### 2. Locate User Account
Navigate to the appropriate organizational unit and locate the user account.

Example:
```text
LAB\jdoe
```

---

### 3. Disable User Account
Right-click the user account and select:
```text
Disable Account
```

Verify the disabled account icon appears within ADUC.

---

### 4. Remove Group Memberships
Remove unnecessary security group memberships if applicable.

Do not remove:
```text
Domain Users
```

unless directed by systems administration procedures.

---

### 5. Move User to Disabled Users OU
Attempt to move the disabled user account into the designated Disabled Users organizational unit.

If insufficient permissions prevent this action:
- document the issue
- escalate to systems administration

---

## Microsoft 365 Offboarding Procedure

### 6. Sign Into Microsoft 365 Admin Center
Access:
```text
admin.microsoft.com
```

using the Helpdesk Administrator account.

---

### 7. Revoke Active Sessions
Locate the user account and revoke active Microsoft 365 sessions.

---

### 8. Escalate Restricted Administrative Actions
If role permissions prevent cloud account disablement or license management:
- escalate to the Global Administrator account

---

### 9. Block Cloud Sign-In Access
Using the Global Administrator account:
- block Microsoft 365 sign-in access for the user

---

### 10. Remove Assigned Licenses
Remove assigned Microsoft 365 licenses such as:
```text
Microsoft 365 Business Premium
```

---

## Validation

Verify:
- Active Directory account is disabled
- Microsoft 365 sign-in is blocked
- Active sessions are revoked
- Assigned licenses are removed
- User access to company resources is revoked

---

## Escalation Notes

Help Desk personnel may encounter permission restrictions for:
- OU management
- cloud account disablement
- license removal

These tasks should be escalated according to role-based administrative boundaries.

---

## Ticket Documentation Example

### Help Desk Update

```text
Disabled local Active Directory account for user and revoked active Microsoft 365 sessions successfully. Escalated cloud account disablement and license removal due to administrative permission restrictions.
```

---

### Systems Administration Update

```text
Blocked Microsoft 365 sign-in access and removed assigned licenses as part of standard offboarding procedure.
```

---

## Related Procedures

- User Onboarding
- Password Reset Procedure
- MFA Reset Procedure
- Shared Folder Access Management# Hybrid User Offboarding Procedure (AD DS + Microsoft 365)

## Summary

This knowledge base article outlines the standard procedure for offboarding a user in a hybrid environment using both Active Directory Domain Services (AD DS) and Microsoft 365. The workflow includes disabling local Active Directory access, revoking Microsoft 365 access, removing assigned licenses, and documenting escalation procedures when administrative boundaries are encountered.

---

## Scope

This procedure applies to:
- Employee terminations
- Voluntary departures
- Immediate access revocation requests
- Standard user offboarding workflows

---

## Requirements

### Required Tools
- Active Directory Users and Computers (ADUC)
- RSAT Tools
- Microsoft 365 Admin Center
- Microsoft Entra Admin Center
- Spiceworks Help Desk

### Required Access
- HelpDesk Administrator role
- Delegated Active Directory permissions
- Global Administrator access for license management and cloud account disablement

---

## Active Directory Offboarding Procedure

### 1. Open ADUC
Launch:
```text
dsa.msc
```

---

### 2. Locate User Account
Navigate to the appropriate organizational unit and locate the user account.

Example:
```text
LAB\jdoe
```

---

### 3. Disable User Account
Right-click the user account and select:
```text
Disable Account
```

Verify the disabled account icon appears within ADUC.

---

### 4. Remove Group Memberships
Remove unnecessary security group memberships if applicable.

Do not remove:
```text
Domain Users
```

unless directed by systems administration procedures.

---

### 5. Move User to Disabled Users OU
Attempt to move the disabled user account into the designated Disabled Users organizational unit.

If insufficient permissions prevent this action:
- document the issue
- escalate to systems administration

---

## Microsoft 365 Offboarding Procedure

### 6. Sign Into Microsoft 365 Admin Center
Access:
```text
admin.microsoft.com
```

---

### 7. Revoke Active Sessions
Locate the user account and revoke active Microsoft 365 sessions.

---

### 8. Escalate Restricted Administrative Actions
If role permissions prevent cloud account disablement or license management:
- escalate to the Global Administrator account

---

### 9. Block Cloud Sign-In Access
Using the Global Administrator account:
- block Microsoft 365 sign-in access for the user

---

### 10. Remove Assigned Licenses
Remove assigned Microsoft 365 licenses such as:
```text
Microsoft 365 Business Premium
```

---

## Validation

Verify:
- Active Directory account is disabled
- Microsoft 365 sign-in is blocked
- Active sessions are revoked
- Assigned licenses are removed
- User access to company resources is revoked

---

## Escalation Notes

Help Desk personnel may encounter permission restrictions for:
- OU management
- cloud account disablement
- license removal

These tasks should be escalated according to role-based administrative boundaries.

---

## Ticket Documentation Example

### Help Desk Update

```text
Disabled local Active Directory account for user and revoked active Microsoft 365 sessions successfully. Escalated cloud account disablement and license removal due to administrative permission restrictions.
```

---

### Systems Administration Update

```text
Blocked Microsoft 365 sign-in access and removed assigned licenses as part of standard offboarding procedure.
```

---
