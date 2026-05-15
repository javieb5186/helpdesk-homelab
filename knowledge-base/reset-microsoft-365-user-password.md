# Reset Microsoft 365 User Password

## Summary

This knowledge base article outlines the standard procedure for resetting a Microsoft 365 user password and revoking active cloud authentication sessions.

---

## Scope

This procedure applies to:
- Forgotten Microsoft 365 passwords
- Cloud authentication issues
- Organizational account recovery requests
- Microsoft 365 access restoration workflows

---

## Requirements

### Required Tools
- Microsoft 365 Admin Center
- Microsoft Entra Admin Center

### Required Access
- Helpdesk Administrator role
- User Administrator role

---

## Procedure

### 1. Sign Into Microsoft 365 Admin Center
Access:
```text
admin.microsoft.com
```

using the help desk administrative account.

---

### 2. Locate User Account
Navigate to:
```text
Users → Active Users
```

Locate the user account.

Example:
```text
asmith@helpdeskhomelab.onmicrosoft.com
```

---

### 3. Reset Password
Select:
```text
Reset password
```

Configure:
- Temporary password
- Require password change at next sign-in

---

### 4. Revoke Active Sessions
Revoke active Microsoft 365 sessions to invalidate existing authentication tokens and force reauthentication.

---

### 5. Verify Account Accessibility
Verify the user can successfully authenticate using updated credentials.

---

## Validation

Verify:
- password reset completed successfully
- active sessions revoked successfully
- password change prompt appears
- Microsoft 365 access restored successfully

---

## Ticket Documentation Example

```text
Reset Microsoft 365 password successfully, revoked active sessions, and enforced password change requirement during next sign-in. Verified restored cloud authentication successfully.
```
