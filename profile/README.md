# VERIFRAX

Deterministic verification, governed execution, explicit authority, and irreversible evidence finality.

This organization profile routes readers across the governed VERIFRAX repository and host perimeter while preserving role separation between chambers, hosts, publication surfaces, documentation surfaces, archive/reference surfaces, and intake.

## Public hosts

* `auctoriseal.verifrax.net` — authority issuance and authority reference surface
* `corpiform.verifrax.net` — governed execution and receipt surface
* `proof.verifrax.net` — public proof publication surface
* `verify.verifrax.net` — public verifier surface
* `sigillarium.verifrax.net` — seal archive and reference surface
* `docs.verifrax.net` — explanatory documentation surface
* `apply.verifrax.net` — intake surface

## Live chamber topology

```text
SYNTAGMARIUM = law
ORBISTIUM    = state
CONSONORIUM  = reconciliation
TACHYRIUM    = cognition
AUCTORISEAL  = authority
CORPIFORM    = execution
VERIFRAX     = verification
ANAGNORIUM   = terminal recognition
REGRESSORIUM = terminal recourse
```
## Chamber stack vs implementation strata

Read these as two different public classes:

### Chambers

- `SYNTAGMARIUM` — law
- `ORBISTIUM` — state
- `CONSONORIUM` — reconciliation
- `TACHYRIUM` — cognition
- `AUCTORISEAL` — authority
- `CORPIFORM` — execution
- `VERIFRAX` — verification
- `ANAGNORIUM` — terminal recognition
- `REGRESSORIUM` — terminal recourse

### Implementation, host, and support strata

- `VERIFRAX-WWW` — public root host
- `VERIFRAX-API` — API host implementation surface
- `VERIFRAX-STATUS` — status host implementation surface
- `VERIFRAX-SURFACE` — shared public-surface system
- `VERIFRAX-SPEC` — derived specification publication
- `VERIFRAX-DOCS` — explanatory docs
- `VERIFRAX-PROFILES` — deterministic profile constraints
- `VERIFRAX-verify` — public verification repository and UI boundary
- `proof` — proof publication
- `SIGILLARIUM` — archive/reference
- `apply` — intake

These implementation, host, and support repositories are not parallel sovereignty.
They must not be read as law, state, reconciliation, cognition, authority, execution, verification, terminal recognition, or terminal recourse merely because they are public-facing.

## Authority direction

* `VERIFRAX` authors normative source material.
* `VERIFRAX-SPEC` publishes derived specification artifacts from `VERIFRAX`.
* `VERIFRAX-PROFILES` constrains interpretation without rewriting the specification.
* Derived artifacts are not upstream authority.
* Governance authority is external and binds through `AUCTORISEAL` plus the governed repository set declared in `.github`.

## Surface boundaries

* Authority is issued in `AUCTORISEAL`, not in `VERIFRAX`, `proof`, or `verify`.
* Governed execution occurs in `CORPIFORM`, not in `apply`, `docs`, or `SIGILLARIUM`.
* Public proof publication occurs in `proof`, not in `VERIFRAX-verify`.
* Public verification occurs in `VERIFRAX-verify`, not in `proof`.
* Seal/archive reference lives in `SIGILLARIUM`, not in the evidence root of record.
* Intake starts at `apply`, not at `proof`, `verify`, `docs`, or execution surfaces.

## Start here

* [`VERIFRAX`](https://github.com/Verifrax/VERIFRAX) — authored protocol and evidence boundary
* [`AUCTORISEAL`](https://github.com/Verifrax/AUCTORISEAL) — authority issuance
* [`CORPIFORM`](https://github.com/Verifrax/CORPIFORM) — governed execution
* [`VERIFRAX-verify`](https://github.com/Verifrax/VERIFRAX-verify) — public verification
* [`proof`](https://github.com/Verifrax/proof) — proof publication
* [`VERIFRAX-DOCS`](https://github.com/Verifrax/VERIFRAX-DOCS) — explanatory docs

## Current reading rule

Read hosts and repositories by owned role, not by naming similarity.

If a repository or host starts sounding like authority, execution, proof publication, verification, archive, docs, and intake at the same time, the boundary is already broken.

## Boundary

This repository owns the Verifrax public organization profile surface.

It defines public perimeter reading order, top-level organization presentation, and repository-routing context for public readers.

It is not constitutional law.
It is not canonical world-state.
It is not reconciliation.
It is not sovereign cognition.
It is not authority issuance.
It is not execution.
It is not verification.
It is not proof publication.
It is not intake.

## Not this

This repository is not the constitutional source of truth.
This repository is not canonical world-state.
This repository is not reconciliation machinery.
This repository is not sovereign cognition.
This repository is not authority issuance.
This repository is not execution.
This repository is not verification.
This repository is not proof publication.
This repository is not intake.

## Public npm package order

Package classification rule:

- `@verifrax/verifrax-api` is a machine-interface / implementation package, not a protocol-sovereign package.
- `@verifrax/root` is an implementation package only if retained as a real installable boundary.
- Sovereign chambers do not become packages merely because they are public and important.

The canonical public package surface is read in this exact stack order. GitHub Packages is a distribution index, not the constitutional stack-order surface:

1. [`@verifrax/verifrax`](https://github.com/orgs/Verifrax/packages/npm/package/verifrax) — normative protocol surface
2. [`@verifrax/verifrax-verify`](https://github.com/orgs/Verifrax/packages/npm/package/verifrax-verify) — public verifier surface
3. [`@verifrax/verifrax-spec`](https://github.com/orgs/Verifrax/packages/npm/package/verifrax-spec) — formal specification surface
4. [`@verifrax/verifrax-profiles`](https://github.com/orgs/Verifrax/packages/npm/package/verifrax-profiles) — deterministic profile surface
5. [`@verifrax/auctoriseal`](https://github.com/orgs/Verifrax/packages/npm/package/auctoriseal) — authority issuance
6. [`@verifrax/corpiform`](https://github.com/orgs/Verifrax/packages/npm/package/corpiform) — governed execution
7. [`@verifrax/cicullis`](https://github.com/orgs/Verifrax/packages/npm/package/cicullis) — enforcement boundary
8. [`@verifrax/sigillarium`](https://github.com/orgs/Verifrax/packages/npm/package/sigillarium) — seal/archive reference
9. [`@verifrax/archicustos`](https://github.com/orgs/Verifrax/packages/npm/package/archicustos) — custody-preservation primitive
10. [`@verifrax/attestorium`](https://github.com/orgs/Verifrax/packages/npm/package/attestorium) — attestation primitive
11. [`@verifrax/guillotine`](https://github.com/orgs/Verifrax/packages/npm/package/guillotine) — terminal cutoff primitive
12. [`@verifrax/irrevocull`](https://github.com/orgs/Verifrax/packages/npm/package/irrevocull) — irreversible judgment primitive
13. [`@verifrax/kairoclasp`](https://github.com/orgs/Verifrax/packages/npm/package/kairoclasp) — temporal boundary primitive
14. [`@verifrax/limenward`](https://github.com/orgs/Verifrax/packages/npm/package/limenward) — threshold / boundary primitive
15. [`@verifrax/originseal`](https://github.com/orgs/Verifrax/packages/npm/package/originseal) — origin / provenance primitive
16. [`@verifrax/validexor`](https://github.com/orgs/Verifrax/packages/npm/package/validexor) — verification primitive

This is the public package order. Repository topology, host topology, and package topology are not interchangeable surfaces.
