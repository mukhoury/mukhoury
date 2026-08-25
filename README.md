# Hi, I'm Mukhtar Houry

**Identity & Access Management (IAM) Analyst** with 10+ years of hands-on experience in
identity lifecycle management, role-based access control (RBAC), and access governance
across enterprise retail, consulting, and financial services.

I'm now demonstrating that experience in modern tooling, building and documenting
reproducible IAM labs as case studies.

---

**Focus areas:** identity lifecycle (joiner / mover / leaver) · RBAC & least privilege ·
access reviews & certification · authentication vs. authorization · directory services (LDAP / Active Directory) ·
hybrid identity & directory synchronization

**Certifications:** CompTIA Security+ · ISC2 Certified in Cybersecurity (CC)
**Building toward:** Microsoft SC-300 (Identity & Access Administrator)

---

### Featured work

**[→ iam-portfolio](https://github.com/mukhoury/iam-portfolio)** hands-on IAM labs
documented as case studies (problem → solution → evidence).

- **[Lab 1](https://mukhoury.github.io/iam-portfolio/lab1/): Entra ID Dynamic Groups and Conditional Access.**
  Attribute-based dynamic security groups plus a Conditional Access policy enforcing MFA for
  all users, with a break-glass admin exclusion.
- **[Lab 2](https://mukhoury.github.io/iam-portfolio/lab2/): Identity Governance and Lifecycle Automation.**
  Entitlement management with approval-gated expiring access, fail-closed access reviews, PIM
  just-in-time admin, and joiner/leaver Lifecycle Workflows. Found a termination workflow that
  reported six of six tasks successful while leaving the user in a dynamic group, and an
  onboarding workflow that silently restored the access eight hours later.
- **[Lab 3](https://mukhoury.github.io/iam-portfolio/lab3/): Off-boarding Detection and Consent Auditing with PowerShell.**
  A Microsoft Graph PowerShell control that checks terminated identities against groups, licenses,
  and access package assignments, and hard-stops rather than returning a clean result when the
  session lacks the scope required to see termination data. Found that requesting read-only scopes
  does not produce a read-only session, because the token carries every permission the application
  was already consented for.
- **[Lab 4](https://mukhoury.github.io/iam-portfolio/lab4/): Hybrid Identity and Directory Synchronization.**
  An on-premises Active Directory forest synchronized to Entra ID with Entra Connect Sync. Established
  the on-premises directory as the source of authority, scoped synchronization by organizational unit as
  a security control, and found that disabling an account revokes sign-in while leaving its group
  entitlements and licenses intact, whereas moving it out of sync scope deletes the cloud identity
  outright.

---

**Connect:** [LinkedIn](https://www.linkedin.com/in/mh90/) · open to remote / Greater Los Angeles IAM roles
