# Salesforce Administrator Track – Day 4 Learnings

## Objective

Learned Salesforce Security Model, Profiles, Permission Sets, Role Hierarchy, OWD, Sharing Rules, and Field Level Security.

---

# Modules Completed

## Data Security

Learned how Salesforce protects organizational data using multiple layers of security.

## Control Access to Objects

Learned how Profiles and Permission Sets control object-level permissions.

## Control Access to Fields

Learned how Field Level Security controls visibility and editing of fields.

## Control Access to Records

Learned how record-level security determines which records users can access.

## Role Hierarchy

Learned how management can access records owned by subordinate users.

## Sharing Rules

Learned how to provide additional record access when required.

---

# Key Learnings

## Profiles

Profiles determine:

- Object Permissions
- App Permissions
- Login Access
- Field Permissions

Each user must have exactly one Profile.

---

## Permission Sets

Permission Sets:

- Extend user permissions
- Grant additional access
- Reduce profile complexity

Users can have multiple Permission Sets.

---

## Organization-Wide Defaults (OWD)

OWD determines the default access level for records.

Types:

- Private
- Public Read Only
- Public Read/Write
- Controlled by Parent

---

## Role Hierarchy

Role Hierarchy allows higher-level users to access records owned by lower-level users.

Benefits:

- Supports management visibility
- Follows organizational structure
- Simplifies access control

---

## Sharing Rules

Sharing Rules provide additional access beyond OWD.

Types:

- Owner-Based Sharing Rules
- Criteria-Based Sharing Rules

---

## Field Level Security (FLS)

FLS controls:

- Field Visibility
- Field Editability

Benefits:

- Protects sensitive data
- Supports compliance
- Enhances security

---

# Enterprise Security Design

Implemented security for:

- Students
- Faculty
- Placement Officers
- HODs
- Principal
- Salesforce Administrator

Used:

- OWD
- Role Hierarchy
- Sharing Rules
- Permission Sets

to provide secure access.

---

# Reflection

Today I learned that Salesforce security is built in layers. Profiles and Permission Sets determine what users can do, while OWD, Role Hierarchy, and Sharing Rules determine what records users can access. Proper security design protects data and ensures users only access information relevant to their responsibilities.

---

# Day 4 Outcome

✅ Learned Profiles

✅ Learned Permission Sets

✅ Learned OWD

✅ Learned Role Hierarchy

✅ Learned Sharing Rules

✅ Learned Field Level Security

✅ Learned Record-Level Security

✅ Learned Enterprise Access Control

---

# Conclusion

The Salesforce Security Model is one of the most important concepts in Salesforce Administration. Proper use of Profiles, Permission Sets, OWD, Role Hierarchy, and Sharing Rules ensures secure and controlled access to organizational data.
