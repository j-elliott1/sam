# Software Asset Management (SAM) Risk Register

This Risk Register is part of the **IT Asset & Risk Management Suite** and focuses on identifying, assessing, and mitigating risks within the Software Asset Management (SAM) lifecycle.  
It should be reviewed regularly and updated following audits, renewals, or key project milestones.

---

## Register Overview

| **Field** | **Description** |
|------------|-----------------|
| **Project/Repo Name** | IT Asset & Risk Management Suite |
| **Function** | Software Asset Management (SAM) |
| **Owner** | SAM Program Manager / ITAM Lead |
| **Last Updated** | _YYYY-MM-DD_ |
| **Version** | v1.0 |

---

## Risk Log

| ID | Risk Description | Category | Likelihood | Impact | Risk Rating (L×I) | Mitigation Strategy | Contingency Plan | Owner | Status | Review Date |
|----|------------------|-----------|-------------|---------|-------------------|--------------------|------------------|--------|----------|--------------|
| SAM-01 | Missing or incomplete license documentation may lead to compliance penalties during audits. | Compliance | High | High | 9 | Maintain a centralized and version-controlled license repository. Perform quarterly reconciliations. | Engage vendor or auditor to resolve discrepancies quickly. | SAM Analyst | Open | 2025-11-01 |
| SAM-02 | Expired vendor contracts or unnoticed auto-renewals could result in budget overruns. | Contractual | Medium | High | 8 | Implement renewal tracking with 90-day notifications. | Negotiate short-term extension to maintain coverage. | Procurement / SAM Lead | Monitoring | 2025-11-15 |
| SAM-03 | Discovery tools fail to capture accurate installations, leading to data integrity issues. | Data Integrity | High | High | 9 | Validate discovery tool feeds (SCCM, Tanium, etc.) against HR and AD data. | Run manual spot checks quarterly. | ITAM Data Steward | Open | 2025-11-10 |
| SAM-04 | Vendor license terms not reviewed before deployment cause inadvertent overuse. | Licensing | High | Medium | 8 | Review and store all EULAs and terms in a shared repository. | Remove or reclassify affected software. | SAM Team | Open | 2025-11-20 |
| SAM-05 | Unauthorized software installs introduce security vulnerabilities. | Security | Medium | High | 8 | Use application whitelisting and SCCM baselines. | Quarantine or uninstall noncompliant software. | Security & SAM Teams | Mitigated | 2025-11-30 |
| SAM-06 | Lack of stakeholder engagement results in poor adoption of SAM processes. | Operational | Medium | Medium | 6 | Conduct training sessions and include stakeholders in license reviews. | Reinforce governance through leadership communications. | SAM Program Manager | Open | 2025-12-01 |
| SAM-07 | Inconsistent naming conventions and metadata across tools (SCCM, ServiceNow, vendor portals). | Data Integrity | Medium | Medium | 6 | Standardize naming via data dictionary and validation scripts. | Implement automated sync rules. | Data Management Lead | Open | 2025-12-10 |
| SAM-08 | Loss of key personnel leads to knowledge gaps in license management and reporting. | Resource / Operational | Low | High | 7 | Maintain process documentation and a shared SAM knowledge base. | Cross-train team members on key vendor portfolios. | SAM Manager | Monitoring | 2025-12-05 |
| SAM-09 | Vendor risk assessment not performed before purchase or renewal. | Vendor | Medium | High | 8 | Require vendor risk questionnaire and security review prior to onboarding. | Suspend transactions pending review. | Vendor Risk Officer | Open | 2025-11-25 |
| SAM-10 | Audit response delays due to missing or outdated entitlement data. | Compliance | Medium | High | 8 | Maintain an “audit-ready” evidence package per vendor. | Escalate to leadership with mitigation plan. | SAM Lead | Monitoring | 2025-11-22 |

---

## Risk Scoring Matrix

| **Likelihood** | **Impact** | **Score (L×I)** | **Risk Level** |
|----------------|-------------|------------------|----------------|
| 1 | 1–3 | 1–3 | Low |
| 2 | 4–6 | 4–6 | Medium |
| 3 | 7–9 | 7–9 | High |
| 4 | 10–12 | 10–12 | Very High |

> _Tip: Standardize likelihood and impact scoring across all ITAM functions (e.g., Hardware, Cloud, and Vendor)._

---

## Governance Notes

- **Review Frequency:** Monthly or after license renewals, vendor onboarding, or audits  
- **Data Sources:** SCCM, ServiceNow, Active Directory, Procurement, Contract Management  
- **Change Control:** Update version and commit date via Git after every modification  
- **References:**
  - ISO/IEC 19770-1:2017 — SAM Processes  
  - ITIL 4: Service Asset and Configuration Management  
  - NIST SP 800-53 — Risk Management Framework  

---

_© 2025 IT Asset & Risk Management Suite — Licensed under the [MIT License](../LICENSE)_
