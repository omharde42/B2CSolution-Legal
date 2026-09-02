# B2C Solution — Access Control Policy

**Effective Date:** 22 August 2026
**Last Updated:** 22 August 2026
**Version:** 1.0
**Organization:** B2C Solution

---

## 1. Purpose

The purpose of this Access Control Policy is to establish standards for managing access to **B2C Solution** systems, source code repositories, databases, cloud infrastructure, communication tools, and administrative accounts.

As an early-stage startup, B2C Solution relies on simple, effective, and secure access controls to protect company assets, client data, and system integrity without imposing unnecessary bureaucracy.

---

## 2. Scope

This policy applies to:

- Founders, co-founders, team members, contractors, and contributors;
- Source code repositories (e.g., GitHub organization and repositories);
- Cloud hosting, domain registrars, and server infrastructure;
- Communication and project management platforms;
- Business email and administrative accounts;
- Third-party SaaS tools and services.

---

## 3. Core Access Control Principles

B2C Solution follows three fundamental access control principles:

1. **Least Privilege:** Individuals are granted only the minimum level of access necessary to perform their assigned responsibilities.
2. **Need-to-Know:** Access to sensitive data or systems is provided strictly on a need-to-know basis.
3. **Role-Based Provisioning:** Access rights are assigned based on defined roles rather than ad-hoc requests.

---

## 4. Key Leadership Roles & Key Contacts

Administrative ownership and ultimate system control rest with company leadership:

- **Founder:** Om Harde (`omharde42-dev`)
- **Co-Founder:** Purvesh Bhadale
- **Social Media Handler:** Raj Bonlawar
- **Official Contact Email:** b2csolution2436@gmail.com
- **Website:** https://b2csolutionseller.lovable.app

---

## 5. Account and Password Security

To maintain account security, all personnel and contributors with access to B2C Solution systems must adhere to the following:

- **Multi-Factor Authentication (MFA):** MFA must be enabled on all accounts where supported, particularly GitHub, primary email, domain registrars, and cloud hosting accounts.
- **Strong Passwords:** Passwords must be unique, complex, and managed preferably via a secure password manager.
- **No Shared Credentials:** Individual accounts must be used whenever possible. Shared administrative credentials must be avoided.
- **No Hardcoded Credentials:** Passwords, API keys, private tokens, or database credentials must never be committed to source code or public repositories.

---

## 6. Repository and Code Access

- **Public Repositories:** Maintained for public documentation, legal frameworks, and open-source projects. Write access is restricted to authorized maintainers.
- **Private Repositories:** Client projects and proprietary source code are maintained in private repositories. Access is granted specifically to assigned team members.
- **Branch Protection:** Main and production branches must use branch protection wherever the platform supports it, including mandatory code review or pull request approval before merging. An emergency bypass must be approved and documented, limited to the duration of the emergency, followed by review of the change by the next business day, and removed immediately when the emergency ends.

---

## 7. Onboarding and Access Provisioning

When a new team member, contractor, or contributor joins B2C Solution:

1. The Founder or Co-Founder approves the required access level.
2. Accounts are provisioned using official business emails or verified GitHub usernames.
3. MFA is verified prior to granting repository write access.
4. The contributor is briefed on applicable security policies (`security/SECURITY_POLICY.md`).

---

## 8. Offboarding and Access Revocation

When a contributor or team member leaves B2C Solution or changes roles:

1. Privileged access to GitHub repositories, cloud infrastructure, and administrative accounts must be revoked immediately upon departure. A lower-risk, non-privileged account may be revoked within 24 hours only under a documented exception approved by the Founder or Co-Founder that identifies an owner, deadline, and compensating controls.
2. Any shared credentials or SSH keys associated with the individual must be rotated.
3. Access rights are reviewed to ensure no residual access remains.

---

## 9. Third-Party and Client Access

- **Third-Party Services:** Third-party integrations or APIs must use restricted service tokens with minimal required permissions.
- **Client Access:** Clients may be granted read or demonstration access to staging environments or designated repositories as defined in the `legal/CLIENT_SERVICE_AGREEMENT.md`.

---

## 10. Access Review and Monitoring

- Access lists for GitHub repositories, hosting environments, and core tools will be reviewed periodically (at least twice per year or as team composition changes).
- Suspicious login attempts or unauthorized access attempts must be reported according to `security/INCIDENT_RESPONSE_POLICY.md`.

---

## 11. Policy Compliance and Contact

Failure to follow access control standards may result in suspension or revocation of access permissions.

For questions or access requests, contact:

**Organization:** B2C Solution
**Email:** b2csolution2436@gmail.com
**Website:** https://b2csolutionseller.lovable.app

---

## 12. Document Information

| Field | Information |
|---|---|
| Document | Access Control Policy |
| Organization | B2C Solution |
| Version | 1.0 |
| Effective Date | 22 August 2026 |
| Status | Active |
| Review Cycle | Annual / Operational Updates |
| Document Owner | B2C Solution |

---

## Disclaimer

This Access Control Policy outlines internal security procedures appropriate for an early-stage startup. It should be adapted as team size, system complexity, and client requirements grow.

**© 2026 B2C Solution. All rights reserved.**
