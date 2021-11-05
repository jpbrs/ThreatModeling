# Design

The design phase is the starting ground for your threat modeling activities. You'll gather as much data as possible about what you're building, and what you're using to build it with.

## Ask Questions about your system

**Area** | **Questions**
System description	| What does the system do? What are the business processes handled by the service? Are they clearly defined?
System environment	| Will the system be built on the cloud or on-premise? Which OS will it be built on? Will containers be used? Is the system an application, service, or something entirely different?
Scenarios	| How will the system be used? How will it not be used?
Permissions	| Does the system have script execution, data, or hardware access requirements? If so, what are they?
Cloud provider	| Which cloud provider will the system use? What default security configuration options does it provide? How do these options affect the system security requirements?
Operating system	| Which Operating System will the system use? What default security configuration options does it offer? How do these options affect the system security requirements?
First- and third-party	| Which first- and third-party services will the system use? What default security configuration options do they offer? How do these options affect the system security requirements?
Accounts	| What are the account types that will be used in the system, like users and administrators? Will these accounts be local or cloud enabled? What access do they need and why?
Identity & access control	| How will the system help secure those accounts? Will it rely on Azure Active Directory (Azure AD)? Will it use features like Access Control Lists (ACL), Multi-Factor Authentication (MFA) and Session control?
Tokens & sessions	| Will the system process requests like SOAP or REST APIs? How will it handle different sessions?
Bypass	| Will the system use or require back-doors? If so, how will it work?
Logging, monitoring and backing up	| What are the mechanisms used by the system to log security events, monitor for anomalies and back up system data? Which event types will it capture?
Network	| What are all the intrusion, detection, and protection systems that will be used? How will communication be encrypted?
Data	| What type of data will be created or handled by the system? What will the data classification type be? How will the system trust data sources? How will it parse data? What will be the expected input and output behaviors? How will validation be handled? How will data be encrypted across all states?
Secrets management	| How will the system handle keys, certificates, and credentials?