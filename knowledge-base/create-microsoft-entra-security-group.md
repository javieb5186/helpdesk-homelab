# Create Microsoft Entra Security Group

## Summary

This knowledge base article outlines the standard procedure for creating and managing Microsoft Entra security groups used for organizational access management, cloud administration, and role-based access control (RBAC) workflows.

---

## Scope

This procedure applies to:
- Organizational access management
- Cloud administrative group creation
- Role-based access control (RBAC)
- Microsoft 365 organizational group management
- Cloud identity administration

---

## Requirements

### Required Tools
- Microsoft Entra Admin Center
- Microsoft 365 Organizational Account

### Required Access
- Organizational administrative account
- Group management permissions within Microsoft Entra ID

---

## Procedure

### 1. Access Microsoft Entra Admin Center
Open:
```text
entra.microsoft.com
```

---

### 2. Navigate to Group Management
Open:
```text
Groups → All Groups
```

within Microsoft Entra Admin Center.

---

### 3. Create New Group
Select:
```text
New Group
```

to begin group creation.

---

### 4. Configure Group Settings
Configure the following settings:

| Setting | Value |
|---|---|
| Group Type | Security |
| Membership Type | Assigned |

Example group name:
```text
RemoteSupport_Technicians
```

---

### 5. Configure Group Description
Add a description reflecting the organizational purpose of the group.

Example:
```text
Remote support technician security group for organizational support operations
```

---

### 6. Add Group Members
Assign authorized organizational users as group members.

Example:
```text
helpdesk@helpdeskhomelab.onmicrosoft.com
```

---

### 7. Complete Group Creation
Finish the group creation process and verify the group appears successfully within Microsoft Entra Admin Center.

---

### 8. Verify Group Membership
Confirm assigned members appear correctly within the group membership configuration page.

---

## Validation

Verify:
- security group created successfully
- assigned membership configuration applied successfully
- organizational users added successfully
- group visibility verified successfully
- group membership displays correctly
