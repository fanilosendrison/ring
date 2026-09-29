---
okf_version: "1.0"
kind: "KnowledgeAsset"
asset_type: "agent-directives"
domain: "ring-repository-governance"
severity: "strict"
name: "Ring Repository Agent Directives"
repository_governance:
  engineering_project:
    profile_path: "docs/repository-governance/ring-engineering.md"
---

# Ring Repository Agent Directives

## Authority order

Apply this authority order for Ring work:

1. `docs/specification/ring-spec.md` owns Ring Product Intent and current
   normative product meaning.
2. `docs/development/specification-derivation-discipline.md` governs how the
   Ring specification is derived and maintained. It is not Ring Product Intent.
3. Accepted repository artifacts produced under that discipline govern only
   their explicitly established scope.
4. `README.md` is explanatory and remains subordinate to the normative
   specification.
5. GitHub Issues and the Ring Engineering Project govern durable work
   existence, classification, scheduling, dependencies, and workflow state.
   They do not establish Ring product semantics.

Never use an Issue, Project field, implementation, convention, agent
preference, or `proto-ring` mechanism to override or silently extend Ring
Product Intent.

## Specification-first discipline

Read the normative specification and derivation discipline before performing
work that could affect Ring meaning.

Preserve this order:

```text
Product Intent
→ necessary invariants
→ obligations
→ architecture
→ mechanisms
```

Do not select architecture or implementation mechanisms before the applicable
Ring requirements have been validly derived.

Keep `proto-ring` independent from Ring derivation. Compare independently
derived Ring requirements with `proto-ring` only through work explicitly
created for that later confrontation.

## Engineering work management

Before inspecting or mutating Ring Issues or Project state, read
`docs/repository-governance/ring-engineering.md` and apply the shared GitHub
Engineering Projects operational protocol.

Use native GitHub parent, sub-issue, dependency, and Pull Request relationships
for live relationships. Do not maintain a second mutable relationship or status
projection in repository Markdown.

## Repository changes

Use one private linked worktree for each task. Preserve unrelated user state.
Do not modify Ring Product Intent, derivation methodology, or other governed
meaning merely to make implementation convenient.

Until Ring establishes a stronger canonical validation entry point, every
repository change must at minimum pass:

```bash
git diff --check
```
