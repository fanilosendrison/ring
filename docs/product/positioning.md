---
okf_version: "1.0"
kind: "KnowledgeAsset"
asset_type: "product-positioning"
domain: "ring"
severity: "informational"
name: "Ring and Ring Cloud — Product Positioning and Differentiation"
---

# Ring and Ring Cloud — Product Positioning and Differentiation

> **Status and authority:** This is non-normative product positioning. It does
> not change Ring Product Intent or create any requirement, architecture,
> primitive, interface, or implementation guarantee. It does not promote the
> Ring Cloud candidate. Comparisons are not premises for Ring derivation. An
> intended guarantee, its implementation, and its verification remain distinct.

The [Ring specification](../specification/ring-spec.md) remains authoritative
for Ring Product Intent. The
[Ring Product Rationale](ring-product-rationale.md) and
[Ring Cloud Product Rationale](ring-cloud-product-rationale.md) explain value
without creating requirements. The
[Ring Cloud future consideration](../vision/ring-cloud.md) preserves a candidate
only.

## The distinction to understand

Applying a rule is different from preserving the authority, applicability and
validity of that rule as the software and its governance evolve.

These are different classes of capability. A tool may apply a configured rule,
run a check, or enforce a policy without establishing who may change its
meaning, when it applies, or whether a later passing result still represents the
same accepted obligation. This distinction does not imply that every
alternative ignores those questions or that Ring has already demonstrated
universal superiority.

> Ring is designed to let coding agents evolve software without silently
> rewriting the accepted intent, decisions, or obligations that govern it.

## Passing checks is not the whole question

Consider this scenario:

> An agent changes the software. A check fails. The agent changes something
> else. The check then passes.

The final passing result admits at least four materially different
interpretations:

<!-- markdownlint-disable MD013 -->

| Situation | Interpretation |
| --------- | -------------- |
| The original applicable obligation is satisfied again. | Repair. |
| An entitled authority legitimately revises the obligation. | Authorized evolution. |
| The agent weakens the obligation or its acceptance criteria without sufficient authority. | Unauthorized drift, despite a passing check. |
| Available evidence cannot establish which situation applies. | Unresolved interpretation, not presumed success. |

<!-- markdownlint-enable MD013 -->

Changing a test is not prohibited in principle. Correcting an erroneous test
can be legitimate. The relevant questions are whether the change came from
sufficient authority and whether its justification is preserved. Governance
does not freeze rules forever; it distinguishes accepted evolution from silent
weakening.

The scenario illustrates requirements already established by Ring Product
Intent. It selects no test representation, authority mechanism, validation
engine, or other implementation.

> The important question is not only whether the checks pass, but whether
> the resulting software and the criteria used to accept it still follow
> from accepted authority.

## Ring's intended end-to-end responsibility

Ring is designed around the continuity of this responsibility chain:

```text
accepted authority
→ applicable obligations
→ exact state under evaluation
→ appropriately scoped results
→ explainable admissibility
→ governed maintenance and remediation
```

The intended product experience includes agent administration of that chain.
The human establishes and evolves Product Intent, but must not become the
permanent operator of governance work that is mechanically administrable.

Three categories remain distinct:

- a necessary consequence follows from accepted applicable premises;
- genuine implementation freedom permits an agent to choose among realizations
  that do not change accepted product meaning or guarantees; and
- an underdetermined product choice returns to the human authority when its
  alternatives differ in product meaning or guarantees.

Implementation remains open. Ring does not require every future source line,
abstraction, optimization, cache, or algorithm to be pre-enumerated. The
effects of those choices remain subject to whichever governed properties
actually apply.

As the [Ring Product Rationale](ring-product-rationale.md) explains, Ring does
not make a model incapable of hallucinating. It is designed to contain the
governed consequences of agent errors by preventing implementation activity
from silently becoming governing truth.

That responsibility remains bounded by the coverage actually governed, the
quality of the accepted obligations, what can be observed, and the real scope
of the verification performed. Ring is not a universal correctness oracle and
does not guarantee bug-free software.

## Ring Cloud's candidate distinction

> Ring Cloud aims to preserve the distinction between repair, authorized
> requirement evolution, unauthorized weakening, and unresolved evidence
> across software-development trajectories.

For some evaluation and learning uses, a generic `failure → success` sequence is
insufficient. A successful check obtained after unauthorized weakening of its
acceptance criterion must not automatically be interpreted as a positive
repair.

Three responsibilities must be evaluated separately:

1. **Produce a governed observation:** establish what the applicable governance
   says about an exact state, including what remains unknown.
2. **Capture the observation:** preserve the observation and enough of its
   context, provenance, authorization, and state binding for later use.
3. **Exploit the observation:** use captured material for analysis, evaluation,
   research, learning, routing, or another downstream purpose.

A competitor may fulfill one role without fulfilling the others. A composition
may supply missing roles when its components, integration boundaries, and
required dependencies are actually available and adequate; a hypothetical
component that still needs to be developed is not an available composition.

The signal remains bounded by what was established and captured. Later
statistical or learned results remain downstream analysis and do not become
governing authority.

The first transition at which a violation is observed does not necessarily
identify the causal action. Historical information that can no longer be
recovered with equivalent authority does not imply that no useful synthetic or
alternative learning example can be produced. Another system may provide an
equivalent capability; this is not an exclusivity claim for Ring Cloud. The
practical value of governance-aware annotations must be evaluated rather than
presumed.

## How alternatives should be compared

Alternatives should be compared by the responsibilities and guarantees they
actually cover, not by whether their descriptions contain words such as
*governance*, *intent*, *invariant*, *policy*, or *dataset*.

The comparison has three independent dimensions:

- **Ring guarantees:** preservation of governed repository evolution relative
  to accepted authority;
- **Cloud signal:** production and longitudinal preservation of a suitably
  governed observation; and
- **Cloud downstream:** uses made of that signal for evaluation, learning,
  research, routing, assurance, or analysis.

A configurable primitive is not automatically a complete end-to-end solution.
Conversely, an actually available composition can be equivalent on a declared
scope without sharing Ring's architecture, names, or components.

Named observations and technical ratings belong in dated historical reports,
not in this positioning document. The
[Competitive Guarantee Watch](../research/competitive-watch/README.md) defines
that separate evidence process.

## Evidence and public claims

Public claims must preserve three levels:

```text
intended guarantee
implemented mechanism
verified behavior
```

Ring is described as **“is designed to”** do something until its implementation
and verification establish stronger claims. Ring Cloud is described as
**“aims to”** or as a **candidate** while it remains unpromoted and its
realization is not established.

The following general conclusions are prohibited unless their stated scope and
evidence genuinely establish them:

- “only Ring can”;
- “no competitor does this”;
- “Ring eliminates hallucinations”;
- “Ring guarantees bug-free software”; and
- “Ring Cloud owns uniquely unobtainable training data.”

Every comparative conclusion must identify its date, scope, and evidence basis.
An absence of public evidence is not evidence that a capability is impossible
or absent.
