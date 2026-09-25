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
agentic software development: a governed repository must be able to evolve
freely, including changing its own accepted decisions and obligations, without
silently drifting from the authorities, decisions, obligations, and
representations that govern its current state.

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
