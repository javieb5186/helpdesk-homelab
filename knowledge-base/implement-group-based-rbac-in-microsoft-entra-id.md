# Implement Group-Based Administrative RBAC in Microsoft Entra ID

## Summary

This knowledge base article outlines the standard procedure for implementing centralized role-based access control (RBAC) within Microsoft Entra ID using role-assignable security groups for administrative role inheritance and organizational access management.

---

## Scope

This procedure applies to:
- Organizational administrative access management
- Centralized RBAC implementation
- Microsoft Entra administrative role management
- Privileged access group configuration
- Cloud identity administration

---

## Requirements

### Required Tools
- Microsoft Entra Admin Center
- Microsoft 365 Organizational Administrative Account

### Required Access
- Global Administrator permissions
- Microsoft Entra administrative role management permissions

---

## Procedure

### 1. Access Microsoft Entra Admin Center
Open:
```text
entra.microsoft.com
```

and sign in using the organizational administrative account.

---

### 2. Create Role-Assignable Security Group
Navigate to:
```text
Groups → New Group
```

Configure:
- Group Type:
```text
Security
```

- Membership Type:
```text
Assigned
```

Enable:
```text
Microsoft Entra roles can be assigned to the group
```

Example group name:
```text
RemoteSupport_Admins
```

---

### 3. Add Administrative Group Members
Add authorized organizational administrative users as members of the role-assignable security group.

Example:
```text
helpdesk@helpdeskhomelab.onmicrosoft.com
```

---

### 4. Access Administrative Roles
Navigate to:
```text
Identity → Roles & admins
```

within Microsoft Entra Admin Center.

---

### 5. Assign Administrative Roles to Group
Select the required Microsoft Entra administrative role.

Examples:
- Helpdesk Administrator
- User Administrator

Select:
```text
Add assignments
```

Assign the:
```text
RemoteSupport_Admins
```

role-assignable security group to the selected administrative role.

Repeat the assignment process for all required administrative roles.

---

### 6. Remove Direct Administrative Assignments
If transitioning fully to centralized RBAC management:
- remove direct individual administrative role assignments from user accounts

---

### 7. Validate Inherited Administrative Access
Verify users inherit administrative permissions successfully through group membership.

Validate:
- user administration
- password reset capability
- administrative portal access
- organizational support workflows

---

## Validation

Verify:
- role-assignable security group created successfully
- administrative group membership configured successfully
- Microsoft Entra administrative roles assigned successfully
- inherited administrative permissions function correctly
- centralized RBAC structure implemented successfully
