# Layer 2 — Systemic Dependencies

## Purpose

This layer models how technical, operational, and organizational
dependencies influence the amplification or containment of cyber risk
as threats propagate across systems.

Its objective is to expose hidden coupling points that transform
localized failures into systemic events.

---

## Core Question

Which dependencies cause cyber failures to amplify, cascade, or become
systemically significant?

---

## Analytical Scope

This layer focuses on:

- Technical system interdependencies
- Shared identity, data, and transaction services
- Organizational and process coupling
- Single points of amplification and bottlenecks

It does not evaluate control maturity or compliance posture.

---

## Dependency Modeling

Dependencies are modeled as explicit relationships rather than implicit
assumptions, including:

- Shared services and trust anchors
- Transactional coupling across domains
- Temporal dependencies between processes
- Organizational escalation paths

Dependencies may amplify or dampen propagation effects.

---

## Key Assumptions

- System architectures contain hidden coupling points
- Dependencies are often undocumented or underestimated
- Failure impact depends more on dependency structure than on the
  initial compromise itself

All assumptions are explicit and reviewable.

---

## Outputs

This layer produces:

- Dependency maps
- Amplification points
- Bottlenecks and critical coupling paths

These outputs refine propagation behavior identified in Layer 1.

---

## Boundary Conditions

This layer does not:

- Propose architectural redesigns
- Perform root cause analysis
- Replace enterprise architecture practices

Its sole purpose is to make systemic dependencies explicit.
