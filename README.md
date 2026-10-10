---
okf_version: "1.0"
kind: "KnowledgeAsset"
asset_type: "readme"
domain: "ring"
severity: "guideline"
name: "Ring"
---

# Ring

Ring exists to preserve the integrity of software-repository evolution under
agentic software development: the human establishes and evolves Product Intent,
the agentic development system administers repository evolution under that
accepted intent, and the repository must remain able to evolve freely without
silently drifting from the authorities, decisions, obligations, and
representations that govern its current state.

> Passing checks is not enough if their meaning can change without accepted
> authority. Ring is designed to distinguish restoring an existing obligation,
> legitimately revising it, and silently weakening what the software is
> supposed to guarantee—without making the human the permanent operator of
> repository governance.

This distinction is explained in the non-normative
[Product Positioning and Differentiation](docs/product/positioning.md).
It describes intended product responsibilities, not a claim that the complete
implementation or comparative superiority has already been demonstrated.

The intended human boundary is Product Intent. Ordinary mechanically governable
repository administration is an agentic-system responsibility; genuinely
underdetermined product-level meaning returns to the human Product Intent
authority rather than being silently decided by an agent.

Ring is intended to be the agent-facing repository-governance interface for that
administration. An agentic development system must be able to use Ring to
bootstrap governance for a repository, inspect its current governance, check
conformance, distinguish mechanically remediable state from authority-required
meaning, apply mechanically determined governance maintenance or remediation,
and validate the exact resulting repository state.

Ring does not silently turn an observed or apparently stable repository state
into a stronger governance conclusion. A repository-state-dependent conclusion
must be supported by the state properties actually established for it. If a
required property cannot be established, Ring exposes that condition rather
than claiming conformance or validation from assumption.

The concrete API, CLI, protocol, module structure, and repository-governance
layout remain later derivation questions.

This repository currently contains Ring's initial Product Intent
specification together with the development methodology used to derive and
maintain it. Ring is developed specification-first:

```text
Product Intent
→ necessary invariants
→ obligations
→ architecture
→ mechanisms
```

The normative specification is
[docs/specification/ring-spec.md](docs/specification/ring-spec.md). It defines
Ring's Product Intent and the immediate semantic distinctions required to
interpret it; invariants, architecture, and mechanisms are deliberately left to
later derivation. This README is subordinate to that specification.

Two non-normative Product Rationale documents provide additional context:
[Ring Product Rationale](docs/product/ring-product-rationale.md) explains the
user problem, value, and outcomes behind Ring's existing Product Intent, while
[Ring Cloud Product Rationale](docs/product/ring-cloud-product-rationale.md)
explains the value proposition behind the non-authoritative Ring Cloud
candidate. Neither document is an input to Ring derivation.

`proto-ring` is a separate experiment and is not an input to Ring's Product
Intent or its derivation.

A separate non-authoritative future consideration for a possible adjacent
[Ring Cloud](docs/vision/ring-cloud.md) product preserves the longitudinal
governance-data opportunity and the future Ring/Ring Cloud boundary questions.
It is not Ring Product Intent, is not an input to Ring derivation, and creates
no Ring invariant, obligation, architecture, or mechanism.

The candidate Ring Cloud opportunity includes preserving these distinctions
over time so that evaluations and learning data do not automatically label a
weakened acceptance criterion as a successful repair.

The [Competitive Guarantee Watch](docs/research/competitive-watch/README.md) is
a dated, evidence-based research archive kept separate from product authority.
