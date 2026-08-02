# Identity and Access Management (IAM)

## Overview

Identity and Access Management (IAM) is a cybersecurity framework that ensures only authorized users, devices, and applications can access organizational resources. It combines policies, technologies, and processes to authenticate user identities and control access to systems, applications, networks, and sensitive data.

IAM plays a vital role in protecting organizations from unauthorized access, insider threats, and data breaches. Modern enterprises rely on IAM solutions to manage millions of digital identities while ensuring secure and seamless access across on-premises and cloud environments.

---

# Objectives of IAM

The primary objectives of Identity and Access Management are:

- Verify the identity of users.
- Control access to resources.
- Protect sensitive information.
- Prevent unauthorized access.
- Enforce security policies.
- Improve regulatory compliance.
- Reduce insider threats.

---

# Identity vs Authentication vs Authorization

| Concept | Description |
|----------|-------------|
| Identity | The digital representation of a user, device, or application. |
| Authentication | Verifying that the identity is genuine. |
| Authorization | Determining what an authenticated user is allowed to access. |

---

# IAM Workflow

```text
        User Login
             │
             ▼
     Identity Verification
             │
             ▼
      Authentication
             │
             ▼
      Authorization
             │
             ▼
 Access Granted / Denied
```

---

# Authentication Methods

Authentication confirms that a user is who they claim to be.

### 1. Password-Based Authentication

The most common authentication method where users enter a username and password.

**Advantages**

- Simple to implement
- Widely supported

**Limitations**

- Weak passwords
- Password reuse
- Phishing attacks

---

### 2. Multi-Factor Authentication (MFA)

MFA requires users to verify their identity using two or more authentication factors.

Common factors include:

- Something you know (Password/PIN)
- Something you have (Phone, Security Token)
- Something you are (Fingerprint, Face Recognition)

**Benefits**

- Stronger security
- Reduced account compromise
- Protection against stolen passwords

---

### 3. Biometric Authentication

Uses unique physical characteristics for identity verification.

Examples:

- Fingerprint
- Face Recognition
- Retina Scan
- Voice Recognition

---

### 4. One-Time Password (OTP)

A temporary code generated for a single login session.

Examples:

- SMS OTP
- Email OTP
- Authenticator App Codes

---

# Authorization

Authorization determines the level of access an authenticated user receives.

Examples:

- Student → Access course materials
- Faculty → Manage student records
- Administrator → Full system control

---

# Access Control Models

## 1. Role-Based Access Control (RBAC)

Permissions are assigned according to job roles.

Example:

| Role | Permissions |
|------|-------------|
| Student | View Course Content |
| Faculty | Upload Grades |
| Administrator | Full Access |

RBAC simplifies permission management in large organizations.

---

## 2. Attribute-Based Access Control (ABAC)

Access decisions are based on attributes such as:

- User role
- Department
- Device type
- Location
- Time of access

---

## 3. Mandatory Access Control (MAC)

Access permissions are determined by a central authority.

Commonly used in:

- Military
- Government
- Defense organizations

---

## 4. Discretionary Access Control (DAC)

Resource owners decide who can access their files or resources.

Example:

Sharing a Google Drive document with selected users.

---

# Principle of Least Privilege

The Principle of Least Privilege (PoLP) states that users should receive only the minimum permissions required to perform their tasks.

### Benefits

- Reduces attack surface
- Limits insider threats
- Prevents accidental misuse
- Improves security management

---

# Single Sign-On (SSO)

Single Sign-On allows users to authenticate once and access multiple applications without logging in repeatedly.

### Advantages

- Better user experience
- Reduced password fatigue
- Centralized authentication
- Improved productivity

Examples:

- Google Workspace
- Microsoft 365
- Enterprise Portals

---

# Identity Lifecycle Management

Managing digital identities involves several stages.

```text
Create Identity
       │
       ▼
Assign Permissions
       │
       ▼
Monitor Activity
       │
       ▼
Modify Access
       │
       ▼
Disable/Delete Account
```

Proper lifecycle management prevents unauthorized access from inactive accounts.

---

# Real-World Example

## Corporate Employee Access

A new employee joins an organization.

1. HR creates a digital identity.
2. IT assigns the employee to the appropriate department.
3. IAM automatically grants access to required applications.
4. Multi-Factor Authentication is enabled.
5. Login activity is continuously monitored.
6. When the employee leaves the organization, all accounts are immediately deactivated.

This automated process improves security while reducing administrative effort.

---

# Benefits of IAM

- Stronger access control
- Improved data security
- Reduced risk of unauthorized access
- Better compliance with security standards
- Simplified user management
- Enhanced productivity through SSO
- Better visibility into user activities

---


## Summary

Identity and Access Management is a foundational component of modern cybersecurity. By combining authentication, authorization, access control models, and continuous monitoring, organizations can protect sensitive resources from unauthorized access while providing users with secure and efficient access to the systems they need. As organizations increasingly adopt cloud computing and remote work, IAM continues to play a critical role in securing digital identities and maintaining organizational security.
