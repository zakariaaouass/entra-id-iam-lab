# Entra ID IAM Lab

Demonstrating practical Identity & Access Management (IAM) concepts with Microsoft Entra ID.

## Objectives

- Manage users and groups
- Design role-based access control (RBAC)
- Apply least-privilege principles
- Configure application access and SSO foundations
- Explore Conditional Access
- Perform access reviews and document IAM governance decisions
- Capture evidence and lessons learned

## Lab scenario

A fictional company, **Contoso Labs**, has three business teams:

- Sales
- Finance
- IT

The goal is to design a simple, governed identity model where users receive only the access they need for their role.

## Architecture

```text
Users
  |
  +--> Security Groups --> Applications / Resources
  |
  +--> Entra Roles (privileged access)
  |
  +--> Conditional Access --> Authentication / Access controls
  |
  +--> Access Reviews --> Periodic access recertification
```

## Lab modules

### 01 - Tenant and identity foundation
- Create test users
- Create security groups
- Apply naming conventions
- Record the identity inventory

### 02 - RBAC and least privilege
- Define business roles
- Assign access through groups
- Review privileged roles
- Document least-privilege decisions

### 03 - Application access
- Register / integrate a test application
- Assign users/groups
- Document Enterprise Application vs App Registration

### 04 - Conditional Access
- Build a test policy
- Use report-only mode where appropriate
- Document scope, grant controls, and exclusions

### 05 - Access Reviews
- Create an access review for a group or application
- Review unnecessary access
- Record the governance outcome

## Evidence

Screenshots and sanitized exports belong in `/screenshots`.
Do not upload passwords, secrets, tokens, tenant secrets, client secrets, private keys, or personal data.

## Documentation

See `/docs` for the lab notes and governance records.

## Disclaimer

This is a personal training lab using fictional users/resources. No  production information
