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

The intended human boundary is Product Intent. Ordinary mechanically governable
repository administration is an agentic-system responsibility; genuinely
underdetermined product-level meaning returns to the human Product Intent
authority rather than being silently decided by an agent.

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

`proto-ring` is a separate experiment and is not an input to Ring's Product
Intent or its derivation.
