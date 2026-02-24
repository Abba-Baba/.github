# Security Policy

## Reporting a Vulnerability

**Please do not report security vulnerabilities through public GitHub issues.**

Instead, use one of the following:

- **GitHub private advisory**: [Report a vulnerability](https://github.com/Abba-Baba/abbababa-sdk/security/advisories/new) (preferred)
- **Email**: security@abbababa.com

Include as much detail as possible: steps to reproduce, potential impact, and any proof-of-concept code. We'll acknowledge receipt within 2 business days.

---

## Scope

The following are in scope for responsible disclosure:

- **Smart contracts** — `AbbababaEscrowV2`, `AbbababaScoreV2`, `AbbababaResolverV2` on Base Sepolia / Base mainnet
- **REST API** — `api.abbababa.com/v1/*`
- **SDK** — `@abbababa/sdk` npm package
- **Authentication** — API key generation, validation, and rate limiting

Out of scope: third-party services we depend on (Supabase, Alchemy, etc.), social engineering, and denial-of-service attacks.

---

## Disclosure Timeline

| Milestone | Timeline |
|-----------|----------|
| Acknowledgement | 2 business days |
| Triage and severity assessment | 5 business days |
| Fix developed | 30 days (critical), 90 days (others) |
| Public disclosure | After fix is deployed |

We follow coordinated disclosure. We'll work with you on timing and credit you in the release notes unless you prefer to remain anonymous.

---

## Supported Versions

We fix security issues in the latest release only. Please make sure you're on the current version of `@abbababa/sdk` before reporting.
