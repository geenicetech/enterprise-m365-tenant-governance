# Enterprise M365 Tenant Governance & Identity Foundation

## Project Overview

This project demonstrates the design and implementation of **enterprise-grade Microsoft 365 tenant governance** using **least-privilege administrative access** configured through the Microsoft 365 Admin Center**.

The focus of this project is on reducing over-privileged access, enforcing separation of duties, and establishing a secure and auditable administration model suitable for medium-to-large organizations.

## Business Problem
Many organizations operate with excessive Global Administrator privileges, increasing security risk and audit exposure.

## Solution
- Reduced Global Administrator access
- Implemented break-glass emergency account
- Introduced least-privilege administrative access

## Technologies Used
- Microsoft 365 Admin Center

## Architecture
diagrams/m365-role-governance.png

## Key Controls Implemented
- Least privilege administration
- An emergency access account
- Clear separation of duties

## Security Considerations
- Break-glass accounts exclude from Conditional Access policies that could block access
- Strong password policy enforced

## Outcome
A secure, auditable, and enterprise-ready M365 tenant identity foundation.
