# Governance Manifests

This directory contains **authoritative manifests** that define the closed-world governance perimeter.

- `GOVERNED_REPOS.txt` — repos that MUST be governed (rulesets + merge policy + required checks).
- `NON_GOVERNED_REPOS.txt` — repos that are explicitly excluded (quarantined / legacy / experimental).
  - Non-governed repos MUST still follow merge policy hardening (squash-only + delete branch).
  - If rulesets are supported for that repo/plan, they SHOULD be applied; if not, merge-policy-only is enforced.

Any repo not present in either list is a policy violation.
