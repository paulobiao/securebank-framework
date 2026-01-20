> ⚠️ **Legacy Draft Notice**
>
> This document reflects an early draft of SecureBank’s layered
> architecture. It is preserved for historical context and conceptual
> evolution.
>
> The authoritative definition of the SecureBank framework layers is
> documented in:
> - `framework/overview.md`
> - `layer1_threat_propagation.md`
> - `layer2_systemic_dependencies.md`
> - `layer3_impact_quantification.md`
> - `layer4_regulatory_exposure.md`
> - `layer5_decision_resilience.md`

# SecureBank — Layers (Draft)

## Layer 1 — Identity
- Purpose: define the service identity and auth assumptions
- Output: identity risk context

## Layer 2 — Risk Analytics
- Purpose: quantify systemic risk drivers and decision thresholds
- Output: risk decision signals

## Layer 3 — Transaction Authorization
- Purpose: evaluate anomalous authorization and limit controls
- Output: transaction-level exposure

## Layer 4 — Payment/Liquidation
- Purpose: model downstream settlement propagation
- Output: financial loss channel

## Layer 5 — Governance/Board Decision
- Purpose: convert technical + financial signals into executive decisions
- Output: board-ready decision options
# SecureBank — Decision Layers

SecureBank is structured as a layered decision framework that translates technical cyber events into executive-level decisions through controlled propagation across organizational dimensions.

---

## Layer 1 — Technical Event Layer

Description:
Represents the initial cyber or transactional event.

Examples:
- API credential compromise
- Transaction limit manipulation
- Identity misuse
- Control failure

Output:
- Event classification
- Affected systems
- Initial severity (non-financial)

---

## Layer 2 — Systemic Propagation Layer

Description:
Models how the technical event propagates across interconnected systems.

Focus:
- Shared services
- Authorization engines
- Replicated configurations
- Cross-product exposure

Output:
- Scope expansion
- Blast radius estimation
- Dependency mapping

---

## Layer 3 — Financial Impact Layer

Description:
Translates systemic impact into measurable financial exposure.

Includes:
- Transactional loss
- Operational disruption
- Remediation cost
- Opportunity cost

Output:
- Estimated financial impact range
- Time-based loss projection

---

## Layer 4 — Regulatory Exposure Layer

Description:
Maps financial and operational impact to regulatory consequences.

Includes:
- Reporting thresholds
- Supervisory scrutiny
- Fines and penalties
- Compliance breaches

Output:
- Regulatory risk classification
- Escalation requirements

---

## Layer 5 — Executive Decision Layer

Description:
Supports board and executive decision-making.

Decisions include:
- Continue / suspend operations
- Notify regulators
- Activate crisis governance
- Invest in mitigation controls

Output:
- Decision options
- Trade-offs
- Time sensitivity

>>>>>>> 184d74d (Add layered decision architecture to SecureBank framework)
