<h1 align="center">Hey, I'm Abner Peña 👋</h1>
<h3 align="center">IAM & Cloud Security Engineer · Azure AD / Entra ID · PowerShell · Endpoint Security</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/abner-pena/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-abner--pena-0077B5?style=flat&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:abner.pena97@gmail.com">
    <img src="https://img.shields.io/badge/Email-abner.pena97%40gmail.com-D14836?style=flat&logo=gmail&logoColor=white" />
  </a>
  <img src="https://img.shields.io/badge/Security%2B-In%20Progress-yellow?style=flat&logo=comptia" />
  <img src="https://img.shields.io/badge/SC--300-Planned%20Sep%202026-blue?style=flat&logo=microsoft" />
  <img src="https://img.shields.io/badge/Open%20to-Remote%20W2%20Roles-brightgreen?style=flat" />
</p>

---

## About Me

IAM and Cloud Security Engineer with hands-on enterprise experience in **Azure AD / Entra ID**, identity lifecycle management, endpoint security, and PowerShell automation.

At **YNAP (Yoox Net-A-Porter)**, I administer Azure AD / Entra ID with MFA and Conditional Access, managed DLP/GDPR compliance across NA/EU/APAC, and led a 400+ machine Windows 11 migration. I've automated 1,000+ user accounts via PowerShell and built identity and cloud infrastructure from scratch.

Currently pursuing **CompTIA Security+** (Aug 2026) and **SC-300: Microsoft Identity & Access Administrator** (Sep 2026). Targeting a fully remote IAM or Cloud Security Engineer role.

---

## 🔐 Identity & Access Management

| Project | What I Built | Stack |
|---|---|---|
| [Phishing-Resistant MFA Lab](https://github.com/abner-pena/mfa-phishing-resistance-lab) | Entra ID migration off phishable factors onto FIDO2, Windows Hello, and certificate-based auth: a custom Conditional Access authentication strength, number matching to kill MFA fatigue, AAGUID key allowlisting, a coverage-gated retirement of SMS and voice, and KQL detections for legacy-method sign-ins, prompt bombing, and policy blocks | Entra ID · Authentication Strengths · FIDO2/WebAuthn · Graph PowerShell |
| [Identity Governance & Access Reviews](https://github.com/abner-pena/identity-governance-access-reviews) | Entra ID Governance build: access packages with two-stage approval and 90 day expiry, separation-of-duties incompatible packages, recurring group, package, and guest access reviews with auto-apply removal, plus Graph reporting and KQL audit queries for grants, review decisions, and SoD denials | Entra ID Governance · Entitlement Management · Access Reviews · Graph PowerShell |
| [Privileged Access Workstation](https://github.com/abner-pena/privileged-access-workstation) | Tier 0 PAW build guide: AppLocker allowlisting, Credential Guard, zero cached credentials, ASR rules, outbound default-deny firewall, plus a Conditional Access policy enforcing PAW-only privileged sign-in and a PowerShell compliance auditor | Windows 11 · AppLocker · Credential Guard · Conditional Access |
| [SAML vs OIDC SSO Lab](https://github.com/abner-pena/saml-oidc-sso-lab) | Side-by-side federation protocol lab in Entra ID: SAML enterprise app with custom claims mapping, OIDC app registration via Graph PowerShell, annotated token teardowns, cert expiry monitoring, and AADSTS failure triage scripts | Entra ID · SAML 2.0 · OIDC/OAuth 2.0 · Graph PowerShell |
| [Zero Trust Architecture Lab](https://github.com/abner-pena/zero-trust-architecture-lab) | Zero Trust reference build in Azure: Conditional Access policy set (phishing-resistant MFA, legacy auth block, device compliance, risk-based), segmented VNet with default-deny NSGs, and KQL detections for policy bypass and tampering | Entra ID · Conditional Access · Azure NSGs · KQL |
| [Okta Lifecycle Management](https://github.com/abner-pena/okta-lifecycle-management) | Full joiner-mover-leaver automation: CSV-driven provisioning, attribute-based group rules, SCIM 2.0 app provisioning, and two-stage deprovisioning with audit reporting | Okta · SCIM 2.0 · PowerShell · Universal Directory |
| [Azure PIM Lab](https://github.com/abner-pena/azure-pim-lab) | Privileged Identity Management: eligible role assignments, MFA-gated activation, approval workflows, quarterly access reviews, and audit KQL queries | Entra ID · PIM · Graph API · PowerShell |
| [PowerShell AD Automation](https://github.com/abner-pena/powershell-ad-automation) | 3 production scripts: bulk user provisioning from CSV, inactive account deprovisioning with quarantine, and full access audit reporting | PowerShell · AD DS · RBAC |
| [Azure Entra ID Lab](https://github.com/abner-pena/azure-entra-id-lab) | Conditional Access policies, MFA enforcement, SSPR, device compliance, and legacy auth blocking, with importable JSON policy templates | Entra ID · Intune · Graph API |
| [Configuring Active Directory in Azure](https://github.com/abner-pena/Configuring-Active-Directory-within-Azure-VMs) | Full AD domain from scratch: DCs, OUs, GPOs, user lifecycle, PowerShell bulk provisioning | Azure VMs · AD DS · PowerShell |
| [Network File Shares and Permissions](https://github.com/abner-pena/Network-File-Shares-and-Permissions-with-Active-Directory) | RBAC-based file share access control using AD groups and permission inheritance | Active Directory · RBAC · Windows Server |

---

## 🛡️ Security Operations

| Project | What I Built | Stack |
|---|---|---|
| [Microsoft Sentinel SIEM Lab](https://github.com/abner-pena/microsoft-sentinel-siem-lab) | Full SIEM deployment: log ingestion from Entra ID, 4 KQL detection queries (brute force, impossible travel, privileged activity, new admin alerts), and scheduled analytic rules | Sentinel · KQL · Log Analytics |

---

## ☁️ Cloud Infrastructure

| Project | What I Built | Stack |
|---|---|---|
| [Azure Network Protocols Lab](https://github.com/abner-pena/azure-network-protocols) | NSG rule configuration and live network traffic inspection across RDP, SSH, DNS, ICMP | Azure · NSGs · Wireshark |
| [Azure Virtual Machine Setup](https://github.com/abner-pena/Virtual-Machine) | Foundation lab: provisioning and configuring Azure VMs for identity and cloud infra work | Azure · Windows Server |

---

## 📓 Daily Study Log

[![Daily Commits](https://img.shields.io/badge/Study%20Log-Daily%20Commits-6f42c1?style=flat&logo=github)](https://github.com/abner-pena/daily-security-log)

Active cert prep logged daily in [`daily-security-log`](https://github.com/abner-pena/daily-security-log). Rotating through 14 IAM and Security+ concepts: Conditional Access, PIM, Zero Trust, RBAC, Hybrid Identity, Entra ID Protection, and more.

---

## 🧰 Core Stack

```
Identity & Access    Azure AD / Entra ID · Active Directory · Okta · Duo MFA · SSO · RBAC · Conditional Access · PIM
Cloud                Azure (VMs, VNets, NSGs) · DNS · DHCP · VPN · VDI · Microsoft Sentinel
Device Management    SCCM · Jamf Pro · Intune · AirWatch · iOS/Android MDM · OS Imaging
Security             DLP · GDPR · BitLocker · Zscaler · Endpoint Security · MFA · Firewall Policies · KQL
Automation           PowerShell · AD Lifecycle Scripting · Bulk Provisioning · GitHub Actions
```

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://streak-stats.demolab.com?user=abner-pena&theme=dark&hide_border=true&background=0d1117" />
</p>

---

## 🎫 IT Operations

| Project | What I Built |
|---|---|
| [osTicket: Installation](https://github.com/abner-pena/osticket-prereqs) | Full helpdesk stack on Azure (IIS, MySQL, PHP) |
| [osTicket: Configuration](https://github.com/abner-pena/osticket-post-install-config) | Roles, departments, SLAs, help topics |
| [osTicket: Ticket Lifecycle](https://github.com/abner-pena/ticket-lifecycle) | End-to-end ticket workflow simulation |

---

<p align="center">
  <i>Open to fully remote IAM & Cloud Security Engineer roles · English / Spanish · Saddle Brook, NJ</i>
</p>
