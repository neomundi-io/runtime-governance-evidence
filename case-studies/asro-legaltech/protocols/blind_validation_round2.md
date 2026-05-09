# Blind Validation Round 2 Protocol

## Purpose

This protocol defines the second-stage blind validation process for the ASRO × NeoMundi runtime governance study.

Round 2 introduces independent prompt batches unknown to both witness layers before execution.

The objective is to reduce observer coupling and reinforce non-circularity guarantees.

---

# Validation Principle

No witness layer should know:

- expected provider outcomes,
- expected FLAG events,
- expected governance divergence patterns,
- or expected behavioral stability results

before execution.

---

# Blind Batch Structure

The validation batch should contain:

- informational prompts,
- ambiguous prompts,
- adversarial prompts,
- policy-boundary pressure prompts,
- institutional knowledge prompts,
- contextual uncertainty prompts.

Prompt ordering should be randomized.

---

# Independence Constraints

## NeoMundi Layer

NeoMundi receives:
- provider outputs only.

NeoMundi does not receive:
- expected classifications,
- human annotations,
- governance interpretations,
- ASRO witness conclusions.

---

## ASRO Layer

ASRO receives:
- declared governance framing,
- authority posture,
- runtime deployment state.

ASRO does not receive:
- runtime behavioral measurements,
- hallucination findings,
- provider scoring outputs,
- FLAG classifications.

---

# Observer Separation

Where possible:

- prompt authors,
- runtime operators,
- behavioral reviewers,
- governance witnesses,
- and final interpreters

should remain separated until post-run comparison.

---

# Comparison Timing Rule

Cross-layer comparison occurs ONLY after:

- provider execution is complete,
- behavioral measurements are frozen,
- governance witness outputs are frozen.

No mid-run synchronization is allowed.

---

# Evaluation Goals

Round 2 seeks to evaluate:

- stability reproducibility,
- divergence consistency,
- witness independence,
- behavioral localization,
- and protocol robustness under unknown workloads.

---

# Claim Boundary

This protocol does NOT establish:
- provider rankings,
- legal certification,
- production safety guarantees,
- regulatory approval.

The protocol evaluates only:
- methodological robustness,
- witness independence,
- and reproducibility of runtime governance evidence generation.

---

# Current Status

Planned protocol.
Not yet executed.
Subject to future implementation and revision.
