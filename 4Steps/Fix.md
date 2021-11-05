# Fix

The fix phase is where the fate of all threats is decided. Each STRIDE threat maps to one or more security controls, which offer different functions and types to choose from.

## Goals

1. Measure each threat against a prioritization framework or security bug bar
2. Track each threat as a task or work item in a bug management service
3. Generate security control recommendations that are mapped to STRIDE threats
4. Select one or more security control types and functions to address each threat
5. Resolve tasks

## Set up a threat tracking workflow
### Prioritize threats

Start by measuring each threat against a prioritization framework or security bug bar. This process helps you arrange resources to fix issues deemed most important to your organization.

The process uses three key variables:

| **Variable** | **Description** |
| ------------ | --------------- |
| Impact | Uses STRIDE categories to assign impact. |
| Severity | Uses internal bug bar or prioritization framework to assign severity using worst case scenarios. |
| Risk	 | Uses a calculation of security control effectiveness and implementation cost. |

## Security control types and functions

Security controls have different types and functions. When combined, they help secure your system and create multiple layers of security, also known as defense-in-depth.

You can choose one or more security control types:

1. Physical, like cameras
2. Technical, like encryption
3. Administrative, like policies

| **Function** | **Description** |
| ------------ | --------------- |
| Preventive | Reduces the probability or impact of a threat, like firewalls. |
| Detective | Identifies attacks as they happen, like surveillance. |
| Corrective | Controls how the system responds to an ongoing attack, like system patches. |
| Recovery | Recovers system from an attack, like backups. |
| Deterrent | Keeps attackers away from the system, like least privilege. |

## Add security control details to each issue

Add the details to each issue in the bug management solution, then resolve each issue with one of the following resolutions. They'll vary slightly from organization to organization:

| **Resolution** | **Description** |
| ------------ | --------------- |
| Reduce | Issue will be addressed with bug fixes or redesign to reduce or eliminate threat impact and severity. |
| Transfer | Issue will be handled by another system or team. |
| Avoid | The part of the system containing the issue will be cut. |
| Accept | Risk will be accepted without a resolution. It will require the approval of an authorized risk decision maker, which may be based on threat severity. Critical severity threats may require approval from senior leadership, while a defense-in-depth risk may be approved by a senior engineer. Speak with your team for strategic guidance. |





