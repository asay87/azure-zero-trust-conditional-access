# 🟦 Azure Zero Trust & Conditional Access Blueprint

This project demonstrates a complete **Zero Trust identity security implementation** using **Microsoft Entra ID (Azure AD)**.  
It includes Conditional Access policies, MFA enforcement, Identity Protection, and RBAC least privilege configuration.

The purpose is to show how I design and implement **cloud security controls** in a real Azure environment using industry standards (Zero Trust, NIST, CIS).

---

## 🔐 1. Conditional Access Policies Implemented

### ✔ Mandatory MFA for all users
- Enforces MFA for every authentication attempt  
- Blocks risks related to password-only authentication  
📄 File: `conditional_access/mfa_for_all_users.md`

### ✔ Block legacy authentication
- Legacy protocols (IMAP, POP, SMTP Basic Auth) fully blocked  
- Prevents password spray and brute force  
📄 File: `conditional_access/block_legacy_auth.md`

### ✔ Location-based access control
- Blocks sign-ins from risky or unknown countries  
- Allows only trusted locations  
📄 File: `conditional_access/location_based_access.md`

### ✔ Risky sign-in enforcement (Identity Protection)
- High-risk sign-ins are blocked or forced to MFA  
📄 File: `conditional_access/risky_signin_policy.md`

### ✔ Require compliant device (Intune integration)
- Only Intune-compliant devices can access critical apps  
📄 File: `conditional_access/compliant_device_policy.md`

---

## 👤 2. Identity Protection (Entra ID)

### Implemented controls:
- Risky sign-ins monitoring  
- Risky users review  
- Automated remediation actions  
📄 Files:
- `identity_protection/identity_risks_dashboard.md`
- `identity_protection/risky_users_findings.md`

---

## 🧱 3. RBAC & Privileged Access (Least Privilege)

### RBAC Controls:
- No Global Admin for daily use  
- Admin accounts protected by MFA + CA  
- Role assignments minimized (least privilege)  
📄 Files:
- `rbac/least_privilege_roles.md`
- `rbac/admin_roles_pim.md`

---

## 🧩 4. Architecture Diagrams

- Zero Trust identity architecture  
- Authentication flow diagram  
- Conditional Access policy architecture

Files:
- `diagrams/zero_trust_architecture.png`
- `diagrams/identity_flow.png`

---

## 🎯 Goals of the Project

This project demonstrates:
- 🌐 Real-world Azure identity security implementation  
- 🔐 Zero Trust principles in practice  
- 🚨 Protection against risky sign-ins & attacks  
- 👤 Identity hardening (MFA, CA, RBAC, PIM)  
- 🛡 Enterprise-grade Conditional Access architecture  

---

## 📸 Screenshots Provided

Located in `/screenshots/`:
- Conditional Access policies list  
- MFA enforcement  
- Identity Protection alerts  
- RBAC & PIM configuration  

---

## 📫 Contact  
📧 ahmadousaidou1557@gmail.com  
🌐 LinkedIn – https://www.linkedin.com/in/ahmadou-saidou-abdou-240a08223/  
💼 Upwork – https://www.upwork.com/freelancers/~018bd643fea08898d1
