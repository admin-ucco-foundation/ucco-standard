# Contributing to UCCO

Thank you for your interest in contributing to the Universal Capability Certification Object standard.

UCCO is developed in the open. The specification, governance, and editorial process are all public. We welcome contributions from anyone — whether you're building a conforming implementation, work in a regulated industry, or have expertise in cryptography, identity systems, or standards development.

## How to contribute

### Join the conversation

The best place to start is [GitHub Discussions](https://github.com/ucco-foundation/ucco-standard/discussions). Ask questions, share ideas, or provide feedback on the current draft. No contribution is too small — a question about unclear wording often leads to a meaningful improvement.

### Report an issue

If you find an error, inconsistency, or ambiguity in the specification, please [open an issue](https://github.com/ucco-foundation/ucco-standard/issues). Use the provided templates to help us understand and address your concern efficiently.

When reporting issues, please include:

- The section and clause number in the specification
- A clear description of the problem
- If applicable, a suggested correction or improvement

### Propose a change

Substantive changes to the specification follow a structured process:

1. **Open a discussion** describing the change you'd like to propose and the reasoning behind it. This allows the community to provide feedback before you invest time in drafting.
2. **Draft the change** as a pull request against the current working draft. Reference the discussion in your PR description.
3. **Editorial review** — the editorial team will review for consistency with the existing specification, normative language conventions (RFC 2119), and technical accuracy.
4. **Community review** — substantive changes are open for community comment for a minimum of 14 days.
5. **Resolution** — the editorial team incorporates feedback and either merges, requests revision, or closes with explanation.

### Editorial conventions

The UCCO specification follows these conventions:

- Normative keywords (MUST, MUST NOT, SHALL, SHOULD, MAY) are used in accordance with [RFC 2119](https://www.rfc-editor.org/rfc/rfc2119) and are capitalised when used in their normative sense.
- Section references use the format "Section N.N" with a capital S.
- JSON examples are illustrative unless explicitly marked as normative.
- Hash and key values in examples use placeholder notation (`{hash}`, `{key}`) rather than fabricated values.

### What we're looking for

We particularly welcome contributions in these areas:

- **Clarity improvements** — if something is hard to understand, it probably needs rewriting
- **Conformance test cases** — examples that exercise edge cases in the specification
- **Implementation experience** — reports from building conforming implementations, especially where the spec is ambiguous or underspecified
- **Security review** — analysis of the cryptographic operations and threat model
- **Interoperability considerations** — issues that arise when different implementations interact
- **Internationalisation** — considerations for deployment across jurisdictions and character sets

## What we won't accept

- Changes that break backward compatibility with the current draft without a compelling technical justification
- Additions that serve a single implementation's needs at the expense of generality
- Marketing language or promotional content
- Changes to normative sections without corresponding updates to the conformance requirements

## Code of conduct

All participants in the UCCO project are expected to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). We are committed to providing a welcoming and productive environment for everyone.

## Licensing

By contributing to this repository, you agree that your contributions will be licensed under the same terms as the project:

- Specification text: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
- Code, test suites, and tooling: [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)

## Questions

If you're unsure about anything, open a discussion or contact the editorial team at admin@ucco.foundation. There are no wrong questions.
