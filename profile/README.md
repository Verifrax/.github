# VERIFRAX

Deterministic verification, governed execution, and irreversible evidence finality.

VERIFRAX is a protocol stack for binding authority, execution, and verification into auditable public surfaces.

## Core public surfaces

- **[VERIFRAX](https://github.com/Verifrax/VERIFRAX)** — canonical protocol, evidence index, and verification boundary
- **[AUCTORISEAL](https://github.com/Verifrax/AUCTORISEAL)** — authority sealing and issuance boundary
- **[CORPIFORM](https://github.com/Verifrax/CORPIFORM)** — authority-governed execution and receipt boundary

## Stack model

- **Authority** → AUCTORISEAL issues explicit authority objects
- **Execution** → CORPIFORM executes or refuses under that authority
- **Verification** → VERIFRAX records evidence, evaluates claims, and preserves finality boundaries

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

## Public links

- Website: **https://www.verifrax.net/**
- Protocol contact: **protocol@verifrax.net**

## Orientation

Start with the canonical protocol repository:

- **[github.com/Verifrax/VERIFRAX](https://github.com/Verifrax/VERIFRAX)**

Then inspect the authority and execution layers:

- **[github.com/Verifrax/AUCTORISEAL](https://github.com/Verifrax/AUCTORISEAL)**
- **[github.com/Verifrax/CORPIFORM](https://github.com/Verifrax/CORPIFORM)**

Deterministic verification. One execution. Final evidence.
