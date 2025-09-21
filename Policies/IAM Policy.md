## Purpose
This policy establishes rules and responsibilities for managing user access to information
systems, applications, and data to ensure that only authorized individuals have access to
relevant resources based on business need and job role.

## Scope
Applies to all employees, contractors, and third-party users of systems, applications, and
networks within the ISMS scope of Stark Industries Inc., including the SaaS platform and
supporting infrastructure.

## Access Control Principles
1. Least Privilege: Users are granted the minimum access necessary to perform their duties.
2. Need to Know: Access to confidential, restricted, and classified information is limited to those with a justified business requirement.
3. Role-Based Access Control (**RBAC**): Access is defined and granted according to job function.
4. Segregation of Duties: Critical tasks must be split among multiple users to prevent errors and reduce fraud risk.

## User Access Management
### Registration/De-registration
1. All accounts must be formally requested, approved, and documented.
2. Access is removed immediately when a user leaves the company or changes
3. roles.

## User Responsibilities (Annex A, 5.16)
Users must:
1. Keep manage credentials and keep them confidential and secure.
2. Report suspected unauthorized access immediately.
3. Not share login credentials or reuse passwords across systems, including those from personal devices.

## Access Review and Monitoring
### Access to key systems is reviewed:
1. Quarterly for privileged accounts
2. Every 12 months for all other users
3. Inactive accounts are disabled or removed after 30 days of inactivity.

## Remote Access and Third Parties
Remote access is only permitted through approved, secure channels.
### Third-party access requires:
1. Contract (i.e. NDA) in place
2. Time-bound, monitored access
3. Logging and review of actions

## Authentication Requirements
All systems require strong authentication. \
Password policies to follow NIST guidelines (https://auditboard.com/blog/nist-password-guidelines)
### MFA is enforced for:
1. Admin accounts
2. Cloud environments 
3. Remote access

## Access to Sensitive Data
### Access to confidential, restricted, or classified data must be:
1. Logged
2. Reviewed for anomalies
3. Limited to individuals with signed access agreements

## Segregation of Duties Implementation (Annex A, 5.3)
|Function	|Primary Role	|Secondary/Approval Role|
|-------------|-------------|-------------|
|Code development and Deployment|	Developer	|Infrastructure engineer (approves production deployment)|
|Access approvals for critical systems	|System Owner	|Information: Security Manager|
|Backup and restoration	| Infrastructure Engineer	|GRC Analyst or IT Engineer|

## Enforcement
### Violations of this policy may result in:
1. Immediate access revocation
2. Disciplinary action
3. Potential legal consequences

## Roles and Responsibilities

|Role	|Responsibility|
|-------|-------|
|Information Security Manager	|Oversees policy enforcement and reviews| 
|GRC Analyst |	Conducts access reviews, tracks approvals, supports audits| 
|System Owners |	Approve and monitor access to their respective assets| 
|All Users |	Follow access procedures and report issues promptly|

## Policy Review
### The contents within this document are to be audited every 12 months or upon significant change to the environment or regulatory requirements.

|Date |Version |Author | Description |Approval by | Last Updated | Review Frequency |Next Review|
|------|---|----------|--------------------|----------|------|------|------|
| &nbsp; | &nbsp; |  &nbsp;  |   &nbsp; |  &nbsp; |  &nbsp; |  &nbsp; | &nbsp; |
| &nbsp; | &nbsp; |  &nbsp;  |   &nbsp; |  &nbsp; |  &nbsp; |  &nbsp; | &nbsp; |
| &nbsp; | &nbsp; |  &nbsp;  |   &nbsp; |  &nbsp; |  &nbsp; |  &nbsp; | &nbsp; |


