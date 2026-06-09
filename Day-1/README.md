# Day 1 - User Management and Security

## What is a Salesforce Administrator?

A Salesforce Administrator manages users, security, permissions, and system configurations in Salesforce.

## Difference Between User, Role, Profile, and Permission Set

### User
A person who can log in to Salesforce.

### Profile
Defines what a user can do.

### Role
Defines what records a user can see.

### Permission Set
Provides extra permissions without changing the profile.

## College Security Design

| Role | Student | Course | Placement | Attendance |
|--------|--------|--------|--------|--------|
| Student | View | View | View | View |
| Faculty | View/Edit | View/Edit | View | Create/Edit |
| Placement Officer | View | View | Create/Edit/Delete | View |
| HOD | View/Edit | View/Edit | View/Edit | View/Edit |
| Principal | View/Edit | View/Edit | View/Edit | View/Edit |
| Salesforce Admin | Full Access | Full Access | Full Access | Full Access |

## Admin Access Risks

If a student gets Administrator access:

- Sensitive data may be exposed
- Records can be modified or deleted
- Security settings can be changed
- Users can be created or removed

### Prevention
- Use Least Privilege Access
- Assign Correct Profiles
- Review Permissions Regularly
- Enable MFA

## Learnings

- Salesforce Admin manages users and security.
- Profiles control permissions.
- Roles control record visibility.
- Permission Sets provide additional access.
- Identity Management secures user authentication.

## Reflection

Strong access control is important because it protects data, prevents unauthorized access, and maintains system security.
