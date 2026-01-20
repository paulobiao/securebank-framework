# Layer 1 — Threat Propagation

## Purpose

This layer models how a cyber threat propagates across interconnected
systems over time, rather than treating incidents as isolated events.

The objective is to make threat propagation behavior explicit and
decision-relevant before technical compromise escalates into systemic loss.

---

## Core Question

How does an initial cyber compromise propagate across systems,
identities, and transactions under realistic operational conditions?

---

## Analytical Scope

This layer focuses on:

- Initial compromise vectors
- Lateral and vertical propagation paths
- Time-dependent escalation dynamics
- Amplification and containment effects

It does not attempt to detect threats or replace operational security controls.

---

## Key Assumptions

- Modern infrastructures are highly interconnected
- Failures propagate non-linearly
- Time-to-decision materially affects impact
- Propagation behavior is architecture-dependent

All assumptions are explicit and subject to independent review.

---

## Outputs

This layer produces:

- Propagation pathways
- Time-based exposure windows
- Early decision signals for containment or escalation

These outputs serve as inputs for subsequent layers.

---

## Boundary Conditions

This layer does not:

- Perform threat detection
- Attribute attackers
- Assess control effectiveness in isolation

Its sole purpose is to model propagation behavior.
