# VERIFRAX

Deterministic verification, governed execution, and irreversible evidence finality.

VERIFRAX is a protocol stack for binding authority, execution, and verification into auditable public surfaces.

## Core public surfaces

- **[VERIFRAX](https://github.com/Verifrax/VERIFRAX)** — authoring protocol surface, evidence index, and verification boundary
- **[AUCTORISEAL](https://github.com/Verifrax/AUCTORISEAL)** — authority sealing and issuance boundary
- **[CORPIFORM](https://github.com/Verifrax/CORPIFORM)** — authority-governed execution and receipt boundary

## Stack model

- **Authority** → AUCTORISEAL issues explicit authority objects
- **Execution** → CORPIFORM executes or refuses under that authority
- **Verification** → VERIFRAX records evidence, evaluates claims, and preserves finality boundaries

## Authority model

- **VERIFRAX** authors normative source material for the active repository interpretation boundary.
- **VERIFRAX-SPEC** publishes derived specification artifacts from VERIFRAX.
- Derived specification artifacts are not upstream repository authority.
- Governance authority is external and binds through AUCTORISEAL plus the governed repository set declared in **[Verifrax/.github](https://github.com/Verifrax/.github)**.

## Current public boundary

The currently established public boundary includes:

- bootstrap artifacts through **artifact-0004**
- recorded authority-governed CORPIFORM execution evidence
- recorded package publication surfaces for:
  - `@verifrax/auctoriseal`
  - `@verifrax/corpiform`

## Design constraints

- no authority, no execution
- no ambiguity, no execution
- no unsigned consequence, no acceptance
- no hidden mutation, no trust

## Orientation

Start with the authoring and verification surface:

- **[github.com/Verifrax/VERIFRAX](https://github.com/Verifrax/VERIFRAX)**

Then inspect the authority and execution layers:

- **[github.com/Verifrax/AUCTORISEAL](https://github.com/Verifrax/AUCTORISEAL)**
- **[github.com/Verifrax/CORPIFORM](https://github.com/Verifrax/CORPIFORM)**

Then inspect the derived publication and support surfaces:

- **[github.com/Verifrax/VERIFRAX-SPEC](https://github.com/Verifrax/VERIFRAX-SPEC)**
- **[github.com/Verifrax/VERIFRAX-PROFILES](https://github.com/Verifrax/VERIFRAX-PROFILES)**
- **[github.com/Verifrax/VERIFRAX-SAMPLES](https://github.com/Verifrax/VERIFRAX-SAMPLES)**
- **[github.com/Verifrax/VERIFRAX-DOCS](https://github.com/Verifrax/VERIFRAX-DOCS)**
- **[github.com/Verifrax/VERIFRAX-verify](https://github.com/Verifrax/VERIFRAX-verify)**
