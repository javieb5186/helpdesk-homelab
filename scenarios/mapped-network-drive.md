# Mapped Network Drive Configuration

## Objective

Configure a persistent mapped network drive for a domain user to simulate shared company storage access within a Windows domain environment.

---

## Environment

### Systems
- DC01
- CLIENT01

### Technologies
- Windows Server 2025
- Active Directory
- SMB File Sharing
- Windows 11 Pro
- Mapped Network Drives

---

## Share Information

| Drive Letter | Network Path |
|---|---|
| S: | \\\DC01\StandardUsers |

---

## Configuration Steps

### 1. Verified Shared Folder Access
Confirmed that the `LAB\jdoe` domain account had appropriate permissions to access the `StandardUsers` shared folder.

### 2. Opened Map Network Drive Wizard
Used File Explorer on CLIENT01 to configure a mapped network drive.

### 3. Configured Drive Mapping
Configured the following settings:
- Drive Letter: `S:`
- Folder Path: `\\DC01\StandardUsers`
- Reconnect at sign-in: Enabled

### 4. Connected to Shared Folder
Successfully mapped the shared folder as a persistent network drive.

---

## Validation

### Successful Validation
- `S:` drive appeared successfully in File Explorer
- `LAB\jdoe` accessed the mapped drive successfully
- File creation and modification worked successfully
- Drive remained persistent after sign-in

---

## Key Concepts Practiced

- SMB File Sharing
- Network Drive Mapping
- Active Directory Authentication
- Shared Folder Permissions
- Persistent Drive Mapping
- Windows File Explorer Administration
- Domain Resource Access

---

## Screenshots

### Mapped Network Drive

![Mapped Drive](../screenshots/scenarios/mapped-network-drive/mapped-drive.png)
