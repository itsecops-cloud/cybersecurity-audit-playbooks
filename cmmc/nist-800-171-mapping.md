# NIST SP 800-171 Control Mapping

NIST SP 800-171 provides 110 security requirements across 14 control families.

Below is a condensed operational mapping for typical technical and SIEM environments.

| Control Family | Example Control | Operational Mapping |
|----------------|-----------------|---------------------|
| AC (Access Control) | AC-2 | IAM policies, MFA, role reviews |
| AU (Audit & Accountability) | AU-6 | Log collection, retention |
| IA (Identification & Auth) | IA-2 | MFA enforcement |
| SC (System & Comm Protec) | SC-8 | TLS/HTTPS enforcement |

Mapping operational sources to NIST requirements simplifies evidence collection.

---

## Best Practices

- Centralize logs for audit search
- Validate controls in isolation and at scale
- Document control exceptions and mitigating controls

