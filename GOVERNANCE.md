# Governance

## Overview

The UCCO standard is maintained by the UCCO Foundation as an open, vendor-neutral specification. This document describes how decisions are made, how the specification evolves, and how the editorial process works.

## Principles

**Open development.** All specification work happens in public. Discussions, proposals, reviews, and editorial decisions are visible to anyone. There are no private channels where normative decisions are made.

**Rough consensus.** We follow the IETF's model of rough consensus. Decisions are made when the community has had sufficient opportunity to comment and the editorial team determines that the direction has broad support. Unanimity is not required; unresolved objections are documented.

**Running code.** Implementation experience carries weight. A proposal backed by a working implementation that demonstrates the need is stronger than a theoretical argument alone.

**Stability.** The specification provides a stable foundation for implementers. Breaking changes require clear justification, a transition path, and sufficient notice.

## Roles

### Editorial team

The editorial team is responsible for the technical integrity and consistency of the specification. They:

- Review and merge changes to the specification
- Resolve editorial disputes
- Maintain the normative language and structural conventions
- Determine when the specification is ready for a version increment
- Coordinate the publication process

The editorial team currently consists of the founding contributors. As the community grows, additional editors will be appointed based on sustained, high-quality contributions to the specification.

### Contributors

Anyone who participates in discussions, opens issues, reviews pull requests, or submits changes is a contributor. Contributors do not need any formal role to participate — the process is open to all.

### Implementers

Organisations and individuals who build conforming implementations of the UCCO standard. Implementer feedback is given particular weight in editorial decisions, as they have direct experience with the specification's practical implications.

## Specification lifecycle

### Drafts

Working drafts are published in this repository. They represent the current state of editorial work and may change at any time. Drafts are numbered sequentially (v1.0, v1.1, v1.1 Rev2, etc.) and carry a "Draft" status marker.

### Candidate releases

When the editorial team determines that a draft is stable and ready for wider review, it is designated a Candidate Release. Candidate Releases are open for a minimum 30-day public comment period. Substantive issues raised during this period must be resolved before the specification advances.

### Published standards

A Candidate Release that has successfully completed public review and resolved all substantive issues becomes a Published Standard. Published Standards are versioned using semantic versioning (MAJOR.MINOR.PATCH).

- **MAJOR** — backward-incompatible changes to normative requirements
- **MINOR** — backward-compatible additions or clarifications
- **PATCH** — editorial corrections that do not change normative meaning

### Amendments

Between version increments, the editorial team may publish errata — a list of known errors and their corrections. Errata do not change the version number but are incorporated into the next published version.

## Decision process

1. **Proposal** — a change is proposed via GitHub Discussion or Issue
2. **Discussion** — the community comments; the editorial team may request additional information or implementation evidence
3. **Draft** — if the proposal has support, a pull request is submitted
4. **Review** — minimum 14-day review period for substantive changes
5. **Resolution** — the editorial team merges, requests changes, or closes with a documented rationale

Objections are taken seriously. If a contributor believes their objection has not been adequately addressed, they may request a formal response from the editorial team, which will be published in the issue or PR.

## Amendments to this governance document

This governance document may be updated by the editorial team. Substantive changes to governance follow the same review process as specification changes.
