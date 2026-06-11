# Salesforce Administrator Track – Day 4

## What is OWD?

OWD (Organization-Wide Defaults) is the baseline level of record access in Salesforce. It determines the default access users have to records they do not own.

### Types of OWD

- Private
- Public Read Only
- Public Read/Write
- Controlled by Parent

---

## What is Role Hierarchy?

Role Hierarchy allows users higher in the hierarchy to access records owned by users below them.

### Benefits

- Easier data sharing
- Supports organizational structure
- Improves management visibility

---

## What are Sharing Rules?

Sharing Rules automatically grant additional record access to users based on criteria or ownership.

### Types of Sharing Rules

- Owner-Based Sharing Rules
- Criteria-Based Sharing Rules

---

# Difference Between Profile, Permission Set, and Role

| Feature | Profile | Permission Set | Role |
|----------|----------|---------------|------|
| Controls User Actions | Yes | Yes | No |
| Controls Record Visibility | No | No | Yes |
| Assigned to User | One | Multiple | One |
| Grants Extra Access | No | Yes | No |
| Defines Data Hierarchy | No | No | Yes |

---

# College Security Design

## User Access Matrix

| Role | Student Records | Faculty Records | Placement Records |
|--------|---------------|---------------|---------------|
| Student | View Own | No | View Own |
| Faculty | View Students | View Own | No |
| Placement Officer | View | View | View/Edit |
| HOD | View Department | View Department | View Department |
| Principal | View All | View All | View All |
| Salesforce Administrator | Full Access | Full Access | Full Access |

---

## Edit Permissions

| Role | Attendance | Placement Data | Student Details |
|--------|------------|----------------|----------------|
| Student | No | No | Own Details |
| Faculty | Yes | No | No |
| Placement Officer | No | Yes | No |
| HOD | Yes | Yes | Yes |
| Principal | Yes | Yes | Yes |
| Salesforce Administrator | Yes | Yes | Yes |

---

## Delete Permissions

| Role | Student Records | Placement Records |
|--------|----------------|------------------|
| Student | No | No |
| Faculty | No | No |
| Placement Officer | No | Yes |
| HOD | No | No |
| Principal | No | No |
| Salesforce Administrator | Yes | Yes |

---

# Faculty Access Scenario

## Requirement

- Faculty A → Only CSE Students
- Faculty B → Only ECE Students
- HOD → All Students in Department
- Principal → All Students

---

## OWD Design

Student Records = Private

Reason:
Only record owners can access records by default.

---

## Role Hierarchy

Principal
│
├── CSE HOD
│ └── CSE Faculty
│
└── ECE HOD
└── ECE Faculty

Reason:
Allows HODs to see records of faculty members within their department.

---

## Sharing Rules

- Share CSE student records with CSE Faculty.
- Share ECE student records with ECE Faculty.

Reason:
Provides controlled access to department-specific records.

---

## Permission Sets

Use Permission Sets for:

- Attendance Editing
- Placement Access
- Additional Reporting Permissions

Reason:
Avoids creating multiple profiles.

---

# Reflection

## Why Should Salesforce Not Make All Records Visible?

1. Protects student privacy.
2. Prevents unauthorized access.
3. Supports organizational hierarchy.
4. Reduces accidental modifications.
5. Protects sensitive information.
6. Ensures regulatory compliance.
7. Improves security.
8. Prevents data misuse.
9. Limits insider threats.
10. Supports role-based access control.



✅ Field Level Security

✅ Record-Level Security

✅ Enterprise Access Control
