---
okf_version: "1.0"
kind: "KnowledgeAsset"
asset_type: "research-methodology"
domain: "ring-competitive-watch"
severity: "strict"
name: "Competitive Guarantee Watch Methodology"
---

# Competitive Guarantee Watch Methodology

Methodology version: 1.2.0

This version identifies the research method, not a Ring product version. The
method governs competitive-watch operations only. Its axes are research
questions grounded in existing Ring authorities; they are not new Ring
invariants, obligations, architecture, or derivation premises.

## Guarantee comparison

The following axes guide evidence collection and scoped assessment.

### R1 — Accepted authority

Determine how the examined scope represents human Product Intent, authority by
responsibility or scope, proposal versus acceptance, and genuine implementation
freedom. Establish who can change governed meaning and how that entitlement is
known.

### R2 — Applicability and coverage

Determine which obligations actually apply, how omitted checks are handled,
and whether indeterminate applicability can be distinguished from satisfied or
inapplicable obligations.

### R3 — Evolution of governance

Determine how authorized revisions of requirements, rules, policies, and tests
are distinguished from unilateral weakening of acceptance criteria.

### R4 — Exact binding and currentness

Determine the state actually observed, evaluation premises and context, how
stale results are excluded, and how results bind to the state ultimately
accepted.

### R5 — Unknown and failure handling

Determine how impossible observations, unavailable verifiers, incomplete
proof, ambiguous authority, and other unknowns are represented. Identify
boundaries at which a positive result is prohibited because the required fact
was not established.

### R6 — Agent-administered governance

Determine whether an agent can bootstrap, inspect, diagnose, maintain, perform
a determined repair, mutate governance state, and validate the resulting state
without routine human reconstruction of mechanically administrable governance.

### R7 — Representation and provenance integrity

Determine how canonical and secondary sources, currentness, dependencies, and
continuity of accepted changes are represented and preserved.

### R8 — End-to-end composition

Determine the responsibilities of observer, decider, and enforcer; host
dependencies; bypass assumptions; concurrency and partial-failure behavior; and
how evolution of the governance system itself is governed.

### C1 — Observation-time governed signal

Determine what was actually established at the observation time, under which
authority, for which obligation and exact state, including what remained
unknown.

### C2 — Longitudinal validity

Determine whether repair, authorized revision, unauthorized weakening, and
missing evidence remain distinguishable as governance evolves.

### C3 — Learning-label validity

Determine whether data distinguishes failure, diagnosis, insufficient repair,
restored conformance, authority, and escalation. Never infer proven causality
from observed localization alone.

### C4 — Downstream capabilities

Examine evaluation, regression generation, datasets, training, repair research,
routing, prediction, harness improvement, cross-cutting intelligence,
assurance, audit, and incident analysis. For every use, identify the required
signal, its producer, missing dependencies, and actual availability.

### C5 — Capture, reproducibility and authorization

Determine what context is preserved, which capture gaps remain, whether replay
is possible, how material is minimized, which reuse rights exist, and which
historical facts cannot be reconstructed with equivalent authority.

These questions never require a competitor to adopt an architecture that Ring
has not itself adopted. Equivalent available compositions are assessed by their
actual guarantees and boundaries, not by resemblance to Ring names or assumed
mechanisms.

## Permanent radar

Once an identifiable actor, product, or component is evaluated on any scope, it
remains monitored indefinitely while the watch operates unless the user gives
an explicit instruction to stop monitoring it.

An actor is never removed automatically because of:

- a low threat level;
- a complementary role;
- a lack of news;
- an indeterminate assessment;
- closed source;
- an archived repository;
- closure of a finding; or
- acquisition, renaming, or cessation of activity.

Monitoring membership, actor lifecycle, relevance, capability, and confidence
are separate facts. A dormant or discontinued actor retains its history and is
checked for revival, successors, forks, and transferred technology.

A rename preserves actor identity. A genuine fork or successor receives a
linked identity. An identity error is corrected in a new report without erasing
history.

The effective historical radar is the union of:

- initial seeds;
- admissions in every prior report;
- explicit user additions; and
- pending registrations recovered with verifiable references.

`watchlist.json` does not override or replace admissions recorded in reports. A
user instruction to stop monitoring changes monitoring status while preserving
the actor and all reports.

## Two mandatory activities for every execution

Every execution performs both activities:

- **A — accumulated-radar monitoring:** inspect every retained actor according
  to current coverage obligations and cursors;
- **B — open discovery:** search for new actors, products, components, forks,
  research projects, features, and available compositions.

Neither activity may be omitted because the other consumed available resources.
When either cannot be completed, the report declares incomplete coverage.
Discovery occurs on every run, not only on Monday, and is not limited to known
names.

Search by problems and guarantees, rotating formulations across:

- repository authority;
- applicability and omitted checks;
- mutation of requirements, tests, and policies;
- evidence validity and exact-state binding;
- admission and authorized repair;
- governed capture and longitudinal validity;
- repair and escalation datasets;
- evaluation environments;
- harness control; and
- available end-to-end compositions.

Include new products, research projects, new features from known actors, forks,
and compositions that are actually available. Record the channels, queries,
and times actually used. “No new entrant found” is acceptable only after a real
search and never proves that no entrant exists. A hypothetical capability that
would still need to be developed is not an available composition.

## Implementation analysis

Do not stop at public positioning when a conclusion depends on code behavior.
For each relevant guarantee, follow this path when accessible:

```text
production entry point
→ observer / input construction
→ applicability and rule selection
→ evaluator
→ error and unknown handling
→ evidence and state binding
→ actual enforcement / admission
→ capture and downstream interpretation
```

Inspect:

- configurations and defaults;
- features actually reachable in the product;
- disableable controls;
- error and bypass paths;
- which actor may modify policy;
- whether a newly introduced policy can authorize its own modification;
- wrappers and delegated components;
- positive and negative tests; and
- differences among branches, releases, and deployed services.

Monitor relevant source changes even without a public announcement. Reproduce
useful tests or counterexamples when the environment permits safe, isolated
execution without user secrets.

Never collapse these evidence states:

```text
code read
!= tests read
!= tests executed
!= verified proof
```

When code is closed, inaccessible, or incomplete, preserve the limitation,
continue monitoring, inspect available primary material, and do not infer the
absence of a capability. An unfinished technical inspection becomes a
persistent investigation. A component whose identity is still indeterminate is
represented explicitly as indeterminate rather than assigned an invented
identity.

## Discriminating scenarios

Retain these scenarios as analysis questions:

1. An agent changes code and then weakens the failing control.
2. A human legitimately revises the requirement.
3. A stale representation contradicts current authority.
4. A new implementation violates a pre-existing governed property.
5. Code or governance changes after successful validation.
6. A mandatory control cannot execute.
7. A new agent resumes without prior private conversation.
8. Multiple repairs imply different product choices.
9. A data pipeline labels weakening as repair.

These scenarios do not constitute a normative Ring benchmark installed by this
work.

## Levels and dimensions

Assess these dimensions separately:

- `ring_guarantees`;
- `cloud_signal`; and
- `cloud_downstream`.

No aggregate score or average is required.

<!-- markdownlint-disable MD013 -->

| Level | Rendered label | Meaning |
| ----- | -------------- | ------- |
| `U` | ⚪ INDETERMINATE | Information is insufficient; this does not mean low threat. |
| `L0` | 🟢 ADJACENT_OR_COMPLEMENTARY | The examined scope does not replace the considered guarantee. |
| `L1` | 🟡 ISOLATED_PRIMITIVE | A relevant primitive exists without the required composed guarantee. |
| `L2` | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | A substantial subset is established and identified gaps remain. |
| `L3` | 🔴 NEAR_EQUIVALENCE | A composition covers most of the declared scope and decisive gaps are explicit. |
| `L4` | 🟣 DEMONSTRATED_SCOPED_EQUIVALENCE | End-to-end equivalence is established for the declared scope with sufficient assumptions, dependencies, and verification. |

<!-- markdownlint-enable MD013 -->

Every rating states its scope, rationale, evidence, confidence, and external
dependencies. Violet on a sub-scope is not equivalence to all of Ring Cloud. A
downstream platform may rely on an external signal producer.

Availability, role, confidence, and lifecycle remain separate. Reputation,
funding, and repository stars do not change technical levels. An announcement
may trigger investigation but cannot promote an established level. No color
removes an actor from the radar.

## Evidence discipline

Prefer primary sources. Source-code evidence identifies immutable revisions and
precise paths. Distinguish event date, publication date, and observation date.

Evidence categories are:

- `claim`;
- `documentation`;
- `source_inspection`;
- `tests_inspected`;
- `reproduced`; and
- `proof_artifact`.

For `reproduced` evidence, preserve the command, environment, result, and a
reference to execution material actually obtained. A formal-proof artifact is
described according to the scope it actually proves; its filename or extension
never establishes proof status automatically. Event and publication dates may
retain limited precision rather than inventing an unsupported time. Never turn
an old chat answer into a verified audit. Never invent a SHA, URL, test, result,
or author.

Preserve these distinctions:

- determinism is not semantic completeness;
- a hash or signature is not truth of content;
- capture is not authority;
- configured verification is not verification executed on the correct state;
- first observed violation is not proven exact cause;
- absence of public evidence is not impossibility;
- announcement is not availability; and
- a useful synthetic example is not an original historical observation.

Apply the same standard to Ring: intended behavior is not an implemented or
verified guarantee.

## History and trajectories

Every published report is immutable. A correction is a new report that
references the original. Actor, component, and finding identifiers remain
stable.

Classify assessment changes independently with:

- `implementation_change`;
- `new_evidence`;
- `assessment_correction`;
- `ring_baseline_change`; and
- `methodology_change`.

Only `implementation_change` establishes technical progress by the competitor.
Do not rewrite historical ratings under a new methodology or Ring baseline.
Each report preserves the Ring commit, schema version, and methodology version
used. Method and schema sources must be recoverable at immutable revisions.

A carried-forward assessment retains its original observation date and sets
`revalidated_this_run` to `false`. Never derive an equivalence date from commit
counts. Analyze gaps actually closed, reduced, reopened, or made dependent on
other systems.

## Publication controls beyond JSON Schema

The structural schema is necessary but insufficient. Before publication, the
execution must also verify:

- uniqueness of identifiers and actor/component pairs;
- resolution of evidence and historical finding references;
- presence of every axis, using explicit `unknown` when not evaluated;
- consistency among `report_id`, `generated_at`, and the report directory;
- temporal consistency of the observation window;
- consistency of `new_entrants`, `admitted_actor_ids`, and
  `newly_admitted_actor_ids`;
- equality between `current_actor_ids` and the set of actor IDs in `actors`;
- inclusion of all historical actors and every new admission;
- `user_stopped` only with a verifiable user instruction;
- no fictitious revalidation or cursor advancement without observation;
- justification for every threat level;
- distinction between a carried-forward value and a new observation;
- JSON/Markdown equivalence; and
- immutability of every previously published report.

Successful structural validation never establishes the truth of competitive
conclusions or inter-report continuity. Those require evidence review and the
separate continuity checks above.
