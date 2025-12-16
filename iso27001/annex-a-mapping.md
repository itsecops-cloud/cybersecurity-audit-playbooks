# ISO 27001 Annex A Control Mapping

ISO/IEC 27001 Annex A provides a catalog of security controls that must be considered when implementing a compliant ISMS.

Below is a high-value mapping table correlating Annex A controls to typical technical and operational enforcement points.

| Annex A Control | Operational Mapping | Evidence |
|----------------|--------------------|----------|
| A.5.1 Information security policies | Policy repository | Latest policy version |
| A.8.1 Asset management | Asset inventory tool | Exported inventory |
| A.9.2 User access management | IAM logs | Role assignments & MFA logs |
| A.12.4 Logging & monitoring | SIEM / log retention | Alert history |
| A.14 System acquisition & dev | Change control | DevOps pipeline logs |
| A.18 Compliance | Internal audit reports | Non-conformance tracking |

This mapping helps reduce gaps between policy, operations, and audit evidence.

---

## Best Practices for Annex A Implementation

- Align Annex A controls to **risk treatment decisions**
- Maintain evidence retention schedules
- Use automation where possible for logging and alerting

ISO auditors evaluate both **design and operating effectiveness** — this mapping supports both aspects.

