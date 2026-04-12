# VERIFRAX

Deterministic verification, governed execution, explicit authority, and irreversible evidence finality.

VERIFRAX is a governed repository and host perimeter that separates authority issuance, governed execution, proof publication, public verification, documentation, archive/reference surfaces, and intake so each public surface can stay inspectable without collapsing role boundaries.

## Public hosts

* `auctoriseal.verifrax.net` — authority issuance and authority reference surface
* `corpiform.verifrax.net` — governed execution and receipt surface
* `proof.verifrax.net` — public proof publication surface
* `verify.verifrax.net` — public verifier surface
* `sigillarium.verifrax.net` — seal archive and reference surface
* `docs.verifrax.net` — explanatory documentation surface
* `apply.verifrax.net` — intake surface

## Live sovereign topology

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

## Public package registry

- @verifrax/validexor
- @verifrax/originseal
- @verifrax/limenward
- @verifrax/kairoclasp
- @verifrax/irrevocull
- @verifrax/guillotine
- @verifrax/attestorium
- @verifrax/archicustos
- @verifrax/cicullis
- @verifrax/verifrax-spec
- @verifrax/verifrax-profiles
- @verifrax/auctoriseal
- @verifrax/corpiform

## Public npm package order

The public package surface is read in this exact stack order:

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
