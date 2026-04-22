# Microsoft 365 Tenant Role Responsibility Matrix

---

## Purpose

This document defines administrative role responsibilities within the Microsoft 365 tenant to ensure:
- Least-privilege access
- Clear separation of duties
- Improved security and governance
- Audit and compliance readiness

---

## Role Responsibility Matrix

| Role | Scope of Responsibility | Notes |
|----|----|----|
| Standard Users | Day-to-day productivity activities | No admin access |
| Security Administrator | Security settings, identity protection, Defender configurations | No service administration |
| Exchange Administrator | Exchange Online mailboxes, mail flow, and messaging services | No tenant-wide access |
| SharePoint Administrator | SharePoint Online and related services | No Exchange or Intune access |
| Intune Administrator | Device enrollment, compliance, and configuration management | No user or mail administration |
| Global Administrator | Full Microsoft 365 tenant access | Used only when necessary |
| Break-Glass Admin Account | Emergency tenant access | Used only in loss-of-access scenarios |

---

## Global Administrator Policy

A minimum of two (2) Global Administrator accounts:
- Primary Global Admin → Used only when necessary
- Break-Glass Global Admin → Emergency use only
- Role is used strictly for high-impact administrative tasks
  
---

## Break-Glass Account Policy

Used only in:
- Identity lockout scenarios
- Conditional Access misconfigurations
Security configuration:
- Excluded from Conditional Access policies that could block access
- Protected with a strong, securely stored password
- Sign-in activity is monitored
- Credentials are reviewed periodically

---

## Governance Principles

- Least privilege at all times
- Role separation to minimize blast radius
- Minimize use of high-privilege accounts
- Emergency access preserved without operational exposure
- Ensure full auditability of administrative actions

---

## Compliance Alignment

This role model aligns with:
- Microsoft identity security best practices
- Enterprise Zero Trust principles
- Industry-standard audit and compliance frameworks
