---
okf_version: "1.0"
kind: "KnowledgeAsset"
asset_type: "agent-directives"
domain: "ring-repository-governance"
severity: "strict"
name: "Ring Engineering GitHub Project Profile"
---

# Ring Engineering GitHub Project Profile

Apply the shared GitHub Engineering Projects operational protocol before using
this profile. This file contains Ring-specific routing, authority, work-state,
classification, scheduling, and workflow policy.

## Fixed routing

- GitHub owner: `fanilosendrison`
- Default repository: `fanilosendrison/ring`
- Project title: `Ring Engineering`
- Project type: user-owned GitHub Project V2
- Project visibility: public

Resolve an unqualified `Issue #N` as `fanilosendrison/ring#N`.

The Project number, URL, node identifiers, field identifiers, option
identifiers, and item identifiers are live GitHub coordinates. Resolve them
mechanically from the owner and exact Project title instead of copying them into
this profile.

## Authority boundary

Ring Engineering is the authority for durable Ring work existence,
classification, scheduling priority, dependencies, and workflow state.

It is not authority for Ring Product Intent, normative product meaning,
derivation validity, accepted semantic choices, verification evidence, or
implementation correctness.

Apply this technical authority order:

1. `docs/specification/ring-spec.md` owns Ring Product Intent and current
   normative product meaning.
2. `docs/development/specification-derivation-discipline.md` governs how the
   specification is derived and maintained without itself becoming Product
   Intent.
3. Accepted repository artifacts produced under that discipline govern only
   their explicitly established scope.
4. `README.md` is explanatory and subordinate to the normative specification.
5. Issues, comments, Project fields, and Project views govern work management
   only.

`proto-ring` remains non-authoritative related work. A comparison Issue may
confront independently derived Ring requirements with `proto-ring` mechanisms,
but neither its existence nor its Project state may influence Ring derivation.

## Workflow-status mapping

Use exactly these `Status` values:

- `Backlog`
- `Ready`
- `In Progress`
- `Review`
- `Done`

Their meanings are:

- `Backlog`: retained work that is not currently independently executable.
- `Ready`: independently executable work whose native blockers are cleared and
  whose accepted scope is sufficient for execution.
- `In Progress`: active execution.
- `Review`: execution produced a complete reviewable result with an explicit
  outstanding review or acceptance gate.
- `Done`: the Issue's acceptance criteria and required validation are complete.

Blocked work remains in `Backlog`, carries every available native blocked-by
relationship, and has an objective resumption condition in its controlling
work item or blocker.

A direct user request may select work outside normal autonomous pickup order,
but it does not alter dependencies, authority, or accepted semantics.

## No Phase field

Ring Engineering MUST NOT define a `Phase` field.

Specification derivation, architecture, verification, and implementation are
technical responsibilities and dependency-ordered work, not workflow phases to
encode as mutable Project classification.

A Phase taxonomy requires a later explicit repository-governance decision.

## Live work-state ownership

Every mutable live work-state fact has exactly one canonical GitHub owner.

| Information | Canonical owner |
| ----------- | --------------- |
| Durable work item | GitHub Issue |
| Open or closed state | GitHub Issue state |
| Workflow state | Project `Status` |
| Work-item classification | Project `Kind` |
| Scheduling priority | Project `Priority` |
| Parent and sub-issue structure | Native GitHub Issue relationships |
| Blocking and blocked-by structure | Native GitHub dependency relationships |
| Pull Request linkage | Native GitHub relationships |
| Acceptance criteria for Issue X | Issue X body |
| Ring Product Intent and normative meaning | Ring repository authority |

Reference live work state; do not mirror it in repository documents.

## Kind

Use exactly these `Kind` values:

- `Agent Task`
- `Follow-up`
- `Finding`

Definitions:

- `Agent Task`: independently scoped work whose accepted outcome can be
  executed once native blockers are cleared.
- `Follow-up`: downstream confrontation, adoption, migration, integration, or
  other work made necessary by prior results.
- `Finding`: a validated concern requiring separate adjudication, correction,
  or an explicit authority decision.

An observation is not a `Finding` until validated. A Finding does not ratify its
proposed resolution merely by existing.

## Priority

Use exactly these `Priority` values:

- `P0`: delay blocks meaningful progress on the active Ring critical path or
  leaves an established integrity boundary exposed.
- `P1`: required by the current Ring program but not blocking all meaningful
  current progress.
- `P2`: important retained downstream or governance work outside the current
  critical path.
- `P3`: useful retained work that can safely wait without meaningful current
  scheduling cost.

Priority is scheduling state only. It never overrides Ring authority, native
dependencies, derivation discipline, acceptance criteria, or validation.

Priority does not imply readiness. A blocked `P0` item remains in `Backlog`.

## Priority revalidation

Re-evaluate open Project Issues after:

1. creation of durable work;
2. Issue completion, closure, or reopening;
3. creation or removal of a native dependency;
4. an accepted Ring authority change that affects executable work;
5. a validated cross-cutting governance Finding.

For each pass, read live Issue state, native dependencies, current Project
fields, and the Ring authority relevant to the work. Mutate only priorities
whose value must change under this profile.

## Autonomous pickup

Use this exact order:

1. candidates must have `Status = Ready`;
2. choose `P0`, then `P1`, then `P2`, then `P3`;
3. never choose work with an unresolved native blocker;
4. use the Project's existing manual order for equal-priority independent work;
5. let a direct user selection override pickup order for that action only.

## Project views

The initial Project exposes one default table view named `View 1`.

Use `View 1` as the complete all-work inventory. Filter by `Status`, `Kind`, or
`Priority` when inspecting the ready queue, active work, backlog, or Findings.
Do not infer authority or workflow state from visual ordering.

Additional views may be introduced only as projections of the canonical fields
and native relationships defined here.

## Issue requirements

A normal Ring Issue must state:

- the concrete outcome;
- the accepted Ring authority or evidence that justifies the work;
- the authority boundary that remains unchanged;
- exact repository surfaces allowed to change where known;
- mechanically checkable acceptance criteria;
- required validation;
- explicit non-goals where scope expansion is plausible.

Dependencies, current Status, Kind, Priority, parent membership, and Pull
Request relationships belong in native GitHub state rather than duplicated
mutable prose.

An Issue may identify stable semantic prerequisites without restating their
mutable live relationship state.

An Issue is work-management authority, not Ring semantic authority. Proposed
Ring meaning becomes authoritative only through the repository process governed
by the normative specification and derivation discipline.

## Findings and scope expansion

Do not silently expand active work when execution exposes a separate material
concern. Validate the observation, preserve the earliest authority layer that
must resolve it, and create a separate `Finding` only when the concern must
survive independently.

A Finding requiring new Ring meaning remains non-executable until the entitled
Ring authority resolves that meaning.

## Repository validation

Use only validation that exists in the current Ring repository.

Until a stronger canonical validation suite exists, every repository change
must at minimum pass:

```bash
git diff --check
```

Do not claim nonexistent validation evidence.

## Completion condition

An Issue reaches `Done` only when:

- its own acceptance criteria are satisfied;
- repository changes it owns are published where required;
- required validation passes;
- required authority, derivation, review, and evidence conditions are met;
- live work state is represented by GitHub rather than a new Markdown mirror.
