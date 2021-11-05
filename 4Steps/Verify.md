# Verify

The verify phase is the last step of the threat modeling process, which often happens before the system is deployed. It involves ensuring requirements are met, assumptions are validated, and security controls are in place.

1. Confirm all previous and new security requirements are satisfied for the system
2. Configure cloud provider, operating system, and components to meet security requirements
3. Ensure all issues are addressed with the right security controls
4. Take system through manual and automated verification before deployment

## Verify requirements and set defaults
Start by verifying all requirements created in the first phase are met.

Examples:

1. Network security plans
2. Secrets management solution implementation
3. Logging and monitoring systems
4. Identity and access controls

Then, make sure the default configuration settings from cloud provider, operating system, and components are changed to meet all security requirements.

Examples:

1. Enable Azure SQL Database transparent data encryption to protect data on disk
2. Use **Role Based Access Control (RBAC)** to assign permissions to users, groups, and applications
3. Enable Windows Firewall across all profiles

All issues logged in the bug management solution should be resolved and all fixes verified.