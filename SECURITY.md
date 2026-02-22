# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest release | ✅ Full support |
| Previous minor | 🔒 Security patches only |
| Older releases | ❌ No support |

## Reporting a Vulnerability

We take security seriously. If you discover a vulnerability in any AiLydian repository, please report it responsibly through our coordinated disclosure process.

### How to Report

1. **DO NOT** create a public GitHub issue for security vulnerabilities.
2. Use [GitHub Private Vulnerability Reporting](https://github.com/lydianai/.github/security/advisories/new) for any repository under this organization.
3. Alternatively, email **security@ailydian.com** with the subject line `[SECURITY] <repo-name>` and include:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact assessment
   - Affected version(s)
   - Any suggested fixes (optional)

### What to Expect

| Stage | Timeline |
|-------|----------|
| Acknowledgment | Within 24 hours |
| Initial Assessment | Within 3 business days |
| Critical Severity Fix | Within 7 days |
| High Severity Fix | Within 30 days |
| Medium Severity Fix | Within 90 days |
| Coordinated Disclosure | After fix is deployed |

### Severity Classification (CVSS v3.1)

| Score | Severity | Response SLA |
|-------|----------|--------------|
| 9.0–10.0 | Critical | 7 days |
| 7.0–8.9 | High | 30 days |
| 4.0–6.9 | Medium | 90 days |
| 0.1–3.9 | Low | Best effort |

### Scope

**In scope:**
- Application code vulnerabilities (all repositories)
- Authentication and authorization flaws
- Data exposure, injection, and XSS issues
- API security (IDOR, BOLA, mass assignment)
- Dependencies with known CVEs (CVSS ≥ 7.0)
- HIPAA/KVKK data handling violations

**Out of scope:**
- Social engineering attacks
- Volumetric denial-of-service (DoS/DDoS)
- Self-XSS requiring user interaction

## Security Standards

| Standard | Status |
|----------|--------|
| OWASP Top 10 | ✅ Enforced |
| Dependabot alerts | ✅ Enabled |
| CodeQL static analysis | ✅ Active |
| Secret scanning | ✅ Push protection ON |
| HIPAA/KVKK compliance | ✅ Healthcare repos |
| PCI DSS (SAQ-D) | ✅ FinTech repos |

## Contact

| Channel | Address |
|---------|---------|
| Security Reports | security@ailydian.com |
| Emergency (Critical) | security@ailydian.com — subject: `[CRITICAL]` |

