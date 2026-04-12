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

```text
Current public package registry:
- verifier
```
