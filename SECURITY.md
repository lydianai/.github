# Security Policy

## Supported Versions

| Version | Supported |
|---------|-----------|
| Latest release | Yes |
| Previous minor | Security patches only |
| Older | No |

## Reporting a Vulnerability

We take security seriously. If you discover a security vulnerability in any of our repositories, please report it responsibly.

### How to Report

1. **DO NOT** create a public GitHub issue for security vulnerabilities.
2. Use [GitHub Private Vulnerability Reporting](https://github.com/lydianai/borsa/security/advisories/new) to submit your report directly.
3. Alternatively, email **sardagemrah@gmail.com** with the subject line `[SECURITY]` and include:
   - Description of the vulnerability
   - Steps to reproduce
   - Potential impact assessment
   - Any suggested fixes (optional)

### What to Expect

| Stage | Timeline |
|-------|----------|
| Acknowledgment | Within 48 hours |
| Initial Assessment | Within 5 business days |
| Critical Fix | Within 7 days |
| High Severity Fix | Within 30 days |
| Medium Severity Fix | Within 90 days |
| Coordinated Disclosure | After fix is deployed |

### Scope

**In scope:**
- Application code vulnerabilities
- Authentication and authorization flaws
- Data exposure or injection issues
- Configuration and deployment security
- Dependencies with known CVEs

**Out of scope:**
- Social engineering attacks
- Volumetric denial-of-service
- Issues in third-party services (report to the respective maintainer)
- Findings from automated scanners without verified impact

### Recognition

Responsible reporters will be credited in our security acknowledgments (unless anonymity is preferred).

## Security Standards

All repositories under this account follow:

- OWASP Top 10 compliance
- Signed commits enforcement
- Automated dependency scanning (Dependabot)
- Static analysis via CodeQL
- Secret scanning with push protection enabled
