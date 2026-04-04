# Verifrax .github

![License](https://img.shields.io/badge/license-Apache--2.0-blue)
![Role](https://img.shields.io/badge/role-organization%20governance-111111)
![Surface](https://img.shields.io/badge/surface-github%20org%20control-1f6feb)

Canonical organization-governance repository for the Verifrax perimeter, responsible for shared GitHub-level defaults, governed-repository registration, organization policy surfaces, and cross-repository coordination rules without becoming the authored protocol source, authority issuer, governed execution runtime, proof publisher, verifier surface, archive surface, intake surface, or commercial host.

## Status

* Repository role: organization governance and shared GitHub defaults only
* Surface class: governance root and repository-perimeter control surface
* Public host ownership: none
* Package status: repository only
* Stack position: upstream GitHub governance surface for the governed repository set
* Authority relation: governance authority is external and bound through AUCTORISEAL plus the governed repository set declared here
* Artifact relation: governance surfaces here must remain aligned with the artifact-0005 boundary in the wider Verifrax system
* License: Apache License Version 2.0

## One-sentence role

`.github` defines the Verifrax organization’s GitHub-level governance perimeter, governed-repository registry surfaces, shared defaults, and required coordination rules so the rest of the stack can remain legible, bounded, and cross-repository consistent without turning this repository into protocol authority, runtime authority, proof publication, verification tooling, or evidence-root chain truth.

## What this repository is

This repository is the organization-governance root for the Verifrax GitHub perimeter.

Its job is to define the shared GitHub-facing control surfaces that apply across repositories.

That includes:

* organization profile content
* shared community defaults
* shared issue and pull-request templates where used
* governed and non-governed repository manifests
* current governance linkage files
* required GitHub-level discipline for repository changes
* cross-repository legibility rules
* repository-perimeter truth that should not be duplicated inconsistently elsewhere

This repository exists so a reader can determine:

* which repositories are governed
* which repositories are not governed
* how organization-level governance is expressed on GitHub
* where shared authority linkage files live
* which repositories are supposed to remain aligned
* which repositories must not silently claim the same host, role, or authority level

## What this repository is not

This repository is not:

* `VERIFRAX`
* `AUCTORISEAL`
* `CORPIFORM`
* `VERIFRAX-SPEC`
* `VERIFRAX-verify`
* `proof`
* `SIGILLARIUM`
* `apply`
* `VERIFRAX-DOCS`
* `ARCHITECTURE`

It is not:

* the authored protocol source
* the authority issuer
* the governed execution runtime
* the proof publication repository
* the public verifier repository
* the archive/catalog repository
* the intake repository
* the documentation repository
* the evidence-root chain registry
* a package distribution surface
* a catch-all narrative repo

It must not:

* claim to verify truth
* claim to issue authority objects
* claim to execute governed actions
* claim to publish proof material as the proof surface
* claim to archive seal history as the archive surface
* claim to be the primary artifact registry
* contain placeholder quickstarts
* contain fake install flows
* contain generic template prose that outruns live system truth

Governance is not protocol authorship.
Governance is not execution.
Governance is not verification.
Governance is not proof publication.

## Why this repository exists

Without a dedicated governance root, the repository perimeter drifts in predictable ways:

* two repos start claiming the same function
* a derived publication repo starts sounding like the authored source
* a surface repo starts implying protocol authority it does not hold
* package truth and README truth drift apart
* host ownership becomes ambiguous
* organization policy lives only in scattered prose

This repository exists to stop that drift at the GitHub boundary.

## Organization-level role in the Verifrax system

The main system split is:

* [`.github`](https://github.com/Verifrax/.github) — GitHub governance root
* [`VERIFRAX`](https://github.com/Verifrax/VERIFRAX) — authored source, maintained implementation surface, and evidence-root chain record
* [`AUCTORISEAL`](https://github.com/Verifrax/AUCTORISEAL) — authority issuance and authority reference
* [`CORPIFORM`](https://github.com/Verifrax/CORPIFORM) — governed execution and receipt boundary
* [`VERIFRAX-SPEC`](https://github.com/Verifrax/VERIFRAX-SPEC) — derived publication surface for specification artifacts
* [`VERIFRAX-verify`](https://github.com/Verifrax/VERIFRAX-verify) — public verifier surface
* [`proof`](https://github.com/Verifrax/proof) — public proof publication surface
* [`SIGILLARIUM`](https://github.com/Verifrax/SIGILLARIUM) — seal/archive reference surface
* [`apply`](https://github.com/Verifrax/apply) — intake surface
* [`VERIFRAX-WWW`](https://github.com/Verifrax/VERIFRAX-WWW) — public commercial root surface
* [`VERIFRAX-API`](https://github.com/Verifrax/VERIFRAX-API) — execution host implementation surface
* [`VERIFRAX-STATUS`](https://github.com/Verifrax/VERIFRAX-STATUS) — status host implementation surface
* [`VERIFRAX-SURFACE`](https://github.com/Verifrax/VERIFRAX-SURFACE) — shared public-surface form system
* primitive repositories — irreversible protocol primitives
* [`verifrax-marketplace-smoke`](https://github.com/Verifrax/verifrax-marketplace-smoke) — marketplace smoke validation surface

This repository governs the organization perimeter around those repositories.
It does not replace any of them.
It must not leave live repositories outside explicit governed or non-governed manifests.

## Authority boundary

These statements must remain explicit and stable:

* `VERIFRAX` authors normative source material.
* `VERIFRAX-SPEC` publishes derived specification artifacts from `VERIFRAX`.
* Derived artifacts are not upstream authority.
* Governance authority is external and bound through `AUCTORISEAL` plus the governed repository set declared in this repository.

That boundary matters because the easiest failure mode is dual authority language.

A limiting case shows why:

If `.github` sounded like the authored source, then `VERIFRAX` would no longer be the authored source.
If `VERIFRAX-SPEC` sounded upstream, then derivation would collapse.
If neither boundary is explicit, any repo can start sounding canonical by accident.

## Governed repository set

This repository should remain the home of the organization-level manifests that define perimeter membership.

Load-bearing governance files include surfaces such as:

* `governance/GOVERNED_REPOS.txt`
* `governance/NON_GOVERNED_REPOS.txt`
* `governance/AUTHORITY_CURRENT.txt`
* `governance/AUTHORITY_DIGEST.txt`
* `governance/AUTHORITY_VERSION.txt`
* `governance/SEAL_SCOPE.txt`

Those files exist so governance is inspectable without reading all repositories one by one.

## Current artifact relation

This repository is not the evidence-root registry for artifact-0005.
That belongs in the evidence-root surfaces of the wider system.

But this repository must still stay aligned with artifact-0005 because organization governance, governed repo membership, authority linkage, and repository-perimeter truth are part of the chain’s surrounding control boundary.

So the precise relationship is:

* `.github` does not author artifact-0005
* `.github` does not issue the artifact-0005 authority object
* `.github` does not emit the artifact-0005 governed receipt
* `.github` does not register artifact-0005 as the evidence root of record
* `.github` does maintain the organization-governance perimeter that artifact-0005 depends on remaining consistent

That is the right level.
Anything stronger becomes false.

## Public host ownership

This repository owns no product host.

It does not own:

* `https://api.verifrax.net/`
* `https://proof.verifrax.net/`
* `https://auctoriseal.verifrax.net/`
* `https://corpiform.verifrax.net/`
* `https://cicullis.verifrax.net/`
* `https://verify.verifrax.net/`
* `https://sigillarium.verifrax.net/`
* `https://apply.verifrax.net/`
* `https://docs.verifrax.net/`
* `https://status.verifrax.net/`

A governance root with no product host should say exactly that.

## What problem a reader should solve here

A reader should land here to answer questions like:

* Which repositories are governed?
* What is the GitHub-level organization boundary?
* What is the authority wording that all repos must preserve?
* Which shared defaults exist across the org?
* What repository is supposed to own which kind of truth?
* Where is the shared governance anchor on GitHub?

A reader should not land here expecting:

* a verifier UI
* a proof viewer
* a runtime API
* a documentation site
* a proof archive
* package installation instructions for the whole system

## Inputs and outputs

### Inputs

This repository consumes organization-level governance requirements and the declared repository perimeter.

### Outputs

This repository emits governance-facing GitHub surfaces only, such as:

* shared profile content
* organization-level defaults
* governance manifests
* authority-linkage references
* contribution and review discipline at the organization boundary

It does not emit:

* authority objects
* governed execution receipts
* proof publication outputs
* verifier verdicts
* archive catalogs
* primary evidence-root chain records

## Required reading order

A reader trying to understand the system should use this repository as the perimeter entry for governance only.

Typical reading order:

1. `.github` — organization governance perimeter
2. `VERIFRAX` — authored source and evidence-root chain context
3. `AUCTORISEAL` — authority layer
4. `CORPIFORM` — governed execution layer
5. `VERIFRAX-SPEC` — derived spec publication
6. `VERIFRAX-verify` / `proof` / `SIGILLARIUM` / `apply` — outward public surfaces by role

If a reader tries to learn protocol semantics from `.github`, they are already in the wrong repo.

## Shared contribution discipline

Changes here affect organization-wide presentation or governance surfaces.

So changes here must be stricter than normal repository prose changes.

At minimum, changes should preserve these rules:

* one repository role per repository
* no host claimed by two repositories
* no derived repo phrased as upstream authority
* no README allowed to outrun package, deployment, or evidence truth
* no placeholder or speculative present-tense language
* no fake CI claims
* no drift between governed-repo manifests and actual repository perimeter

## Review and merge discipline

This repository should reflect the org’s intended review boundary.

The working rule is:

* work is prepared on repository branches
* review flows through pull requests
* branch discipline remains explicit
* merge authority is not hidden in ad hoc prose edits

Where the operating policy requires the `midiakiasat` to `verifrax-systems` review/merge path, this repository should remain consistent with that discipline instead of implying direct unreviewed mutation.

## CI and governance expectations

Any CI posture described in this README must be real.

This repository should enforce real checks for:

* `Identity` — governance-file identity and repository-perimeter consistency
* `Determinism Check` — reproducibility where governance artifacts must remain reproducible
* governed/non-governed manifest consistency checks
* authority-linkage consistency checks
* README truth checks where applicable

A green check here proves governance-surface consistency only.
It does not prove authority issuance, runtime execution, verifier parity, or proof publication correctness.

## Organization profile boundary

The public organization profile belongs here.

That means this repository is the correct place for:

* organization profile presentation
* org-facing GitHub explanation
* repository-perimeter framing

But it is the wrong place for:

* protocol tutorials that belong in docs
* verifier UX copy that belongs in `VERIFRAX-verify`
* proof-publication copy that belongs in `proof`
* runtime contract copy that belongs in `CORPIFORM` or the execution surface

## Reader contract

A reader should be able to answer these in under fifteen seconds:

1. Is this the GitHub governance root? Yes.
2. Does it own a public product host? No.
3. Does it issue authority? No.
4. Does it execute governed runtime actions? No.
5. Does it publish proofs? No.
6. Does it verify proofs as the verifier surface? No.
7. Does it define the governed repository perimeter? Yes.
8. Must it stay aligned with artifact-0005 in the wider system? Yes.

If those answers are not immediate, the README is still too weak.


## Verifrax system path labels

The governed Verifrax path that this README must stay compatible with is:

1. `.github` — organization governance and governed repository boundary
2. `AUCTORISEAL` — authority issuance and public authority reference
3. `CORPIFORM` — governed execution and receipt emission
4. `VERIFRAX` — authored protocol, evidence root, and artifact-chain registration boundary
5. `VERIFRAX-SPEC` — derived specification publication surface
6. `VERIFRAX-PROFILES` — deterministic profile-constraint surface
7. `VERIFRAX-SAMPLES` — pinned sample and reproducibility surface
8. `VERIFRAX-verify` — public verification repository and UI boundary
9. `VERIFRAX-DOCS` — explanatory documentation surface
10. `cicullis` — enforcement boundary
11. `proof` — proof publication surface
12. `SIGILLARIUM` — seal and archive reference surface
13. `apply` — intake surface

The live host-label map that must remain explicit and non-contradictory is:

* `https://api.verifrax.net/` — execution surface
* `https://proof.verifrax.net/` — proof publication surface
* `https://auctoriseal.verifrax.net/` — authority issuance and authority reference surface
* `https://corpiform.verifrax.net/` — runtime and receipt reference surface
* `https://cicullis.verifrax.net/` — enforcement reference surface
* `https://verify.verifrax.net/` — public verification surface
* `https://sigillarium.verifrax.net/` — seal and archive reference surface
* `https://apply.verifrax.net/` — intake surface
* `https://docs.verifrax.net/` — documentation surface

This README must remain compatible with `artifact-0005` as the load-bearing authority → execution → verification → evidence boundary without claiming that this repository alone authors, proves, seals, or registers `artifact-0005` unless that role is actually true for this repository.


## Security

Treat this repository as organization-governance infrastructure.

Do not use public issues for sensitive findings.
If repository-specific security handling exists elsewhere, follow that repository’s security boundary too.

Governance drift is not harmless here because a wrong governance README can make multiple other repositories sound wrong at once.

## Contributing

A contribution here is wrong if it:

* makes `.github` sound like the authored protocol source
* makes `.github` sound like the authority issuer
* makes `.github` sound like the execution runtime
* makes `.github` sound like the proof or verifier surface
* introduces placeholder quickstarts
* introduces fake host claims
* weakens the authority-direction wording
* drops artifact-0005 perimeter alignment from the organization view
* blurs governed and non-governed repository membership

## License

Apache License Version 2.0. See `LICENSE`.
