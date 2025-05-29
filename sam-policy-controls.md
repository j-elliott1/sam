# Software Asset Management (SAM) Policy Controls

## 1. Objective
Establish a governance framework for managing software assets securely and efficiently across their lifecycle.

## 2. Key Control Areas
- **License Compliance**: Maintain records of valid entitlements and usage.
- **Entitlement Management**: Ensure users receive only what they are licensed for.
- **Usage Monitoring**: Track active vs. inactive installations.
- **Renewal Tracking**: Automated reminders and risk alerts for renewals.
- **Unauthorized Software Control**: Detect and remediate shadow IT.
- **Access Management**: Restrict software admin rights and install privileges.

## 3. Control Enforcement Methods
| Control | Method | Owner |
|--------|--------|-------|
| License validation | SCCM/Intune scans | SAM Manager |
| Role-based provisioning | ITSM workflows | IAM Team |
| Alert thresholds | SAM tool rules | IT Security |
| Quarterly audits | Internal review checklist | Internal Audit |

## 4. Regulatory Alignment
- ISO 19770-1 (ITAM Governance)
- NIST CSF
- HIPAA (if applicable)
- GDPR (for user privacy in software telemetry)

## 5. Risk Considerations
- Over-licensing costs
- Legal penalties due to non-compliance
- Data leakage from unmanaged software
- Redundant or outdated tools impacting performance

## 6. Review & Audit Schedule
- Controls reviewed bi-annually.
- Audit findings documented and tracked to resolution.

## 7. Version History
| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0     | 2025-05-29 | Julia Elliott | Initial draft |
