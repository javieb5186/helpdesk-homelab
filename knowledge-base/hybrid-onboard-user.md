# Hybrid User Onboarding Procedure (AD DS + Microsoft 365)

## Summary

This knowledge base article outlines the standard onboarding procedure for provisioning a new employee account in both Active Directory and Microsoft 365 environments. The workflow includes Active Directory account creation, Microsoft Entra ID provisioning, license assignment, MFA enrollment, and validation of standard organizational access.

## Steps

1. Open Active Directory Users and Computers (dsa.msc) from the help desk workstation.

2. Navigate to the appropriate organizational unit for standard users.

3. Create a new Active Directory user account.
   - Configure first name, last name, and username.
   - Assign a temporary password.
   - Enable "User must change password at next logon."

4. Configure initial user information.
   - Department
   - Job Title
   - Office information

5. Verify appropriate group memberships and standard domain access.

6. Sign into Microsoft Entra Admin Center using the helpdesk administrative account.

7. Create a new Microsoft Entra ID user account.
   - Configure username and display name.
   - Assign a temporary password.
   - Require password change at first sign-in.

8. Escalate Microsoft 365 license assignment to the Global Administrator account if licensing permissions are restricted.

9. Assign the Microsoft 365 Business Premium license to the user account.

10. Verify successful Microsoft 365 account provisioning.

11. Have the user sign into Microsoft 365 services.
   - Outlook Web
   - Microsoft Teams
   - OneDrive

12. Guide the user through Multi-Factor Authentication (MFA) enrollment using Microsoft Authenticator.

13. Verify successful cloud authentication and organizational resource access.

14. Update the Spiceworks ticket with onboarding actions, escalations, and final resolution notes.

## Conclusion

The onboarding process was completed successfully by provisioning both Active Directory and Microsoft 365 access for the new employee account. Standard organizational access, MFA enrollment, and cloud application functionality were verified successfully.
