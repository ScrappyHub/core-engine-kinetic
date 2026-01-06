# KINETIC REQUIRED ARTIFACTS (Canonical V1)

Engine Key: **KINETIC**  
Semantics: **RAW_TRUTH**  
Authority: Engine Repo (Binding addendum; enforced by CORE Runtime)

This document is an addendum to:
`ScrappyHub/Core-platform/GOVERNANCE/RUN_BUNDLE_SPEC.md`

KINETIC is a TRUTH_ENGINE. It emits structural mechanics domain truth only.

---

## Required (in addition to standard RUN_BUNDLE spec)

No additional artifacts are required beyond the standard CORE run bundle.

---

## Required Output Fields (RUN_OUTPUT.json)

RUN_OUTPUT.json MUST satisfy the engine OUTPUT_SCHEMA and MUST include:
- `semantics = RAW_TRUTH`
- `inputs_hash`
- `outputs_hash`

---

## Prohibitions

KINETIC output MUST NOT include:
- safety/compliance certification or operational directives (vertical lens only)
- causal/attribution/intent claims
- identity/governance/billing fields
- peer delivery indicators (inputs are delivered by CORE only)
