# Register Windows Workstation with Microsoft Entra ID

## Summary

This knowledge base article outlines the standard procedure for registering a domain-joined Windows workstation with Microsoft Entra ID to establish organizational cloud identity association and prepare endpoints for future cloud management workflows.

---

## Scope

This procedure applies to:
- Organizational workstation registration
- Hybrid identity environments
- Cloud-connected endpoint preparation
- Microsoft 365 organizational device association

---

## Requirements

### Required Tools
- Windows 11 Pro
- Microsoft Entra Admin Center
- Microsoft 365 Organizational Account

### Required Access
- Organizational Microsoft 365 account
- Standard workstation access
- Multi-Factor Authentication (MFA)

---

## Procedure

### 1. Sign Into Workstation
Sign into the workstation using the organizational domain account.

Example:
```text
LAB\helpdesk
```

---

### 2. Open Work or School Access Settings
Navigate to:
```text
Settings → Accounts → Access work or school
```

---

### 3. Connect Organizational Account
Select:
```text
Connect
```

to begin organizational account association.

---

### 4. Authenticate Organizational Account
Sign into the Microsoft 365 organizational account.

Example:
```text
helpdesk@helpdeskhomelab.onmicrosoft.com
```

Complete authentication and MFA verification if prompted.

---

### 5. Verify Organizational Association
Confirm the workstation displays:
```text
Connected to organization
```

within the Access work or school configuration window.

---

### 6. Verify Device Visibility in Entra
Open:
```text
entra.microsoft.com
```

Navigate to:
```text
Devices → All Devices
```

Verify the workstation appears successfully within the Entra device inventory.

---

### 7. Confirm Device Registration State
Verify the device registration state displays:
```text
Registered
```

---

## Validation

Verify:
- workstation remains domain joined successfully
- organizational cloud identity association completed successfully
- Microsoft authentication completed successfully
- device appears within Entra Admin Center successfully
- device registration state displays correctly
