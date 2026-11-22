<!--
SPDX-License-Identifier: AGPL-3.0-or-later
Commercial license available
© Concepts 1996–2026 Miroslav Šotek. All rights reserved.
© Code 2020–2026 Miroslav Šotek. All rights reserved.
ORCID: 0009-0009-3560-0851
Contact: www.anulum.li | protoscience@anulum.li
SC-NC-STUDIO — repository foundation
-->

# Architecture

## Current executable surface

The checkout contains:
- repository validation tooling;
- dedicated tests;
- workflow definitions;
- native documentation.

No domain component of SC-NC Studio is implemented yet, and no code has moved here from SC-NeuroCore. The metadata keeps domain capabilities, claims and qualified record formats empty.

## Intended records

1. **Session:** A studio session: who reviewed what, which records were shown and which actions were taken.

## Ownership

**This project owns** the planned SC-NC Studio records and boundary rules.

**Owned elsewhere:**

| Responsibility | Owner |
|---|---|
| evidence manifest schema bytes | Evidence Manifest Toolkit |
| acceptance reports | Circuit Acceptance |
| the experiment record | Experiment Ledger |
| the public package, documentation and releases of the monolith | SC-NeuroCore |

## Interpretation

- **Views.** A dashboard shows records; it does not add evidence to them.
- **Moves.** Code arrives only through SC-NeuroCore's split import gate, unit by unit; a planned move is not a moved capability.

Read [the documentation architecture](docs/ARCHITECTURE.md) for the planned records, rules and schema identifiers.
