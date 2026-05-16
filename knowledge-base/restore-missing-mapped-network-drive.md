# Restore Missing Mapped Network Drive

## Summary

This knowledge base article outlines the standard procedure for troubleshooting and restoring a missing mapped network drive for a domain user. The workflow includes remote support using Quick Assist, validation of shared network paths, and restoration of organizational resource access.

---

## Scope

This procedure applies to:
- Missing mapped network drives
- Shared folder access issues
- Standard user network resource troubleshooting
- Remote support workflows

---

## Requirements

### Required Tools
- Quick Assist
- File Explorer
- Shared Network Folder Access

### Required Access
- Standard domain user account
- Shared folder permissions
- Remote support access

---

## Procedure

### 1. Initiate Remote Support Session
Launch:
```text
Quick Assist
```

from the help desk workstation and establish a remote support session with the affected user workstation.

---

### 2. Verify User Issue
Open File Explorer and confirm the mapped network drive is missing.

Example:
```text
S:
```

---

### 3. Validate Shared Network Path
Verify the shared network path is reachable.

Example:
```text
\\DC01\StandardUsers
```

---

### 4. Open Map Network Drive
Open:
```text
This PC → Map Network Drive
```

---

### 5. Configure Network Drive
Configure:
- Drive Letter:
```text
S:
```

- Folder Path:
```text
\\DC01\StandardUsers
```

Enable:
```text
Reconnect at sign-in
```

---

### 6. Complete Drive Mapping
Finish the drive mapping process and verify the mapped drive appears successfully within File Explorer.

---

### 7. Verify Resource Accessibility
Confirm the user can:
- open shared folders
- access organizational files
- perform standard workflow operations

---

## Validation

Verify:
- mapped network drive appears successfully
- shared network path reachable successfully
- organizational resource access restored successfully
- user workflow functionality restored successfully

---
