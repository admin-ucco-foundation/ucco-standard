# Security Policy

## Reporting a vulnerability

The UCCO specification defines cryptographic operations and security-critical data structures. We take security issues seriously.

If you discover a vulnerability in the specification itself — such as a weakness in the cryptographic construction, a flaw in the chain hashing scheme, or an attack vector against the dual-key architecture — please report it responsibly.

**Do not open a public issue for security vulnerabilities.**

Instead, email **security@ucco.foundation** with:

- A description of the vulnerability
- The affected section(s) of the specification
- Steps to reproduce or a proof of concept, if applicable
- Your assessment of severity and potential impact

We will acknowledge receipt within 48 hours and provide an initial assessment within 7 business days.

## Scope

This policy covers the UCCO specification and any reference materials published in this repository. It does not cover third-party implementations of the UCCO standard — please report those to the respective implementation maintainers.

## Recognition

We gratefully acknowledge security researchers who report vulnerabilities responsibly. With your permission, we will credit you in the security advisory and in the specification's acknowledgements section.

## Disclosure timeline

We follow a coordinated disclosure approach:

1. Report received and acknowledged (48 hours)
2. Initial assessment and severity determination (7 days)
3. Fix developed and reviewed (timeline varies by severity)
4. Advisory published with fix
5. Public disclosure

For critical vulnerabilities in the cryptographic construction, we will coordinate with known implementers before public disclosure.
