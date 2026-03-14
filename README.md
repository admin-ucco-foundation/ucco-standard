# UCCO — Universal Capability Certification Object

**The open standard for cryptographic capability certification.**

UCCO defines how capability credentials are issued, verified, revoked, and audited — for both human and autonomous actors. Every certification carries cryptographic proof of who issued it, who holds it, and what they demonstrated.

> The internet moved data without knowing who sent it. UCCO moves capability with full knowledge of who holds it, what they're certified to do, and what they actually did.

## The Standard

| Document | Version | Status |
|---|---|---|
| [UCCO Standard](./UCCO-Standard-v1.1-Rev2-Draft.pdf) | v1.1 Rev2 | Draft |

### Sections

1. **Scope** — what UCCO covers and what it doesn't
2. **Normative References** — external standards UCCO depends on
3. **Terms and Definitions** — canonical vocabulary
4. **UCCO Data Model** — the certification object structure
5. **Cryptographic Operations** — signing, chain hashing, verification
6. **Lifecycle Management** — issuance, renewal, transfer
7. **Revocation and Expiry** — how credentials die
8. **Conformance Requirements** — what "UCCO-conforming" means

## Quick Start

Read the standard. That's it. UCCO is a specification, not a software library.

If you're building a conforming implementation:

1. Read the full standard document
2. Implement the data model (Section 4)
3. Implement the cryptographic operations (Section 5)
4. Pass the conformance requirements (Section 8)

## Participate

UCCO is developed in the open. Everyone can contribute.

- **[Discussions](https://github.com/admin-ucco-foundation/ucco-standard/discussions)** — ask questions, propose ideas, share feedback
- **[Issues](https://github.com/admin-ucco-foundation/ucco-standard/issues)** — report problems or request changes to the spec
- **[Pull Requests](https://github.com/admin-ucco-foundation/ucco-standard/pulls)** — propose edits to the standard

See [CONTRIBUTING.md](./CONTRIBUTING.md) for guidelines.

## Governance

The UCCO Foundation maintains this standard as a public good. The foundation is independent of any single implementation.

## License

The UCCO standard document is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).

Reference implementations and test suites (when published) will be licensed under the Apache License 2.0.

## Links

- **Website:** [ucco.foundation](https://ucco.foundation)
- **Contact:** admin@ucco.foundation
