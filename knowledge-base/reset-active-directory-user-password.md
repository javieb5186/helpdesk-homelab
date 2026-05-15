# Reset Active Directory User Password

## Summary

This knowledge base article outlines the standard procedure for resetting a user password in Active Directory Domain Services (AD DS) using Active Directory Users and Computers (ADUC).

---

## Scope

This procedure applies to:
- Forgotten passwords
- Locked user accounts
- Standard password reset requests
- Initial account recovery workflows

---

## Requirements

### Required Tools
- Active Directory Users and Computers (ADUC)
- RSAT Tools

### Required Access
- Delegated Active Directory password reset permissions

---

## Procedure

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
LAB\asmith
```

---

### 3. Reset Password
Right-click the user account and select:
```text
Reset Password
```

Configure:
- Temporary password
- User must change password at next logon

---

### 4. Unlock Account (If Applicable)
If the account is locked:
- unlock the account during the password reset process

---

### 5. Verify Account Status
Verify:
- account remains enabled
- password reset completed successfully

---

## Validation

Verify:
- user can authenticate successfully
- password change prompt appears at next sign-in
- organizational access is restored

---

## Ticket Documentation Example

```text
Reset Active Directory password successfully and enforced password change requirement during next sign-in. Verified account accessibility following password reset.
```
