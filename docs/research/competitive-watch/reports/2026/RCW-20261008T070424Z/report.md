# Veille Ring / Ring Cloud — Rapport du 08/10/2026 09:04:24 CEST

<!-- markdownlint-disable MD007 MD013 MD024 MD029 MD032 -->

- **report_id :** `RCW-20261008T070424Z`
- **type :** `daily`
- **fenêtre observée :** `2026-10-07T06:55:52Z` → `2026-10-08T07:04:24Z`
- **généré à :** `2026-10-08T07:04:24Z`
- **référence Ring :** `fanilosendrison/ring@2dba6f54e9eac14b9e304d54a0f2e564dcc9111c`
- **version du schéma :** `2`
- **version de la méthode :** `1.2.0`
- **statut de Ring Cloud :** Ring Cloud demeure un candidat non normatif : aucune promotion ni réalisation du produit n’est inférée de cette veille.
- **historique disponible lors du passage :** `false`

Ce document est une projection mécanique de `report.json`.

## 1. Fenêtre d’observation et base de comparaison

La fenêtre s’étend de `2026-10-07T06:55:52Z` à `2026-10-08T07:04:24Z`. Le rapport a été généré à `2026-10-08T07:04:24Z` avec Ring à la révision `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c`.

### Sources de base

- `docs/specification/ring-spec.md` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Ring Product Intent and normative meaning
- `docs/product/ring-product-rationale.md` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Non-normative Ring product rationale
- `docs/product/ring-cloud-product-rationale.md` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Non-normative Ring Cloud candidate rationale
- `docs/vision/ring-cloud.md` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Non-authoritative Ring Cloud future consideration
- `docs/product/positioning.md` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Non-normative positioning
- `docs/research/competitive-watch/methodology.md` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Competitive watch methodology 1.2.0
- `docs/research/competitive-watch/report.schema.json` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Report schema v2
- `docs/research/competitive-watch/watchlist.json` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Discovery seed roster
- `docs/research/competitive-watch/reports/2026/RCW-20261007T065552Z/report.json` @ `NOT_PRESENT_ON_ORIGIN_MAIN` — Previous report exists as conversation-produced local artifact only; not an archived GitHub report.

## 2. Synthèse

Évolution technique confirmée chez Mneme, Chainloop et Chock. Mneme publie v0.10.0 et termine la chaîne D1 du Decision Index canonique; DG1 reste à développer. Chainloop ferme deux défaillances importantes de la validité des attestations et de capture obligatoire, avec des exceptions explicitement identifiées. Chock corrige la détection de drift et la couverture multi-racines. Deux acteurs entrent au radar permanent : AgentOps (vraie liaison contenu/acceptance/verdict avec NOT_PROVEN) et GitLab Governed Software Factory (annonces antérieures au précédent rapport, implémentation non vérifiée). Aucun L3/L4 n’est démontré. L’historique du rapport précédent reste récupérable dans ce chat mais n’est pas publié au dépôt : ROSTER_HISTORY_INCOMPLETE, ARCHIVE_PENDING.

⚪ U signifie indéterminé, pas faible menace.

Aucun test tiers n'a été exécuté pendant ce passage; les tests cités ont été inspectés, pas reproduits.

## 3. Tableau des niveaux de menace

| Acteur / composant | Garanties Ring | Signal Cloud | Usages downstream | Confiance | Disponibilité | Dernière observation | Réévalué pendant ce passage ? |
| ------------------ | -------------- | ------------ | ----------------- | --------- | ------------- | -------------------- | ------------------------------ |
| Nool / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Mneme / `mneme-core` | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟡 ISOLATED_PRIMITIVE | high/medium/medium | released | 2026-10-08T07:04:24Z | true |
| CodeSpeak / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Qodo / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Packmind / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Tessl / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Microsoft Agent Governance Toolkit / `policy-engine-core` | 🟡 ISOLATED_PRIMITIVE | 🟡 ISOLATED_PRIMITIVE | 🟢 ADJACENT_OR_COMPLEMENTARY | high/medium/medium | released | 2026-10-07T06:55:52Z | false |
| Agent Control Specification / `acs-runtime` | 🟡 ISOLATED_PRIMITIVE | 🟡 ISOLATED_PRIMITIVE | 🟢 ADJACENT_OR_COMPLEMENTARY | high/high/high | prerelease | 2026-10-07T06:55:52Z | false |
| Chainloop / `policies-attestation` | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟡 ISOLATED_PRIMITIVE | high/high/medium | released | 2026-10-08T07:04:24Z | true |
| Entire / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| LangSmith / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Braintrust / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Langfuse / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Arize Phoenix / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| W&B Weave / Agent Lens / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Kiro / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Augment Intent / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| 8090 / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| CodeRabbit / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Greptile / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Endor Labs / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Rippletide / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Google agent governance offerings / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| GitHub agent platform and governance / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| OpenAI Codex and agent tooling / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Anthropic Claude Code / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Imandra / CodeLogician / SpecLogician / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Antithesis / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Open Policy Agent / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| in-toto / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Spec Kit / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| OpenSpec / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Jama Connect / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| StrongDM software factory / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Prime Intellect / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| SWE-Gym / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| SWE-smith / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| R2E-Gym / DeepSWE / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Poolside / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Chock / `chock-core` | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟡 ISOLATED_PRIMITIVE | 🟢 ADJACENT_OR_COMPLEMENTARY | medium/medium/medium | released | 2026-10-08T07:04:24Z | true |
| DynosAI / `dynosai-core` | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | medium/medium/medium | released | 2026-10-07T06:55:52Z | false |
| Vectimus / `vectimus-core` | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟡 ISOLATED_PRIMITIVE | 🟢 ADJACENT_OR_COMPLEMENTARY | medium/medium/medium | released | 2026-10-07T06:55:52Z | false |
| AgentOps (boshu2/agentops) / `agentops-evidence-core` | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟡 ISOLATED_PRIMITIVE | high/high/medium | unknown | 2026-10-08T07:04:24Z | true |
| GitLab Governed Software Factory / Governance for Agents / `duo-agent-governance-and-factory` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | 2026-10-08T07:04:24Z | false |

### Détails par acteur et composant

#### Nool — `nool` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Mneme — `mneme` / `mneme-core`

- **rôles :** `competitor`
- **résumé :** D1 est désormais réalisé et publié en v0.10.0 (Decision Index canonique, migration explicite et tests de parité historiques); DG1 d’applicabilité/précédence/waivers reste post-D1. 🟠 L2 inchangé.
- **dernière observation :** `2026-10-08T07:04:24Z`
- **réévalué pendant ce passage :** `true`
- **disponibilité :** `released`

##### Garanties Ring — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** Décisions architecturales canoniques, autorité d'écriture, enforcement et lineage.
- **justification :** La persistance canonique, l’identité/versioning et la migration D1 sont désormais publiées en v0.10.0. La couche DG1 de décision effectivement applicable/précédence/waivers reste annoncée comme travail post-D1: équivalence Ring end-to-end non établie.
- **preuves :** `E-MN-001`, `E-MN-002`, `E-MN-003`, `E-20261008-MN-001`, `E-20261008-MN-002`, `E-20261008-MN-003`
- **confiance :** `high`
- **dépendances externes :** aucun

##### Signal Cloud — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** Signal de décision, enforcement, provenance et audit dans le périmètre Mneme.
- **justification :** Le signal gouverné est substantiel, mais la couverture longitudinale complète et la distinction générale des évolutions de gouvernance restent incomplètes.
- **preuves :** `E-MN-001`, `E-MN-002`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Usages downstream — `L1` 🟡 ISOLATED_PRIMITIVE

- **périmètre :** Audit, benchmarks et recherche architecturale Mneme.
- **justification :** Des primitives downstream existent, mais aucune plateforme longitudinale équivalente au candidat Ring Cloud n'est démontrée dans les chemins inspectés.
- **preuves :** `E-MN-001`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `supported` :** Chemins d'autorité humains explicites pour les décisions canoniques. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `DG1 doit encore généraliser la sémantique d'autorité effective.`.
- **R2 — `partial` :** Enforcement/applicability existe pour des règles typées. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `DG1 doit encore formaliser applicabilité, précédence, waivers et décision effective.`.
- **R3 — `partial` :** D1 (versions, writers, migration et parity) publié en v0.10.0; DG1 reste post-D1. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`, `E-20261008-MN-001`, `E-20261008-MN-002`. Lacunes : `Cycle complet de gouvernance des changements reste en fermeture D1/DG1.`.
- **R4 — `partial` :** Persistance canonique et vérification de snapshot. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Trusted execution attestation reste différé.`.
- **R5 — `supported` :** Plusieurs chemins refusent migration/collision plutôt que réparer implicitement. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Étendre à toutes les frontières de gouvernance.`.
- **R6 — `partial` :** CLI/API administrent plusieurs opérations gouvernées. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `D1 pas clos; DG1 à venir.`.
- **R7 — `supported` :** D1 (versions, writers, migration et parity) publié en v0.10.0; DG1 reste post-D1. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`, `E-20261008-MN-001`, `E-20261008-MN-002`. Lacunes : `D1E-D1F à clôturer.`.
- **R8 — `partial` :** Séparation authority/proposals/enforcement documentée. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Résolution effective cross-decision et fédération restent futures.`.
- **C1 — `partial` :** Enforcement/evidence et décisions canoniques produisent un signal structuré. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Attestation d'exécution de tests et couverture complète non établies.`.
- **C2 — `partial` :** Version lineage et supersession aident la validité longitudinale. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Repair versus requirement revision n'est pas encore un contrat complet.`.
- **C3 — `limited` :** Signal de conformité architecturale exploitable. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Labels de réparation/escalade Ring Cloud non établis.`.
- **C4 — `limited` :** Audit/research/benchmark existent. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Pas de plateforme longitudinale équivalente démontrée.`.
- **C5 — `partial` :** Provenance canonique et corpus de tests présents. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Reproductibilité de toutes les observations runtime non établie.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `2026-10-07T06:55:52Z`
- **dernier contrôle de signal :** `2026-10-08T07:04:24Z`
- **dernière inspection de code :** `2026-10-08T07:04:24Z`
- **dernière évaluation :** `2026-10-08T07:04:24Z`
- **prochaine échéance :** `2026-10-15T07:04:24Z`
- **statut de surveillance :** `permanent`
- **cycle de vie :** `active`
- **couverture :** `partial`
- **motif d’admission :** Piste initiale évaluée techniquement pendant cette baseline.
- **acteurs liés :** aucun
- **investigations en attente :**
- Suivre clôture D1E-D1F puis DG1.
- Évaluer trusted test attestation et sémantique effective-decision lorsqu'elles changent.

#### CodeSpeak — `codespeak` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Qodo — `qodo` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Packmind — `packmind` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Tessl — `tessl` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Microsoft Agent Governance Toolkit — `microsoft-agt` / `policy-engine-core`

- **rôles :** `competitor`, `supplier`, `complement`
- **résumé :** Le noyau n'est plus un moteur indépendant: c'est un shim ACS. Le toolkit complet reste à auditer séparément.
- **dernière observation :** `2026-10-07T06:55:52Z`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `released`

##### Garanties Ring — `L1` 🟡 ISOLATED_PRIMITIVE

- **périmètre :** Policy engine core actuel du toolkit.
- **justification :** Le core inspecté est désormais un shim vers ACS; les garanties end-to-end restent donc tributaires d'ACS et de l'hôte, avec en plus une note de sécurité explicite sur une provenance de manifest à restaurer.
- **preuves :** `E-MS-001`
- **confiance :** `high`
- **dépendances externes :** `agent-control-spec`, `agent-hooks host`

##### Signal Cloud — `L1` 🟡 ISOLATED_PRIMITIVE

- **périmètre :** Signal de verdict du core ACS re-exporté.
- **justification :** Le core ne fournit pas une conservation longitudinale autonome du signal.
- **preuves :** `E-MS-001`
- **confiance :** `medium`
- **dépendances externes :** `agent-control-spec`, `host telemetry/storage`

##### Usages downstream — `L0` 🟢 ADJACENT_OR_COMPLEMENTARY

- **périmètre :** Usages Ring Cloud du core policy engine.
- **justification :** Aucune capacité downstream équivalente n'est établie dans le core inspecté.
- **preuves :** `E-MS-001`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `limited` :** Le core expose ACS/approval contracts. Preuves : `E-MS-001`. Lacunes : `Résolution d'autorité est externe.`.
- **R2 — `partial` :** Policy plane ACS. Preuves : `E-MS-001`. Lacunes : `Intégration hôte requise.`.
- **R3 — `unknown` :** Évolution autorisée des policies non évaluée. Preuves : aucun. Lacunes : `Inspecter surfaces toolkit hors core.`.
- **R4 — `partial` :** Policy input via ACS. Preuves : `E-MS-001`. Lacunes : `Exact state global à l'hôte.`.
- **R5 — `partial` :** Runtime structuré. Preuves : `E-MS-001`. Lacunes : `Note de sécurité sur provenance URL à résoudre selon versions.`.
- **R6 — `limited` :** Core policy seulement. Preuves : `E-MS-001`. Lacunes : `Toolkit complet non audité.`.
- **R7 — `limited` :** Le code signale explicitement une frontière de provenance manquante dans ACS ciblé. Preuves : `E-MS-001`. Lacunes : `Vérifier version effective et restauration upstream.`.
- **R8 — `limited` :** Shim de compatibilité, responsabilités distribuées. Preuves : `E-MS-001`. Lacunes : `Inspecter host integrations.`.
- **C1 — `partial` :** Signal ACS exposé. Preuves : `E-MS-001`. Lacunes : `Persistance externe.`.
- **C2 — `unknown` :** Non établi. Preuves : aucun. Lacunes : `Inspecter telemetry/record stores du toolkit.`.
- **C3 — `unknown` :** Non établi. Preuves : aucun. Lacunes : `Inspecter downstream.`.
- **C4 — `unknown` :** Non évalué au-delà du core. Preuves : aucun. Lacunes : `Inspecter toolkit complet.`.
- **C5 — `limited` :** Reproductibilité du runtime ACS. Preuves : `E-MS-001`. Lacunes : `Storage/provenance externes.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `2026-10-07T06:55:52Z`
- **dernier contrôle de signal :** `2026-10-08T07:04:24Z`
- **dernière inspection de code :** `2026-10-07T06:55:52Z`
- **dernière évaluation :** `2026-10-07T06:55:52Z`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `permanent`
- **cycle de vie :** `active`
- **couverture :** `partial`
- **motif d’admission :** Piste initiale évaluée techniquement pendant cette baseline.
- **acteurs liés :** `acs`
- **investigations en attente :**
- Auditer les host integrations et la version effective d'ACS, notamment la provenance des manifests URL.

#### Agent Control Specification — `acs` / `acs-runtime`

- **rôles :** `competitor`, `supplier`, `complement`
- **résumé :** Primitive importante pour composer un concurrent, mais pas une chaîne Ring/Ring Cloud end-to-end à elle seule.
- **dernière observation :** `2026-10-07T06:55:52Z`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `prerelease`

##### Garanties Ring — `L1` 🟡 ISOLATED_PRIMITIVE

- **périmètre :** Runtime de décision policy déterministe ACS.
- **justification :** ACS fournit une primitive forte de décision mais délègue explicitement enforcement, approval resolution, identity computation et record keeping à l'hôte.
- **preuves :** `E-AC-001`, `E-AC-002`
- **confiance :** `high`
- **dépendances externes :** `agent-hooks host integration`

##### Signal Cloud — `L1` 🟡 ISOLATED_PRIMITIVE

- **périmètre :** Verdict et policy input évalué.
- **justification :** Le runtime peut exposer le signal de décision mais ne possède pas lui-même la persistance/record keeping nécessaire au signal longitudinal.
- **preuves :** `E-AC-001`, `E-AC-002`
- **confiance :** `high`
- **dépendances externes :** `host telemetry/storage`

##### Usages downstream — `L0` 🟢 ADJACENT_OR_COMPLEMENTARY

- **périmètre :** Usages longitudinaux Ring Cloud dans ACS.
- **justification :** ACS n'est pas une plateforme d'analytique ou d'apprentissage longitudinal.
- **preuves :** `E-AC-001`
- **confiance :** `high`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `limited` :** Policies déterministes, approval exprimable. Preuves : `E-AC-001`, `E-AC-002`. Lacunes : `Résolution d'approbation et identité sont à l'hôte.`.
- **R2 — `partial` :** Manifest/interception points structurent l'applicabilité. Preuves : `E-AC-001`, `E-AC-002`. Lacunes : `Complétude dépend de l'intégration hôte.`.
- **R3 — `unknown` :** Évolution autorisée des policies non évaluée ici. Preuves : aucun. Lacunes : `Évaluer governance des manifests/bundles.`.
- **R4 — `partial` :** Le policy_input exact est retourné. Preuves : `E-AC-001`, `E-AC-002`. Lacunes : `Liaison à l'état repo dépend de l'hôte.`.
- **R5 — `partial` :** Erreurs de runtime structurées. Preuves : `E-AC-001`, `E-AC-002`. Lacunes : `Décision finale dépend de l'hôte.`.
- **R6 — `limited` :** Runtime policy seulement. Preuves : `E-AC-001`, `E-AC-002`. Lacunes : `Pas d'administration repository end-to-end.`.
- **R7 — `partial` :** Manifest/policy input explicites. Preuves : `E-AC-001`, `E-AC-002`. Lacunes : `Provenance et lifecycle complets dépendent de l'hôte.`.
- **R8 — `limited` :** Contrat d'interception clair. Preuves : `E-AC-001`, `E-AC-002`. Lacunes : `Enforcement réel et approbation externes.`.
- **C1 — `partial` :** Verdict+policy input disponibles. Preuves : `E-AC-001`, `E-AC-002`. Lacunes : `Pas de record keeping natif.`.
- **C2 — `unknown` :** Pas de longitudinalité native établie. Preuves : aucun. Lacunes : `Hôte requis.`.
- **C3 — `unknown` :** Pas de labels de réparation natifs. Preuves : aucun. Lacunes : `Hôte/downstream requis.`.
- **C4 — `not_applicable` :** ACS est un runtime de policy, pas une plateforme d'analytics. Preuves : `E-AC-001`, `E-AC-002`. Lacunes : aucun.
- **C5 — `limited` :** Déterminisme favorise la reproduction. Preuves : `E-AC-001`, `E-AC-002`. Lacunes : `Persistance et contexte global à l'hôte.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `2026-10-07T06:55:52Z`
- **dernier contrôle de signal :** `2026-10-08T07:04:24Z`
- **dernière inspection de code :** `2026-10-07T06:55:52Z`
- **dernière évaluation :** `2026-10-07T06:55:52Z`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `permanent`
- **cycle de vie :** `active`
- **couverture :** `partial`
- **motif d’admission :** Piste initiale évaluée techniquement pendant cette baseline.
- **acteurs liés :** `microsoft-agt`
- **investigations en attente :**
- Évaluer une composition hôte concrète qui assume enforcement/approval/record keeping.

#### Chainloop — `chainloop` / `policies-attestation`

- **rôles :** `competitor`, `complement`, `supplier`
- **résumé :** Renforcement réel de la chaîne de preuves: vérification keyless par défaut lorsque configurée, requireTrace pre-push restauré en v1.118.1, GitLab commit verification plus honnête et capture des skills; limites configurables/host persistent. 🟠 L2 inchangé.
- **dernière observation :** `2026-10-08T07:04:24Z`
- **réévalué pendant ce passage :** `true`
- **disponibilité :** `released`

##### Garanties Ring — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** Policies attachées aux matériaux et attestations de supply-chain.
- **justification :** Chainloop fournit une chaîne substantielle policy→material→evaluation→gate avec références/digests, mais ne démontre pas que l'autorité et la complétude de ces policies représentent tout le sens produit gouverné.
- **preuves :** `E-CL-001`, `E-CL-002`, `E-20261008-CL-001`, `E-20261008-CL-003`
- **confiance :** `high`
- **dépendances externes :** aucun

##### Signal Cloud — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** PolicyEvaluation et attestation structurées.
- **justification :** Le signal est riche: matériau, policy digest/reference, requirements, skipped reasons, raw I/O, commit/auth/runner peuvent être conservés. L'autorité de l'évolution des exigences reste toutefois externe.
- **preuves :** `E-CL-001`, `E-CL-002`, `E-20261008-CL-001`, `E-20261008-CL-003`, `E-20261008-CL-005`, `E-20261008-CL-006`
- **confiance :** `high`
- **dépendances externes :** aucun

##### Usages downstream — `L1` 🟡 ISOLATED_PRIMITIVE

- **périmètre :** Réutilisation des attestations/policy results.
- **justification :** Les données sont exploitables pour audit et analyses, mais aucune sémantique générale repair-versus-authorized-revision et aucun programme d'apprentissage équivalent à Ring Cloud ne sont établis ici.
- **preuves :** `E-CL-001`, `E-CL-002`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `limited` :** Policies et contracts sont explicites. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Autorité de création/révision des exigences non établie par le verifier.`.
- **R2 — `supported` :** requiredPoliciesForMaterial et attachments structurent l'applicabilité déclarée. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Omission d'une policy pertinente reste possible si le contrat ne la déclare pas.`.
- **R3 — `limited` :** Références/digests rendent les versions observables. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Légitimité de la mutation non établie.`.
- **R4 — `partial` :** Matériaux digestés, commit head optionnel, references policy. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Commit optionnel et couverture de l'état gouvernant complète non garantie.`.
- **R5 — `partial` :** Pre-push requireTrace bloque les erreurs quand activé; la signature d’attestation est exigée avec keyless configuré/forced. Preuves : `E-CL-001`, `E-CL-002`, `E-20261008-CL-001`, `E-20261008-CL-002`, `E-20261008-CL-003`. Lacunes : `Hooks Git et binaire peuvent être absents; option requireTrace=false; ForceVerification désactivable; TrustConfigFault TSA laisse une vérification temporelle non établie.`.
- **R6 — `limited` :** Verifier/gating automatiques. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Administration produit/repository plus large hors périmètre.`.
- **R7 — `supported` :** Références, digests, raw results, runtime overrides. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Autorité sémantique des policies externe.`.
- **R8 — `partial` :** Attestation et policy engine composés. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Boundary d'autorité/host hors verifier.`.
- **C1 — `supported` :** Signal renforcé par refus push en absence de trace lorsque requireTrace=true, keyless verification sous configuration applicable, et skill materials. Preuves : `E-CL-001`, `E-CL-002`, `E-20261008-CL-003`, `E-20261008-CL-006`. Lacunes : `Une capture/validation non configurée ou contournée reste possible; aucune autorité générale sur revision des exigences.`.
- **C2 — `limited` :** Références/digests permettent comparaison de versions. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Repair versus authorized requirement revision non natif.`.
- **C3 — `partial` :** Violations/skips/requirements constituent des labels utiles. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Ils ne qualifient pas seuls la légitimité d'une révision.`.
- **C4 — `partial` :** Audit et exploitation d'attestations possibles. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Pas d'équivalence Ring Cloud complète établie.`.
- **C5 — `supported` :** Attestation/CAS/raw results et contexte runner/auth structurent reproductibilité/audit. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Réutilisation/licences des données non évaluées.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `2026-10-07T06:55:52Z`
- **dernier contrôle de signal :** `2026-10-08T07:04:24Z`
- **dernière inspection de code :** `2026-10-08T07:04:24Z`
- **dernière évaluation :** `2026-10-08T07:04:24Z`
- **prochaine échéance :** `2026-10-15T07:04:24Z`
- **statut de surveillance :** `permanent`
- **cycle de vie :** `active`
- **couverture :** `partial`
- **motif d’admission :** Piste initiale évaluée techniquement pendant cette baseline.
- **acteurs liés :** aucun
- **investigations en attente :**
- Auditer qui peut modifier les policy attachments/contracts et comment ces changements sont autorisés.
- Évaluer le lien exact entre attestation signée, commit final et gouvernance effective.

#### Entire — `entire` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### LangSmith — `langsmith` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Braintrust — `braintrust` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Langfuse — `langfuse` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Arize Phoenix — `phoenix` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### W&B Weave / Agent Lens — `weave` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Kiro — `kiro` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Augment Intent — `augment-intent` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### 8090 — `8090` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### CodeRabbit — `coderabbit` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Greptile — `greptile` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Endor Labs — `endor-labs` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Rippletide — `rippletide` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Google agent governance offerings — `google-agent-governance` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### GitHub agent platform and governance — `github-agent-platform` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### OpenAI Codex and agent tooling — `openai-codex` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Anthropic Claude Code — `anthropic-claude-code` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Imandra / CodeLogician / SpecLogician — `imandra` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Antithesis — `antithesis` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Open Policy Agent — `opa` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### in-toto — `in-toto` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Spec Kit — `spec-kit` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### OpenSpec — `openspec` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Jama Connect — `jama` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### StrongDM software factory — `strongdm-factory` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Prime Intellect — `prime-intellect` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### SWE-Gym — `swe-gym` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### SWE-smith — `swe-smith` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### R2E-Gym / DeepSWE — `r2e-gym` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Poolside — `poolside` / `unverified-seed`

- **rôles :** aucun
- **résumé :** Piste conservée dans le radar; aucune conclusion technique n'est tirée pendant ce passage.
- **dernière observation :** `null`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** Garanties Ring: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** Signal Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** Usages downstream Ring Cloud: aucune évaluation technique suffisante pendant cette baseline.
- **justification :** Le projet reste dans le radar permanent mais n'a pas été inspecté assez profondément pendant ce passage pour recevoir un niveau technique.
- **preuves :** aucun
- **confiance :** `low`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R6 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R7 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **R8 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C1 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C2 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C3 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C4 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.
- **C5 — `unknown` :** Non évalué sur cet axe pendant cette baseline. Preuves : aucun. Lacunes : `Non évalué pendant cette baseline.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `null`
- **dernier contrôle de signal :** `null`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `null`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `seed_pending`
- **cycle de vie :** `unknown`
- **couverture :** `not_checked`
- **motif d’admission :** Piste initiale du radar, identité/capacité à vérifier avant notation.
- **acteurs liés :** aucun
- **investigations en attente :**
- Établir l'identité canonique, les sources primaires et le périmètre technique avant toute notation.

#### Chock — `chock` / `chock-core`

- **rôles :** `competitor`, `complement`
- **résumé :** Correction de drift de toggle qui resserre les règles et contrôle Stop multi-workspaces; améliore disponibilité du gate et couverture, sans fermer l’autorité générale des politiques. 🟠 L2 inchangé.
- **dernière observation :** `2026-10-08T07:04:24Z`
- **réévalué pendant ce passage :** `true`
- **disponibilité :** `released`

##### Garanties Ring — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** Enforcement de politiques/guardrails, couverture déclarée, lockfile et drift.
- **justification :** Chock couvre de façon substantielle l'enforcement et l'intégrité de certaines politiques, avec un toggle human-controlled qui reste activé sous drift; il ne démontre pas une chaîne générale Product Intent→autorité→obligations→évolution autorisée.
- **preuves :** `E-CH-001`, `E-CH-002`, `E-CH-003`, `E-20261008-CH-001`, `E-20261008-CH-002`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Signal Cloud — `L1` 🟡 ISOLATED_PRIMITIVE

- **périmètre :** Évidence de couverture, gating et drift de politiques.
- **justification :** Le signal technique est utile mais aucune conservation longitudinale riche de l'autorité et des révisions n'est établie.
- **preuves :** `E-CH-001`, `E-CH-003`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Usages downstream — `L0` 🟢 ADJACENT_OR_COMPLEMENTARY

- **périmètre :** Analytique/apprentissage longitudinal dans le périmètre inspecté.
- **justification :** Aucune capacité downstream comparable à Ring Cloud n'a été établie pendant cette inspection.
- **preuves :** `E-CH-001`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `partial` :** Toggle de guardrails explicitement human-controlled. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Gouvernance générale des changements de policy non établie.`.
- **R2 — `partial` :** Coverage ladder et compilations multi-surfaces. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Complétude des obligations gouvernées non démontrée.`.
- **R3 — `partial` :** Drift détecté; guardrail toggle protégé. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Autorité des modifications de policy hors toggle non établie.`.
- **R4 — `partial` :** Hashes/lockfile lient sources et compilés. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Liaison complète à l'état repository accepté non établie.`.
- **R5 — `supported` :** Suppression tighten-only tolérée, fallback relâché refusé; contrôle Stop sur plusieurs racines. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`, `E-20261008-CH-001`, `E-20261008-CH-002`. Lacunes : `Contrôles bornés par les roots visibles dans le hook et la portée du gate; autorité générale de policy encore non établie.`.
- **R6 — `partial` :** CLI et hooks administrent enforcement. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Remédiation gouvernée générale non démontrée.`.
- **R7 — `supported` :** Digests/lockfile/drift explicites. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Autorité sémantique des changements distincte de l'intégrité.`.
- **R8 — `partial` :** Suppression tighten-only tolérée, fallback relâché refusé; contrôle Stop sur plusieurs racines. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`, `E-20261008-CH-001`, `E-20261008-CH-002`. Lacunes : `Contrôles bornés par les roots visibles dans le hook et la portée du gate; autorité générale de policy encore non établie.`.
- **C1 — `partial` :** Évidence de policy/coverage/gates. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Contexte d'autorité complet non capturé.`.
- **C2 — `limited` :** Lockfile permet de suivre certains changements. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Repair/revision/weakening non distingués génériquement.`.
- **C3 — `unknown` :** Pas de label d'apprentissage gouverné évalué. Preuves : aucun. Lacunes : `Évaluer les exports/événements éventuels.`.
- **C4 — `unknown` :** Pas d'usage longitudinal évalué. Preuves : aucun. Lacunes : `Évaluer les surfaces analytiques éventuelles.`.
- **C5 — `partial` :** Hashes et evidence basis structurent la reproductibilité. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Rétention/autorisation downstream non évaluées.`.

##### Surveillance

- **première observation :** `2026-10-07T06:55:52Z`
- **première évaluation :** `2026-10-07T06:55:52Z`
- **dernier contrôle de signal :** `2026-10-08T07:04:24Z`
- **dernière inspection de code :** `2026-10-08T07:04:24Z`
- **dernière évaluation :** `2026-10-08T07:04:24Z`
- **prochaine échéance :** `2026-10-15T07:04:24Z`
- **statut de surveillance :** `permanent`
- **cycle de vie :** `active`
- **couverture :** `partial`
- **motif d’admission :** Nouvel entrant découvert et évalué pendant cette baseline.
- **acteurs liés :** aucun
- **investigations en attente :**
- Auditer l'autorité de modification des policies hors guardrail toggle.
- Tester exact-state binding entre enforcement et commit final.

#### DynosAI — `dynosai` / `dynosai-core`

- **rôles :** `competitor`
- **résumé :** Nouvel entrant important: architecture très proche du problème de développement gouverné, mais une frontière d'autorité concrète reste ouverte dans le chemin MCP inspecté.
- **dernière observation :** `2026-10-07T06:55:52Z`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `released`

##### Garanties Ring — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** Workflow de développement gouverné et preuves de travail dans le périmètre inspecté.
- **justification :** DynosAI possède une chaîne substantielle spec/plan/gates/scope/validation/evidence, mais le chemin agent-callable dynosai_register_decision peut enregistrer directement une décision comme accepted, ce qui laisse un écart décisif sur l'autorité et l'évolution du sens gouverné.
- **preuves :** `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Signal Cloud — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** État, gates, validations, audit et preuves de trajectoire DynosAI.
- **justification :** Le système conserve un signal structuré substantiel, mais sa validité comme signal de gouvernance générale est limitée par le même écart d'autorité sur les décisions et par l'absence de démonstration end-to-end de réparation versus affaiblissement d'exigence.
- **preuves :** `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Usages downstream — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** Évaluation et exploitation du signal DynosAI dans le périmètre public inspecté.
- **justification :** DynosAI contient des surfaces d'eval intelligence, d'attribution des échecs et de validation structurée; aucune équivalence complète avec les opportunités longitudinales de Ring Cloud n'est établie.
- **preuves :** `E-DY-001`, `E-DY-002`, `E-DY-003`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `partial` :** Gates humains explicites, mais dynosai_register_decision reste agent-callable et marque accepted. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Fermer la frontière d'autorité des décisions enregistrées.`.
- **R2 — `partial` :** Chaînes requirement/acceptance/task/evidence structurées. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Établir la complétude d'applicabilité au-delà des éléments déclarés.`.
- **R3 — `limited` :** Spec/plan versionnés et revus; décision agent-callable affaiblit la séparation proposition/acceptation. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Autorité de révision des décisions/exigences non fermée de bout en bout.`.
- **R4 — `partial` :** Git/worktree, runs et vérification structurée lient une partie de l'état. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Établir la liaison de toutes les prémisses gouvernantes à l'état accepté.`.
- **R5 — `partial` :** Blocages/gates/validation existent. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Cartographier tous les chemins d'indétermination et fail-closed.`.
- **R6 — `supported` :** Le système administre workflow, Git, scopes et validation via ses primitives. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Portée bornée par les validations/configurations déclarées.`.
- **R7 — `supported` :** SQLite autoritatif pour le workflow, Git pour le code, vues dérivées. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Vérifier les transitions de décision autoritative.`.
- **R8 — `partial` :** Contrôleur central et Git guard couvrent beaucoup de frontières. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Évaluer les bypass et la propre évolution des règles/decisions.`.
- **C1 — `partial` :** Gates/runs/audit/validations donnent un signal observation-time. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Validité du signal compromise si l'autorité de décision est auto-attribuable.`.
- **C2 — `limited` :** Historique de runs et décisions persiste. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Distinction générale repair/authorized revision/weakening non établie.`.
- **C3 — `partial` :** Preuves et classification d'échecs structurées. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Labels d'autorité/revision à renforcer.`.
- **C4 — `partial` :** Surfaces d'eval intelligence et métriques présentes. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Pas d'équivalence démontrée aux analyses longitudinales Ring Cloud.`.
- **C5 — `partial` :** Durabilité locale, snapshots, audit. Preuves : `E-DY-001`, `E-DY-002`, `E-DY-003`, `E-DY-004`, `E-DY-005`. Lacunes : `Droits de réutilisation et reproductibilité globale non évalués.`.

##### Surveillance

- **première observation :** `2026-10-07T06:55:52Z`
- **première évaluation :** `2026-10-07T06:55:52Z`
- **dernier contrôle de signal :** `2026-10-08T07:04:24Z`
- **dernière inspection de code :** `2026-10-07T06:55:52Z`
- **dernière évaluation :** `2026-10-07T06:55:52Z`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `permanent`
- **cycle de vie :** `active`
- **couverture :** `partial`
- **motif d’admission :** Nouvel entrant découvert et évalué pendant cette baseline.
- **acteurs liés :** aucun
- **investigations en attente :**
- Vérifier si un composant non inspecté peut empêcher structurellement l'agent d'utiliser dynosai_register_decision comme autorité.
- Tester les scénarios de révision d'exigence versus réparation.

#### Vectimus — `vectimus` / `vectimus-core`

- **rôles :** `competitor`, `complement`
- **résumé :** Nouvel entrant sérieux sur policy-as-code et receipts; l'autorité de l'évolution des policies et la durabilité du signal restent les écarts principaux.
- **dernière observation :** `2026-10-07T06:55:52Z`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `released`

##### Garanties Ring — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** Pré-action policy enforcement et escalation dans les hooks inspectés.
- **justification :** Vectimus fournit une véritable frontière d'enforcement et échoue fermé sur certaines erreurs, mais les politiques peuvent être remplacées/désactivées et aucune chaîne générale d'autorité sur ces changements n'a été établie.
- **preuves :** `E-VE-001`, `E-VE-003`, `E-VE-004`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Signal Cloud — `L1` 🟡 ISOLATED_PRIMITIVE

- **périmètre :** Receipts et audit liés à l'action/policy set.
- **justification :** Les receipts sont une primitive utile de signal mais leur génération est optionnelle, asynchrone/best-effort, peut rester non signée et la rétention locale par défaut est courte.
- **preuves :** `E-VE-001`, `E-VE-002`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Usages downstream — `L0` 🟢 ADJACENT_OR_COMPLEMENTARY

- **périmètre :** Analytique/apprentissage longitudinal dans le périmètre inspecté.
- **justification :** Aucune exploitation longitudinalement équivalente à Ring Cloud n'est démontrée dans le code inspecté.
- **preuves :** `E-VE-001`, `E-VE-002`
- **confiance :** `medium`
- **dépendances externes :** aucun

##### Axes R1–R8 et C1–C5

- **R1 — `limited` :** Escalation vers humain existe. Preuves : `E-VE-001`, `E-VE-002`, `E-VE-003`, `E-VE-004`. Lacunes : `Autorité des mutations de policy/config non établie.`.
- **R2 — `supported` :** Cedar policies actives évaluées avant action. Preuves : `E-VE-001`, `E-VE-002`, `E-VE-003`, `E-VE-004`. Lacunes : `Complétude des policies pertinentes non démontrée.`.
- **R3 — `limited` :** Packs projet et disables modifient l'ensemble effectif. Preuves : `E-VE-001`, `E-VE-002`, `E-VE-003`, `E-VE-004`. Lacunes : `Pas de lineage d'autorité démontré pour ces mutations.`.
- **R4 — `partial` :** Contexte d'action et policy set sont hashés dans le receipt. Preuves : `E-VE-001`, `E-VE-002`, `E-VE-003`, `E-VE-004`. Lacunes : `Pas de liaison générale au repository state accepté.`.
- **R5 — `supported` :** Normalisation fail-closed; escalation deny locale. Preuves : `E-VE-001`, `E-VE-002`, `E-VE-003`, `E-VE-004`. Lacunes : `Évaluer tous les fallbacks serveur/daemon.`.
- **R6 — `partial` :** CLI/hook administre les policies. Preuves : `E-VE-001`, `E-VE-002`, `E-VE-003`, `E-VE-004`. Lacunes : `Remédiation repository gouvernée non démontrée.`.
- **R7 — `partial` :** Receipts signables et hashes. Preuves : `E-VE-001`, `E-VE-002`, `E-VE-003`, `E-VE-004`. Lacunes : `Receipt optionnel/best-effort et policy mutation authority manquante.`.
- **R8 — `partial` :** Hook avant action et fallback local. Preuves : `E-VE-001`, `E-VE-002`, `E-VE-003`, `E-VE-004`. Lacunes : `Frontière serveur et disable/config à approfondir.`.
- **C1 — `partial` :** Receipts capturent contexte et policy-set hash. Preuves : `E-VE-001`, `E-VE-002`, `E-VE-003`, `E-VE-004`. Lacunes : `Capture optionnelle/asynchrone et parfois non signée.`.
- **C2 — `limited` :** Receipts historiques possibles. Preuves : `E-VE-001`, `E-VE-002`, `E-VE-003`, `E-VE-004`. Lacunes : `Rétention par défaut 7 jours et pas de semantics de revision produit.`.
- **C3 — `unknown` :** Pas de labels de réparation évalués. Preuves : aucun. Lacunes : `À investiguer.`.
- **C4 — `unknown` :** Pas de downstream équivalent évalué. Preuves : aucun. Lacunes : `À investiguer.`.
- **C5 — `limited` :** Cryptographie et canonical JSON utiles. Preuves : `E-VE-001`, `E-VE-002`, `E-VE-003`, `E-VE-004`. Lacunes : `Écriture/rétention best-effort et droits non évalués.`.

##### Surveillance

- **première observation :** `2026-10-07T06:55:52Z`
- **première évaluation :** `2026-10-07T06:55:52Z`
- **dernier contrôle de signal :** `2026-10-08T07:04:24Z`
- **dernière inspection de code :** `2026-10-07T06:55:52Z`
- **dernière évaluation :** `2026-10-07T06:55:52Z`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
- **statut de surveillance :** `permanent`
- **cycle de vie :** `active`
- **couverture :** `partial`
- **motif d’admission :** Nouvel entrant découvert et évalué pendant cette baseline.
- **acteurs liés :** aucun
- **investigations en attente :**
- Auditer autorité des rule disables/project packs.
- Évaluer garanties du mode serveur et perte de receipt asynchrone.

#### AgentOps (boshu2/agentops) — `agentops` / `agentops-evidence-core`

- **rôles :** `competitor`, `complement`, `supplier`
- **résumé :** Nouvel acteur substantiel sur exact acceptance + exact subject + independent verdict NOT_PROVEN; pas une gouvernance end-to-end de l’évolution du Product Intent.
- **dernière observation :** `2026-10-08T07:04:24Z`
- **réévalué pendant ce passage :** `true`
- **disponibilité :** `unknown`

##### Garanties Ring — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** Validation indépendante liée à l’acceptance exacte et au contenu exact; non à toute l’administration d’un repository.
- **justification :** StoreVerdict et VerifySubject lient intent/acceptance digest, manifest du sujet, identités et verdict; PASS exige preuves/freshness. Mais l’autorité d’acceptance et la décision de merge sont explicitement laissées au caller; les evidence references ne sont pas validées sémantiquement par VerifySubject.
- **preuves :** `E-20261008-AG-001`, `E-20261008-AG-002`, `E-20261008-AG-003`, `E-20261008-AG-004`
- **confiance :** `high`
- **dépendances externes :** `caller-owned acceptance authority`, `external Git/CI/enforcement`

##### Signal Cloud — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** Verdicts structurés, content-addressed et liés à un sujet et une acceptance précis.
- **justification :** La primitive de verdict PASS/FAIL/NOT_PROVEN et de stockage content-addressed peut produire un signal vérifiable au niveau structurel. La qualité du jugement sémantique, la capture obligatoire, la retention et l’autorité des changements d’acceptance ne sont pas garanties par ce seul mécanisme.
- **preuves :** `E-20261008-AG-001`, `E-20261008-AG-002`, `E-20261008-AG-003`
- **confiance :** `high`
- **dépendances externes :** `caller storage protections`

##### Usages downstream — `L1` 🟡 ISOLATED_PRIMITIVE

- **périmètre :** Analyse optionnelle de verdicts dans un workflow qui ne possède pas le produit Ring Cloud.
- **justification :** Le corpus de verdicts peut alimenter Learn et des évaluations; aucune exploitation longitudinale gouvernée complète n’est démontrée.
- **preuves :** `E-20261008-AG-001`, `E-20261008-AG-004`
- **confiance :** `medium`
- **dépendances externes :** `external corpus and analytics`

##### Axes R1–R8 et C1–C5

- **R1 — `partial` :** Acceptance explicite appartenant au caller. Preuves : `E-20261008-AG-004`. Lacunes : `Autorité des changements d’acceptance et politiques de repository externes.`.
- **R2 — `unknown` :** Aucune vérification suffisante sur cet axe. Preuves : aucun. Lacunes : `Vérification technique à réaliser.`.
- **R3 — `partial` :** Le verdict compare un état à une acceptance déterminée, sans choisir les révisions. Preuves : `E-20261008-AG-002`, `E-20261008-AG-004`. Lacunes : `Différenciation complète legitimate revision/unauthorized weakening repose sur la source d’intent.`.
- **R4 — `supported` :** Manifest exact et digest intent/acceptance sont comparés au sujet courant. Preuves : `E-20261008-AG-002`. Lacunes : `Le jugement sémantique n’est pas établi par le hash seul.`.
- **R5 — `supported` :** PASS soumis à identités distinctes, freshness, preuves et checked scope complet, sinon NOT_PROVEN. Preuves : `E-20261008-AG-003`. Lacunes : `Attestation de fraîcheur déclarative, pas isolement cryptographique.`.
- **R6 — `limited` :** Stockage et vérification de verdicts; Git/CI/release restent à l’hôte. Preuves : `E-20261008-AG-001`. Lacunes : `Pas de Ring agent-facing governance administrative complète.`.
- **R7 — `partial` :** Artefacts content-addressed, verification digest/manifest. Preuves : `E-20261008-AG-002`. Lacunes : `Liens sémantiques des preuves non validés par VerifySubject.`.
- **R8 — `limited` :** Le caller doit appliquer le verdict; AgentOps ne contrôle pas l’admission du changement en repository. Preuves : `E-20261008-AG-001`, `E-20261008-AG-002`. Lacunes : `Bypass ou changement d’acceptance externe au mécanisme.`.
- **C1 — `partial` :** Verdict content-addressed avec sujet, acceptance et limite connue. Preuves : `E-20261008-AG-002`. Lacunes : `Capturé seulement quand caller utilise StoreVerdict.`.
- **C2 — `limited` :** Les digests permettent de retrouver exactement quelle acceptance fut jugée. Preuves : `E-20261008-AG-004`. Lacunes : `Ne qualifie pas automatiquement la légitimité d’une révision de cette acceptance.`.
- **C3 — `partial` :** PASS/FAIL/NOT_PROVEN, critères et evidence_refs structurés. Preuves : `E-20261008-AG-003`. Lacunes : `La correction réelle des labels dépend encore du reviewer et de la vérifiabilité des preuves.`.
- **C4 — `limited` :** Learn optionnel documenté. Preuves : `E-20261008-AG-001`. Lacunes : `Aucune chaîne longitudinale équivalente prouvée.`.
- **C5 — `partial` :** Stockage content-addressed et vérification du sujet. Preuves : `E-20261008-AG-002`. Lacunes : `Rétention et droits d’usage laissés au caller.`.

##### Surveillance

- **première observation :** `2026-10-08T07:04:24Z`
- **première évaluation :** `2026-10-08T07:04:24Z`
- **dernier contrôle de signal :** `2026-10-08T07:04:24Z`
- **dernière inspection de code :** `2026-10-08T07:04:24Z`
- **dernière évaluation :** `2026-10-08T07:04:24Z`
- **prochaine échéance :** `2026-10-15T07:04:24Z`
- **statut de surveillance :** `permanent`
- **cycle de vie :** `active`
- **couverture :** `partial`
- **motif d’admission :** Découvert par recherche ouverte et évalué sur code source à une révision immuable.
- **acteurs liés :** aucun
- **investigations en attente :**
- Auditer les chemins natifs autour de l’attestation d’indépendance et des evidence references.
- Évaluer comment le caller peut modifier acceptance et si un pipeline réel empêche cette modification sans autorité.
- Vérifier availability/releases et tests exécutables.

#### GitLab Governed Software Factory / Governance for Agents — `gitlab-governed-factory` / `duo-agent-governance-and-factory`

- **rôles :** `competitor`, `research`, `signal_consumer`
- **résumé :** Acteur entrant dans le radar sur communications officielles préexistantes au rapport précédent; aucune couleur technique positive accordée avant vérification de code/composition.
- **dernière observation :** `2026-10-08T07:04:24Z`
- **réévalué pendant ce passage :** `false`
- **disponibilité :** `unknown`

##### Garanties Ring — `U` ⚪ INDETERMINATE

- **périmètre :** GitLab Governed Software Factory / Governance for Agents : aucune vérification end-to-end du composant déployé.
- **justification :** Communiqués officiels et produits à stades beta/early access ou GA différents; code ni tests du contrôle agentique inspectés. Aucune équivalence de garanties/labels ne peut être déclarée sur cette base.
- **preuves :** `E-20261008-GL-001`, `E-20261008-GL-002`
- **confiance :** `low`
- **dépendances externes :** `GitLab platform and commercial features not audited`

##### Signal Cloud — `U` ⚪ INDETERMINATE

- **périmètre :** GitLab Governed Software Factory / Governance for Agents : aucune vérification end-to-end du composant déployé.
- **justification :** Communiqués officiels et produits à stades beta/early access ou GA différents; code ni tests du contrôle agentique inspectés. Aucune équivalence de garanties/labels ne peut être déclarée sur cette base.
- **preuves :** `E-20261008-GL-001`, `E-20261008-GL-002`
- **confiance :** `low`
- **dépendances externes :** `GitLab platform and commercial features not audited`

##### Usages downstream — `U` ⚪ INDETERMINATE

- **périmètre :** GitLab Governed Software Factory / Governance for Agents : aucune vérification end-to-end du composant déployé.
- **justification :** Communiqués officiels et produits à stades beta/early access ou GA différents; code ni tests du contrôle agentique inspectés. Aucune équivalence de garanties/labels ne peut être déclarée sur cette base.
- **preuves :** `E-20261008-GL-001`, `E-20261008-GL-002`
- **confiance :** `low`
- **dépendances externes :** `GitLab platform and commercial features not audited`

##### Axes R1–R8 et C1–C5

- **R1 — `announced` :** GitLab annonce identité, policies et approvals autour des agents. Preuves : `E-20261008-GL-002`. Lacunes : `Vérifier code, disponibilités et chemin concret d’acceptation.`.
- **R2 — `unknown` :** Aucune vérification suffisante sur cet axe. Preuves : aucun. Lacunes : `Vérification technique à réaliser.`.
- **R3 — `unknown` :** Aucune vérification suffisante sur cet axe. Preuves : aucun. Lacunes : `Vérification technique à réaliser.`.
- **R4 — `unknown` :** Aucune vérification suffisante sur cet axe. Preuves : aucun. Lacunes : `Vérification technique à réaliser.`.
- **R5 — `unknown` :** Aucune vérification suffisante sur cet axe. Preuves : aucun. Lacunes : `Vérification technique à réaliser.`.
- **R6 — `unknown` :** Aucune vérification suffisante sur cet axe. Preuves : aucun. Lacunes : `Vérification technique à réaliser.`.
- **R7 — `unknown` :** Aucune vérification suffisante sur cet axe. Preuves : aucun. Lacunes : `Vérification technique à réaliser.`.
- **R8 — `announced` :** GitLab annonce une chaîne plateforme sous politiques organisationnelles. Preuves : `E-20261008-GL-001`. Lacunes : `Contrôle end-to-end non vérifié.`.
- **C1 — `unknown` :** Aucune vérification suffisante sur cet axe. Preuves : aucun. Lacunes : `Vérification technique à réaliser.`.
- **C2 — `unknown` :** Aucune vérification suffisante sur cet axe. Preuves : aucun. Lacunes : `Vérification technique à réaliser.`.
- **C3 — `unknown` :** Aucune vérification suffisante sur cet axe. Preuves : aucun. Lacunes : `Vérification technique à réaliser.`.
- **C4 — `announced` :** GitLab présente Impact Analytics en early access pour coûts et résultats. Preuves : `E-20261008-GL-001`. Lacunes : `Ne prouve pas annotations longitudinales repair/authorized revision/weakening.`.
- **C5 — `unknown` :** Aucune vérification suffisante sur cet axe. Preuves : aucun. Lacunes : `Vérification technique à réaliser.`.

##### Surveillance

- **première observation :** `2026-10-08T07:04:24Z`
- **première évaluation :** `2026-10-08T07:04:24Z`
- **dernier contrôle de signal :** `2026-10-08T07:04:24Z`
- **dernière inspection de code :** `null`
- **dernière évaluation :** `2026-10-08T07:04:24Z`
- **prochaine échéance :** `2026-10-15T07:04:24Z`
- **statut de surveillance :** `permanent`
- **cycle de vie :** `active`
- **couverture :** `partial`
- **motif d’admission :** Identité réelle confirmée par source primaire; première évaluation documentaire bornée, code non inspecté.
- **acteurs liés :** aucun
- **investigations en attente :**
- Décomposer GitLab Duo Agent Platform, Governance for Agents et Security Standard en composants et versions vérifiables.
- Inspecter code ouvert et tests de policy/approval/audit et définir ce qui reste fermé.
- Ne pas confondre annonce du 6 octobre avec une évolution survenue depuis la baseline du 7 octobre.

## 4. Évolutions techniques et constats

### RCW-F-009 — D1 canonical persistence published in mneme-hq v0.10.0; DG1 still pending

- **acteur / composant :** `mneme` / `mneme-core`
- **cycle de vie :** `strengthened`
- **causes de changement :** `implementation_change`
- **constats précédents :** `RCW-20261007T065552Z#RCW-F-003`
- **axes :** `R1`, `R3`, `R7`, `C1`
- **preuves :** `E-20261008-MN-001`, `E-20261008-MN-002`, `E-20261008-MN-003`
- **changement observé :** Mneme a fusionné D1E5 (init/setup canonical), D1E6 (parity/golden evidence) puis publié v0.10.0 le 7 octobre 2026. La chaîne canonique D1 passe en produit publié; DG1 reste explicitement post-D1.
- **effet sur les garanties :** Renforcement réel de l’autorité/persistance/version identity, mais pas de la résolution générale de la décision effective. Ring reste L2.
- **effet downstream :** Signal plus stable par version de décision et identité de règle; catégories longitudinales repair/revision/weakening non complètes.
- **lacune restante :** DG1: applicability/precedence/waivers/effective decision; trust attestation des tests.
- **prochaine investigation :** Suivre premiers commits/PR DG1 et distinguer annonce, merge et code effectivement disponible.

### RCW-F-010 — Configured keyless mode verifies pushed attestations before CAS; explicit TSA and opt-out boundaries

- **acteur / composant :** `chainloop` / `policies-attestation`
- **cycle de vie :** `strengthened`
- **causes de changement :** `implementation_change`
- **constats précédents :** `RCW-20261007T065552Z#RCW-F-008`
- **axes :** `R4`, `R5`, `R7`, `C1`, `C5`
- **preuves :** `E-20261008-CL-003`, `E-20261008-CL-004`
- **changement observé :** La PR #3529 vérifie avant persistance signature, CA acceptée et organisation du workflow en mode keyless configuré (forced par défaut); les signatures non conformes sont refusées. L’option forceVerification=false et une exception TSA TrustConfigFault sont explicites.
- **effet sur les garanties :** Chaîne de preuve renforcée contre attestation non vérifiée, sous configuration keyless; pas d’autorité Produit Intent sur la policy applicable.
- **effet downstream :** Meilleure authenticité du signal d’attestation dans le mode configuré, mais ne pas inférer preuve de timestamp lorsqu’un TrustConfigFault est toléré.
- **lacune restante :** Aucune vérification si keyless non configuré; opt-out; TSA indéterminé exceptionnel; mutation des policy attachments.
- **prochaine investigation :** Tester les chemins forceVerification=false, no-keyless et TSA TrustConfigFault; vérifier la pertinence des trust roots.

### RCW-F-011 — requireTrace pre-push gate restored; missing-binary bypass remains

- **acteur / composant :** `chainloop` / `policies-attestation`
- **cycle de vie :** `strengthened`
- **causes de changement :** `implementation_change`
- **constats précédents :** `RCW-20261007T065552Z#RCW-F-008`
- **axes :** `R5`, `R8`, `C1`, `C5`
- **preuves :** `E-20261008-CL-001`, `E-20261008-CL-002`, `E-20261008-CL-007`
- **changement observé :** PR #3555, incluse dans release v1.118.1, corrige le script pre-push qui terminait sur exit 0 et laissait passer un push quand upload trace échouait malgré requireTrace=true. Le nouveau hook propage le statut non nul; une absence du binaire chainloop garde un exit 0.
- **effet sur les garanties :** Un défaut matériel de fail-closed est réparé sous requireTrace=true et hook actif; cela ne garantit pas tout le chemin si binaire/hook est absent.
- **effet downstream :** Réduit les fausses réussites où la capture était supposée obligatoire mais manquait; l’intégralité du signal n’est pas démontrée sans contrôle de l’installation.
- **lacune restante :** Hook installé/trusté et binaire présent; requireTrace désactivable; couverture des sessions non observées.
- **prochaine investigation :** Vérifier tests de migration des hooks et simuler push sans binaire ou hook installé.

### RCW-F-012 — Trace enriches skill provenance; GitLab commit unverifiable distinguished from unsigned

- **acteur / composant :** `chainloop` / `policies-attestation`
- **cycle de vie :** `strengthened`
- **causes de changement :** `implementation_change`
- **constats précédents :** `RCW-20261007T065552Z#RCW-F-008`
- **axes :** `R4`, `R5`, `C1`, `C3`, `C5`
- **preuves :** `E-20261008-CL-005`, `E-20261008-CL-006`
- **changement observé :** PR #3550 distingue GitLab 404 signature-not-found de project/commit inaccessible (unavailable), précise token read_api; PR #3551 capture certains skills utilisés et artefacts hashés au moment de l’usage, avec trous documentés (skills sans dossier, limites).
- **effet sur les garanties :** Provenance et inconnus d’observation plus précis, mais aucun sens produit supplémentaire n’est prouvé.
- **effet downstream :** Meilleure information sur contexte agent et signature commit; non équivalence à un label de réparation gouvernée.
- **lacune restante :** Skill no-folder/limites, vérification commit propre à chaque plateforme, autorité des règles non établie.
- **prochaine investigation :** Lire tests de provenance skills et vérifier si les champs sont effectivement capturés à temps pour toutes les surfaces.

### RCW-F-013 — Turn-end drift improves tightening-only deletion and multi-repository scope

- **acteur / composant :** `chock` / `chock-core`
- **cycle de vie :** `strengthened`
- **causes de changement :** `implementation_change`
- **constats précédents :** `RCW-20261007T065552Z#RCW-F-004`
- **axes :** `R5`, `R8`
- **preuves :** `E-20261008-CH-001`, `E-20261008-CH-002`, `E-20261008-CH-003`
- **changement observé :** PR #245 fusionnée le 7 octobre: suppression de toggle tighten-only ne refuse plus le Stop et nettoie record; fallback qui relâche refuse. Stop évalue plusieurs racines de workspace et retient le verdict le plus sévère.
- **effet sur les garanties :** Corrige à la fois faux refus et trous de couverture observés; ne démontre pas autorité générale de révision de la policy.
- **effet downstream :** Signaux de gate moins faussés par un resserrement de garde-fou; sémantique longitudinale limitée.
- **lacune restante :** Intégration hook et champ d’observation, droit de mutation des policies hors toggle.
- **prochaine investigation :** Inspecter tests pour suppression avec fallback user non vérifié et pour roots multi-repository.

### RCW-F-014 — Content-bound independent verdict PASS/FAIL/NOT_PROVEN is real scoped prior art

- **acteur / composant :** `agentops` / `agentops-evidence-core`
- **cycle de vie :** `new`
- **causes de changement :** `new_evidence`
- **constats précédents :** aucun
- **axes :** `R1`, `R3`, `R4`, `R5`, `R7`, `C1`, `C2`, `C3`
- **preuves :** `E-20261008-AG-001`, `E-20261008-AG-002`, `E-20261008-AG-003`, `E-20261008-AG-004`
- **changement observé :** Découverte et inspection du code AgentOps: StoreVerdict lie l’acceptance et le sujet exact, VerifySubject contrôle digests et PASS; validatePass refuse identité auteur/validator identique, preuve absente, not_checked non vide.
- **effet sur les garanties :** Substitut L2 significatif sur validation indépendante strictement liée au contenu; autorité de changement d’acceptance et admission finale demeurent externes.
- **effet downstream :** Verdicts content-addressed exploitables; aucune chaîne Ring Cloud longitudinale complète établie.
- **lacune restante :** Références de preuve non sémantiquement jugées par VerifySubject; identité/freshness attested par caller/runtime; acceptance authority externe.
- **prochaine investigation :** Auditer les chemins de corruption/tampering des evidence references et une intégration repository réelle.

### RCW-F-015 — GitLab governed software factory surfaced from official but earlier announcement

- **acteur / composant :** `gitlab-governed-factory` / `duo-agent-governance-and-factory`
- **cycle de vie :** `new`
- **causes de changement :** `new_evidence`
- **constats précédents :** aucun
- **axes :** `R1`, `R8`, `C1`, `C4`
- **preuves :** `E-20261008-GL-001`, `E-20261008-GL-002`
- **changement observé :** Communiqué GitLab du 6 octobre trouvé lors de la découverte ouverte du 8 octobre, avec Governance for Agents déjà annoncée en juin en private beta; disponibilité hétérogène.
- **effet sur les garanties :** Le vocabulaire organisationnel et les claims de contrôle nécessitent une investigation. Aucun niveau L1+ attribué faute de code/composition vérifiée.
- **effet downstream :** Impact Analytics annoncé en early access, sans preuve de labels Ring Cloud. Aucun progrès entre 7 et 8 octobre démontré par cette nouvelle découverte.
- **lacune restante :** Composants/version/déploiement et sémantique de l’autorité de révision des exigences non vérifiés.
- **prochaine investigation :** Isoler un composant GitLab accessible et auditer la véritable chaîne policy→approval→merge→evidence.

## 5. Recherche de nouveaux entrants et compositions

- **statut de découverte :** `partial`
- **acteurs admis :** `agentops`, `gitlab-governed-factory`
- **nouveaux entrants :** `agentops`, `gitlab-governed-factory`

### Recherches réellement effectuées

1. **web search and GitHub code/repository discovery** — `2026-10-08T07:04:24Z` — couverture `partial`
   - Requête : MnemeHQ mneme GitHub October 7 8 2026 D1 DG1 release pull requests
   - Résultat : Recherche effectuée pendant ce passage; horodatage agrégé de clôture du rapport (heure précise individuelle non enregistrée), non une preuve d’exhaustivité.
   - Preuves : aucun
2. **web search and GitHub code/repository discovery** — `2026-10-08T07:04:24Z` — couverture `partial`
   - Requête : pablo-cano dynosai github October 2026 MCP decision approval
   - Résultat : Recherche effectuée pendant ce passage; horodatage agrégé de clôture du rapport (heure précise individuelle non enregistrée), non une preuve d’exhaustivité.
   - Preuves : aucun
3. **web search and GitHub code/repository discovery** — `2026-10-08T07:04:24Z` — couverture `partial`
   - Requête : open-coder-ai chock releases governance October 2026
   - Résultat : Recherche effectuée pendant ce passage; horodatage agrégé de clôture du rapport (heure précise individuelle non enregistrée), non une preuve d’exhaustivité.
   - Preuves : aucun
4. **web search and GitHub code/repository discovery** — `2026-10-08T07:04:24Z` — couverture `partial`
   - Requête : vectimus policy receipts agent governance Oct 2026 release
   - Résultat : Recherche effectuée pendant ce passage; horodatage agrégé de clôture du rapport (heure précise individuelle non enregistrée), non une preuve d’exhaustivité.
   - Preuves : aucun
5. **web search and GitHub code/repository discovery** — `2026-10-08T07:04:24Z` — couverture `partial`
   - Requête : chainloop-dev chainloop updates October 2026 attestation policy authorization
   - Résultat : Recherche effectuée pendant ce passage; horodatage agrégé de clôture du rapport (heure précise individuelle non enregistrée), non une preuve d’exhaustivité.
   - Preuves : aucun
6. **web search and GitHub code/repository discovery** — `2026-10-08T07:04:24Z` — couverture `partial`
   - Requête : agent governance requirement drift tests coding agents new open source October 2026
   - Résultat : Recherche effectuée pendant ce passage; horodatage agrégé de clôture du rapport (heure précise individuelle non enregistrée), non une preuve d’exhaustivité.
   - Preuves : aucun
7. **web search and GitHub code/repository discovery** — `2026-10-08T07:04:24Z` — couverture `partial`
   - Requête : autonomous coding agent spec intent governance policy evidence gate tool new
   - Résultat : Recherche effectuée pendant ce passage; horodatage agrégé de clôture du rapport (heure précise individuelle non enregistrée), non une preuve d’exhaustivité.
   - Preuves : aucun
8. **web search and GitHub code/repository discovery** — `2026-10-08T07:04:24Z` — couverture `partial`
   - Requête : new github repositories requirements approval agents policy governance evidence October 2026
   - Résultat : Recherche effectuée pendant ce passage; horodatage agrégé de clôture du rapport (heure précise individuelle non enregistrée), non une preuve d’exhaustivité.
   - Preuves : aucun
9. **web search and GitHub code/repository discovery** — `2026-10-08T07:04:24Z` — couverture `partial`
   - Requête : GitLab announces foundation for governed software factory October 8 2026 official
   - Résultat : Recherche effectuée pendant ce passage; horodatage agrégé de clôture du rapport (heure précise individuelle non enregistrée), non une preuve d’exhaustivité.
   - Preuves : `E-20261008-GL-001`
10. **web search and GitHub code/repository discovery** — `2026-10-08T07:04:24Z` — couverture `partial`
   - Requête : GitLab Duo Agent Platform governance Oct 8 2026 launch
   - Résultat : Recherche effectuée pendant ce passage; horodatage agrégé de clôture du rapport (heure précise individuelle non enregistrée), non une preuve d’exhaustivité.
   - Preuves : `E-20261008-GL-001`
11. **web search and GitHub code/repository discovery** — `2026-10-08T07:04:24Z` — couverture `partial`
   - Requête : site:docs.gitlab.com governance for agents approval agent actions policy audit 2026
   - Résultat : Recherche effectuée pendant ce passage; horodatage agrégé de clôture du rapport (heure précise individuelle non enregistrée), non une preuve d’exhaustivité.
   - Preuves : aucun
12. **web search and GitHub code/repository discovery** — `2026-10-08T07:04:24Z` — couverture `partial`
   - Requête : Open source AgentOps subject verdict NOT_PROVEN intent independent coding agent
   - Résultat : Recherche effectuée pendant ce passage; horodatage agrégé de clôture du rapport (heure précise individuelle non enregistrée), non une preuve d’exhaustivité.
   - Preuves : aucun

### Candidats en attente

- useblocks / Pharaoh — intent layer for agentic engineering
- Atellagent Agent Authority
- Axiomorix
- GAAI governance framework
- fabriqa.ai specification-native agentic development
- Kandev
- SIDJUA
- ai-software-factory governance controller
- NexusClaw agent-governance
- Sovereign AgentOps
- lapop-agent-governance
- agentboard governance stack
- nono agent runtime security
- GitLab GitLab Agent Governance for Agents specific source implementation
- EngineeringSpec / agents-govern-framework (research lead)
- AgentOps additional feature surfaces beyond evidence core

### Doublons, forks, renommages et lignées

- Microsoft Agent Governance Toolkit policy-engine core is currently a compatibility shim over Agent Control Specification; both identities are retained but linked, not double-counted as independent core engines.
- GitLab is an existing established company, newly admitted to the watch; its October 6 announcement predates the previous October 7 report.

### Limites de découverte

- La découverte ne garantit pas le repérage de tout nouvel entrant.
- Les résultats secondaires servent de leads; les évaluations d’implémentation s’appuient sur source code ou primaire.
- Horodatage des recherches déclaré à la clôture faute de timestamp par requête.
- L’ancien rapport n’a pas été archivé dans le repository; un suivi de continuité complet n’est pas revendiqué.

## 6. Trajectoires

- Mneme: progression réelle D1 (implémentation canonique et release 0.10.0 le 7 octobre), niveau Ring L2 inchangé; DG1 reste déterminant.
- Chainloop: progression réelle R5/C1 par vérification keyless conditionnelle, réparation de requireTrace pre-push, meilleure gestion des états unverified/unknown, enrichissement skills; signal Cloud L2 inchangé.
- Chock: progression réelle sur drift tighten-only et multi-root coverage; Ring L2 inchangé.
- DynosAI, Vectimus, ACS: HEAD inchangé; les anciennes évaluations ne sont pas revalidées exhaustivement.
- AGT: changements deps/CI, pas de gain de garantie démontré; note core L1 reconduite.
- GitLab: annonce officielle datée 2026-10-06 mais découverte 2026-10-08 — new_evidence, pas un changement technique entre deux rapports.
- AgentOps: première évaluation à la révision 4e5be46c, aucune trajectoire antérieure disponible.

## 7. Implications pour le positionnement

- Ne jamais fonder le positionnement sur une prétendue absence de provenance/attestation chez les alternatives: Chainloop et AgentOps produisent déjà des preuves fortement liées à des digests.
- Ring doit continuer de se différencier par la continuité d’autorité et l’évolution gouvernée des obligations elles-mêmes. Mneme D1 et AgentOps se rapprochent sur des sous-ensembles, sans équivalence complète démontrée.
- La réparation Chainloop requireTrace démontre qu’une option “fail closed” peut être contournée par un simple script de hook erroné: les comparaisons doivent examiner le dernier point qui bloque réellement la transition.
- GitLab montre que le langage “governed software factory” est déjà public chez des acteurs majeurs; le message de Ring doit rester spécifique et testable, et ne pas prétendre exclusivité.

## 8. Couverture, retards et investigations ouvertes

### Couverture

- **fanilosendrison/ring authority and archive — `complete` :** curseur `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` → `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c`. Spec, discipline, rationale, vision, positioning, methodology, execution, watchlist et schéma relus sur main; aucun rapport RCW archivé présent.
- **baseline RCW-20261007T065552Z — `partial` :** curseur `null` → `null`. Fichiers JSON/Markdown du rapport précédent récupérés depuis les pièces de conversation, mais absents du dépôt canonique; aucune archive GitHub n’a été revendiquée.
- **MnemeHQ/mneme — `partial` :** curseur `b4035655c5ada6cfcaa0ea153ea22caedd672e61` → `3580fa57e36283f836df0af7b199f87dc8762975`. Commits depuis 7 octobre et PR #458/#460/#461, release v0.10.0, architecture/roadmap inspectés; tests lus, non exécutés.
- **chainloop-dev/chainloop — `partial` :** curseur `10df49bc7b7e16772a96a03096765da5bc67699c` → `925c921cf79f2749675e5dc189922f22b120537e`. Commits et PR #3529/#3550/#3551/#3555, code hooks/action/controlplane et release v1.118.1 inspectés; tests lus, non exécutés.
- **open-coder-ai/chock — `partial` :** curseur `da248c38f0d3f3e82e00e8b0342e919879819f73` → `ab90feb4755d9c2168c2f3014cb66cbb18a699f8`. PR #245, code toggle et stop_roots et tests inspectés. PR #247 vérifiée comme mise à jour de warning d’installation; aucune note globale reclassée.
- **microsoft/agent-governance-toolkit — `partial` :** curseur `c4d7e3375c985098e54e802eb32c965ddbc955c7` → `84ae67348705996a3d65e31936afb7d02853f2a0`. Liste des commits récents consultée: dépendances/CI/supply-chain, aucune clôture sémantique AGT établie; code du core non ré-audité.
- **pablo-cano/dynosai — `partial` :** curseur `019f46579e081cb9154fa63b49177e2654020203` → `019f46579e081cb9154fa63b49177e2654020203`. HEAD main inchangé depuis baseline; aucune revalidation du chemin de décision, note précédente reconduite.
- **vectimus/vectimus — `partial` :** curseur `99ee6c7ad28e9a83306d3e17f0ce973a47e4d6b4` → `99ee6c7ad28e9a83306d3e17f0ce973a47e4d6b4`. HEAD main inchangé; pas de nouvelle inspection de garanties, note précédente reconduite.
- **responsibleai/agent-control-spec — `partial` :** curseur `f2334533651d726b4e9daac170e5116ac3135794` → `f2334533651d726b4e9daac170e5116ac3135794`. HEAD main inchangé; aucune composition hôte ACS inspectée ce passage.
- **boshu2/agentops — `partial` :** curseur `null` → `4e5be46c0295ff9b93c2c798497f062f6be04f6c`. Première inspection du contrat, code evidence/store/verdictcheck et descriptions; tests non exécutés.
- **GitLab Governed Software Factory — `partial` :** curseur `null` → `2026-10-06`. Communiqués officiels du 6 octobre et 10 juin inspectés; code de produit non inspecté; nouvelles preuves, pas changement observé depuis baseline.
- **open discovery search — `partial` :** curseur `null` → `2026-10-08T07:04:24Z`. Recherches sémantiques et surveillance des sources GitHub/communiqués; couverture non exhaustive.
- **remaining permanent radar and discovery seeds — `not_checked` :** curseur `null` → `null`. Acteurs historiques conservés, mais aucune inspection individuelle complète; pas d’avancement de leurs cursors.

- **acteurs en retard :** aucun
- **continuité du radar :** `history_incomplete`
- **notes de réconciliation :** Les 42 acteurs du report précédent RCW-20261007T065552Z sont conservés à partir de sa copie JSON locale récupérée de cette conversation (fichier réel); pourtant aucun ancien rapport n’existe dans origin/main. La continuité dans le chat est reconstituée, mais l’historique GitHub canonique est incomplet: ROSTER_HISTORY_INCOMPLETE. Les nouveaux acteurs AgentOps et GitLab sont conservés sans reclassement rétrospectif.

### Questions ouvertes

- DG1 Mneme: quelle sémantique publique de décision effective, precedence, waiver et scope arrive après D1 publié ?
- Chainloop: combien de modes installés appliquent réellement requireTrace et que se passe-t-il si le binaire disparaît ?
- Chainloop: l’exception TSA TrustConfigFault permet-elle un usage downstream qui confond timestamp invérifiable et timestamp prouvé ?
- Chock: les changements de policy hors guardrail toggle suivent-ils une autorité acceptée ?
- AgentOps: qui protège l’acceptance contre la révision unilatérale et comment les evidence_refs sont-elles sémantiquement validées ?
- GitLab: peut-on inspecter une chaîne source/runtime Governed Software Factory ou Governance for Agents disponible ?
- Le précédent RCW est-il enfin archivé sous son ID immuable dans GitHub ?

## 9. Sources et éléments de preuve

### E-MN-001 — `source_inspection`

- **acteur :** `mneme`
- **URL :** <https://github.com/MnemeHQ/mneme/blob/b4035655c5ada6cfcaa0ea153ea22caedd672e61/docs/roadmap/README.md>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `b4035655c5ada6cfcaa0ea153ea22caedd672e61`
- **chemin ou localisateur :** `docs/roadmap/README.md`
- **proposition étayée :** D1 n'est pas encore entièrement clos et DG1, prévu après D1, doit formaliser autorité, applicabilité, précédence, waivers et résolution effective des décisions.
- **limites :**
- Lecture statique du dépôt; aucun test Mneme exécuté pendant ce passage.
- **exécution :** `null`

### E-MN-002 — `source_inspection`

- **acteur :** `mneme`
- **URL :** <https://github.com/MnemeHQ/mneme/blob/b4035655c5ada6cfcaa0ea153ea22caedd672e61/mneme/decision_add.py>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `b4035655c5ada6cfcaa0ea153ea22caedd672e61`
- **chemin ou localisateur :** `mneme/decision_add.py`
- **proposition étayée :** Le chemin canonical add_decision est explicitement présenté comme une opération d'autorité humaine, idempotente à contenu identique et fail-closed en cas de collision ou d'autorité différente.
- **limites :**
- Le chemin d'ajout n'établit pas à lui seul les sémantiques globales d'applicabilité et de précédence.
- **exécution :** `null`

### E-MN-003 — `tests_inspected`

- **acteur :** `mneme`
- **URL :** <https://github.com/MnemeHQ/mneme/blob/b4035655c5ada6cfcaa0ea153ea22caedd672e61/tests/test_d1e3_canonical_add_decision.py>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `b4035655c5ada6cfcaa0ea153ea22caedd672e61`
- **chemin ou localisateur :** `tests/test_d1e3_canonical_add_decision.py`
- **proposition étayée :** Les tests présents couvrent identité d'occurrence, no-op byte-identical sur retry et échec fermé pour contenu différent.
- **limites :**
- Tests inspectés seulement; ils n'ont pas été exécutés pendant ce passage.
- **exécution :** `null`

### E-DY-001 — `documentation`

- **acteur :** `dynosai`
- **URL :** <https://github.com/pablo-cano/dynosai/blob/019f46579e081cb9154fa63b49177e2654020203/docs/ARCHITECTURE.md>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `019f46579e081cb9154fa63b49177e2654020203`
- **chemin ou localisateur :** `docs/ARCHITECTURE.md`
- **proposition étayée :** DynosAI documente SQLite comme autorité de workflow, Git comme vérité de code, des gates humains persistants et un workflow déterministe.
- **limites :**
- Documentation corroborée par des chemins de code ciblés, mais pas par exécution end-to-end.
- **exécution :** `null`

### E-DY-002 — `source_inspection`

- **acteur :** `dynosai`
- **URL :** <https://github.com/pablo-cano/dynosai/blob/019f46579e081cb9154fa63b49177e2654020203/src/dynosai_flow/validation_integrity.py>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `019f46579e081cb9154fa63b49177e2654020203`
- **chemin ou localisateur :** `src/dynosai_flow/validation_integrity.py`
- **proposition étayée :** Le moteur construit une chaîne requirement→acceptance→task→evidence et signale notamment l'absence de preuves et les tests auto-écrits comme preuve unique.
- **limites :**
- Cette intégrité ne prouve pas à elle seule l'autorité de chaque exigence.
- **exécution :** `null`

### E-DY-003 — `source_inspection`

- **acteur :** `dynosai`
- **URL :** <https://github.com/pablo-cano/dynosai/blob/019f46579e081cb9154fa63b49177e2654020203/src/dynosai_flow/engine.py>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `019f46579e081cb9154fa63b49177e2654020203`
- **chemin ou localisateur :** `src/dynosai_flow/engine.py`
- **proposition étayée :** Le moteur impose revue de spec et plan, refuse les plans obsolètes, vérifie le résultat agent avant code review et exige un résultat independently verified avant approbation du code.
- **limites :**
- Inspection statique; aucune campagne de tests DynosAI exécutée.
- **exécution :** `null`

### E-DY-004 — `source_inspection`

- **acteur :** `dynosai`
- **URL :** <https://github.com/pablo-cano/dynosai/blob/019f46579e081cb9154fa63b49177e2654020203/src/dynosai_flow/mcp.py>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `019f46579e081cb9154fa63b49177e2654020203`
- **chemin ou localisateur :** `src/dynosai_flow/mcp.py`
- **proposition étayée :** dynosai_register_decision est exposé aux profils agent de design/acceptance et délègue directement à register_decision sans gate humain dans ce chemin.
- **limites :**
- Une intégration externe pourrait ajouter une contrainte supplémentaire; aucun mécanisme de ce type n'a été établi dans le chemin inspecté.
- **exécution :** `null`

### E-DY-005 — `source_inspection`

- **acteur :** `dynosai`
- **URL :** <https://github.com/pablo-cano/dynosai/blob/019f46579e081cb9154fa63b49177e2654020203/src/dynosai_flow/agents.py>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `019f46579e081cb9154fa63b49177e2654020203`
- **chemin ou localisateur :** `src/dynosai_flow/agents.py`
- **proposition étayée :** Les instructions agent disent que les décisions humaines passent par MCP Elicitation et qu'il ne faut jamais auto-approuver.
- **limites :**
- Une instruction de prompt n'est pas une frontière d'autorité équivalente à une interdiction structurelle.
- **exécution :** `null`

### E-CH-001 — `documentation`

- **acteur :** `chock`
- **URL :** <https://github.com/open-coder-ai/chock/blob/da248c38f0d3f3e82e00e8b0342e919879819f73/docs/coverage-levels.md>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `da248c38f0d3f3e82e00e8b0342e919879819f73`
- **chemin ou localisateur :** `docs/coverage-levels.md`
- **proposition étayée :** Chock distingue explicitement plusieurs niveaux de couverture et refuse de confondre détection, best-effort et enforcement démontré.
- **limites :**
- La taxonomie de couverture ne prouve pas l'autorité produit ou la légitimité de l'évolution des politiques.
- **exécution :** `null`

### E-CH-002 — `source_inspection`

- **acteur :** `chock`
- **URL :** <https://github.com/open-coder-ai/chock/blob/da248c38f0d3f3e82e00e8b0342e919879819f73/src/chock/guardrails/toggle.py>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `da248c38f0d3f3e82e00e8b0342e919879819f73`
- **chemin ou localisateur :** `src/chock/guardrails/toggle.py`
- **proposition étayée :** Le mécanisme de toggle de guardrails détecte le drift et ignore un état modifié hors du chemin attendu, conservant les guardrails activés; la surface est explicitement décrite comme human-controlled.
- **limites :**
- Cette autorité est spécifique aux guardrails inspectés, pas à toute gouvernance du sens produit.
- **exécution :** `null`

### E-CH-003 — `source_inspection`

- **acteur :** `chock`
- **URL :** <https://github.com/open-coder-ai/chock/blob/da248c38f0d3f3e82e00e8b0342e919879819f73/src/chock/lock.py>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `da248c38f0d3f3e82e00e8b0342e919879819f73`
- **chemin ou localisateur :** `src/chock/lock.py`
- **proposition étayée :** Le lockfile et les digests permettent de détecter le drift de sources/politiques compilées.
- **limites :**
- Drift détecté n'implique pas, à lui seul, qu'une modification est autorisée ou non par le Product Intent.
- **exécution :** `null`

### E-VE-001 — `source_inspection`

- **acteur :** `vectimus`
- **URL :** <https://github.com/vectimus/vectimus/blob/99ee6c7ad28e9a83306d3e17f0ce973a47e4d6b4/src/vectimus/cli/hook_cmd.py>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `99ee6c7ad28e9a83306d3e17f0ce973a47e4d6b4`
- **chemin ou localisateur :** `src/vectimus/cli/hook_cmd.py`
- **proposition étayée :** Vectimus normalise les actions, échoue fermé sur erreur de normalisation, évalue avant l'action, traite escalate comme deny local et écrit audit/receipt lorsque configuré.
- **limites :**
- Le mode serveur peut ajouter d'autres responsabilités; elles ne sont pas établies ici.
- **exécution :** `null`

### E-VE-002 — `source_inspection`

- **acteur :** `vectimus`
- **URL :** <https://github.com/vectimus/vectimus/blob/99ee6c7ad28e9a83306d3e17f0ce973a47e4d6b4/src/vectimus/engine/receipts.py>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `99ee6c7ad28e9a83306d3e17f0ce973a47e4d6b4`
- **chemin ou localisateur :** `src/vectimus/engine/receipts.py`
- **proposition étayée :** Les receipts lient hash du contexte et du policy set, peuvent être signés Ed25519, mais sont écrits de façon asynchrone et la rétention locale par défaut est de sept jours.
- **limites :**
- L'écriture asynchrone peut échouer après le verdict; la présence d'une signature dépend d'une clé disponible.
- **exécution :** `null`

### E-VE-003 — `source_inspection`

- **acteur :** `vectimus`
- **URL :** <https://github.com/vectimus/vectimus/blob/99ee6c7ad28e9a83306d3e17f0ce973a47e4d6b4/src/vectimus/engine/loader.py>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `99ee6c7ad28e9a83306d3e17f0ce973a47e4d6b4`
- **chemin ou localisateur :** `src/vectimus/engine/loader.py`
- **proposition étayée :** Des packs projet peuvent remplacer cache/global/bundled et des règles peuvent être désactivées par configuration ou désactivation temporaire.
- **limites :**
- Aucune chaîne générale d'autorité gouvernant ces changements de politique n'a été établie dans les chemins inspectés.
- **exécution :** `null`

### E-VE-004 — `tests_inspected`

- **acteur :** `vectimus`
- **URL :** <https://github.com/vectimus/vectimus/blob/99ee6c7ad28e9a83306d3e17f0ce973a47e4d6b4/tests/test_temp_disable.py>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `99ee6c7ad28e9a83306d3e17f0ce973a47e4d6b4`
- **chemin ou localisateur :** `tests/test_temp_disable.py`
- **proposition étayée :** La suite présente des tests de désactivation temporaire de règles par projet et de leur impact sur le cache moteur.
- **limites :**
- Tests inspectés seulement; non exécutés pendant ce passage.
- **exécution :** `null`

### E-AC-001 — `documentation`

- **acteur :** `acs`
- **URL :** <https://github.com/responsibleai/agent-control-spec/blob/f2334533651d726b4e9daac170e5116ac3135794/README.md>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `f2334533651d726b4e9daac170e5116ac3135794`
- **chemin ou localisateur :** `README.md`
- **proposition étayée :** ACS se définit comme runtime de décision déterministe et stateless; application des transformations, approbations et record keeping sont des obligations de l'hôte.
- **limites :**
- Évaluation limitée au runtime ACS, pas à une intégration hôte complète particulière.
- **exécution :** `null`

### E-AC-002 — `source_inspection`

- **acteur :** `acs`
- **URL :** <https://github.com/responsibleai/agent-control-spec/blob/f2334533651d726b4e9daac170e5116ac3135794/engine/src/runtime.rs>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `f2334533651d726b4e9daac170e5116ac3135794`
- **chemin ou localisateur :** `engine/src/runtime.rs`
- **proposition étayée :** Le code renvoie verdict et policy_input mais laisse explicitement à l'hôte transform application, enforcement mode, approval resolution et identity computation.
- **limites :**
- Les garanties d'une composition hôte+ACS doivent être évaluées séparément.
- **exécution :** `null`

### E-MS-001 — `source_inspection`

- **acteur :** `microsoft-agt`
- **URL :** <https://github.com/microsoft/agent-governance-toolkit/blob/c4d7e3375c985098e54e802eb32c965ddbc955c7/policy-engine/core/src/lib.rs>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `c4d7e3375c985098e54e802eb32c965ddbc955c7`
- **chemin ou localisateur :** `policy-engine/core/src/lib.rs`
- **proposition étayée :** Le core AGT est désormais un shim de compatibilité vers ACS; il documente aussi une régression de provenance des manifests URL dans la version ACS alors ciblée et recommande de ne pas activer certains dispatchers tant que le gate n'est pas restauré.
- **limites :**
- Le reste du toolkit n'a pas été entièrement inspecté pendant ce passage.
- **exécution :** `null`

### E-CL-001 — `source_inspection`

- **acteur :** `chainloop`
- **URL :** <https://github.com/chainloop-dev/chainloop/blob/10df49bc7b7e16772a96a03096765da5bc67699c/pkg/policies/policies.go>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `10df49bc7b7e16772a96a03096765da5bc67699c`
- **chemin ou localisateur :** `pkg/policies/policies.go`
- **proposition étayée :** Chainloop sélectionne les politiques requises pour un matériau, exécute les scripts, conserve référence/digest, exigences, violations, skip reasons, inputs effectifs, overrides runtime, résultats bruts et caractère bloquant.
- **limites :**
- Les politiques requises proviennent du contrat/attachement; le moteur n'établit pas à lui seul que ce contrat représente tout le sens gouverné.
- **exécution :** `null`

### E-CL-002 — `source_inspection`

- **acteur :** `chainloop`
- **URL :** <https://github.com/chainloop-dev/chainloop/blob/10df49bc7b7e16772a96a03096765da5bc67699c/pkg/attestation/crafter/api/attestation/v1/crafting_state.proto>
- **observé à :** `2026-10-07T06:55:52Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `10df49bc7b7e16772a96a03096765da5bc67699c`
- **chemin ou localisateur :** `pkg/attestation/crafter/api/attestation/v1/crafting_state.proto`
- **proposition étayée :** Le modèle d'attestation porte matériaux/digests, commit de tête optionnel, authentification, environnement runner, résultats de politiques, références/digests, exigences, données brutes, gating et statut skipped.
- **limites :**
- La présence d'un champ commit ou d'un digest ne prouve pas que toute gouvernance pertinente est liée à cet état.
- **exécution :** `null`

### E-20261008-MN-001 — `source_inspection`

- **acteur :** `mneme`
- **URL :** <https://github.com/MnemeHQ/mneme/blob/3580fa57e36283f836df0af7b199f87dc8762975/docs/architecture/d1-closeout.md>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `2026-10-07T16:01:38Z`
- **source publiée à :** `null`
- **révision :** `3580fa57e36283f836df0af7b199f87dc8762975`
- **chemin ou localisateur :** `docs/architecture/d1-closeout.md`
- **proposition étayée :** La clôture D1E6 épingle des tests de parité des consumers, enforcement, audits et identité MCP sur des corpus historiques, avec procédure de release séparée.
- **limites :**
- Tests présents inspectés via PR; non exécutés.
- **exécution :** `null`

### E-20261008-MN-002 — `documentation`

- **acteur :** `mneme`
- **URL :** <https://github.com/MnemeHQ/mneme/releases/tag/v0.10.0>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `2026-10-07T17:28:40Z`
- **source publiée à :** `2026-10-07T17:28:40Z`
- **révision :** `3580fa57e36283f836df0af7b199f87dc8762975`
- **chemin ou localisateur :** `release v0.10.0`
- **proposition étayée :** Release v0.10.0 publiée 2026-10-07T17:28:40Z : Decision Index persisted canonique, versions immuables, rule identity dérivée du contenu, migration explicite avec refus des transformations avec perte.
- **limites :**
- La publication de la release ne démontre pas DG1 ou une suite de tests réexécutée ici.
- **exécution :** `null`

### E-20261008-MN-003 — `source_inspection`

- **acteur :** `mneme`
- **URL :** <https://github.com/MnemeHQ/mneme/blob/3580fa57e36283f836df0af7b199f87dc8762975/docs/roadmap/README.md>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `3580fa57e36283f836df0af7b199f87dc8762975`
- **chemin ou localisateur :** `docs/roadmap/README.md`
- **proposition étayée :** Le roadmap maintient DG1 post-D1 : gouvernance sémantique d’applicabilité, précédence, waivers et résolution de la décision effective.
- **limites :**
- Roadmap, non preuve d’une implémentation future.
- **exécution :** `null`

### E-20261008-CL-001 — `source_inspection`

- **acteur :** `chainloop`
- **URL :** <https://github.com/chainloop-dev/chainloop/blob/925c921cf79f2749675e5dc189922f22b120537e/app/cli/internal/trace/hooks/hooks.go>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `2026-10-07T22:54:38Z`
- **source publiée à :** `null`
- **révision :** `925c921cf79f2749675e5dc189922f22b120537e`
- **chemin ou localisateur :** `app/cli/internal/trace/hooks/hooks.go`
- **proposition étayée :** Le hook pre-push propage désormais le statut non nul de chainloop; les autres hooks ne bloquent pas; si le binaire chainloop est absent le script permet toujours le push.
- **limites :**
- Le comportement repose sur un hook Git installé et non contourné, et sur le binaire présent.
- **exécution :** `null`

### E-20261008-CL-002 — `source_inspection`

- **acteur :** `chainloop`
- **URL :** <https://github.com/chainloop-dev/chainloop/blob/925c921cf79f2749675e5dc189922f22b120537e/app/cli/pkg/action/trace_hook_handler.go>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `925c921cf79f2749675e5dc189922f22b120537e`
- **chemin ou localisateur :** `app/cli/pkg/action/trace_hook_handler.go`
- **proposition étayée :** PrePushFailure bloque le push en cas d’erreur de trace si requireTrace=true, et avertit sans bloquer si false.
- **limites :**
- La protection ne constitue pas une obligation de capturer toutes les sessions si requireTrace est désactivé.
- **exécution :** `null`

### E-20261008-CL-003 — `source_inspection`

- **acteur :** `chainloop`
- **URL :** <https://github.com/chainloop-dev/chainloop/blob/925c921cf79f2749675e5dc189922f22b120537e/app/controlplane/pkg/biz/workflowrun.go>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `2026-10-07T14:34:21Z`
- **source publiée à :** `null`
- **révision :** `925c921cf79f2749675e5dc189922f22b120537e`
- **chemin ou localisateur :** `app/controlplane/pkg/biz/workflowrun.go`
- **proposition étayée :** La réception de l’attestation vérifie signature et organisation en mode keyless configuré, forced par défaut; sans keyless, aucune vérification de ce type. Un TrustConfigFault TSA peut permettre la conservation d’une attestation au timestamp invérifiable après validation de signature.
- **limites :**
- forceVerification=false permet des méthodes de signature non vérifiables par cette voie; le timestamp reste un axe distinct.
- **exécution :** `null`

### E-20261008-CL-004 — `tests_inspected`

- **acteur :** `chainloop`
- **URL :** <https://github.com/chainloop-dev/chainloop/blob/925c921cf79f2749675e5dc189922f22b120537e/app/controlplane/pkg/biz/workflowrun_verification_test.go>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `925c921cf79f2749675e5dc189922f22b120537e`
- **chemin ou localisateur :** `app/controlplane/pkg/biz/workflowrun_verification_test.go`
- **proposition étayée :** Présence de tests ciblant la vérification des attestations dans le control plane.
- **limites :**
- Tests seulement inspectés; aucune exécution locale effectuée.
- **exécution :** `null`

### E-20261008-CL-005 — `documentation`

- **acteur :** `chainloop`
- **URL :** <https://github.com/chainloop-dev/chainloop/pull/3550>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `2026-10-07T21:27:52Z`
- **source publiée à :** `null`
- **révision :** `925c921cf79f2749675e5dc189922f22b120537e`
- **chemin ou localisateur :** `PR #3550 et code de commit verification GitLab`
- **proposition étayée :** La PR fusionnée sépare commit non signé de verification indisponible pour 404 GitLab; elle explicite token read_api nécessaire en projet privé et stable runner detection.
- **limites :**
- Description PR et diff consultés; suite non exécutée.
- **exécution :** `null`

### E-20261008-CL-006 — `source_inspection`

- **acteur :** `chainloop`
- **URL :** <https://github.com/chainloop-dev/chainloop/blob/925c921cf79f2749675e5dc189922f22b120537e/app/cli/internal/trace/claude/skills.go>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `2026-10-07T18:33:33Z`
- **source publiée à :** `null`
- **révision :** `925c921cf79f2749675e5dc189922f22b120537e`
- **chemin ou localisateur :** `app/cli/internal/trace/claude/skills.go`
- **proposition étayée :** La capture des skills de session est ajoutée au parseur de traces Claude et peut inclure des sous-agents.
- **limites :**
- Périmètre signal technique; non une preuve d’autorité sur les exigences.
- **exécution :** `null`

### E-20261008-CL-007 — `documentation`

- **acteur :** `chainloop`
- **URL :** <https://github.com/chainloop-dev/chainloop/releases/tag/v1.118.1>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `2026-10-08T03:32:26Z`
- **source publiée à :** `2026-10-08T03:32:26Z`
- **révision :** `925c921cf79f2749675e5dc189922f22b120537e`
- **chemin ou localisateur :** `release v1.118.1`
- **proposition étayée :** La release v1.118.1 du 8 octobre incorpore la correction requireTrace.
- **limites :**
- La publication ne prouve pas la capture obligatoire quand le binaire/hook est absent.
- **exécution :** `null`

### E-20261008-CH-001 — `source_inspection`

- **acteur :** `chock`
- **URL :** <https://github.com/open-coder-ai/chock/blob/ab90feb4755d9c2168c2f3014cb66cbb18a699f8/src/chock/guardrails/toggle.py>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `2026-10-07T10:15:29Z`
- **source publiée à :** `null`
- **révision :** `ab90feb4755d9c2168c2f3014cb66cbb18a699f8`
- **chemin ou localisateur :** `src/chock/guardrails/toggle.py`
- **proposition étayée :** Une suppression de toggle qui ne fait que resserrer les règles ne bloque plus la fin de tour; elle reste refusée si elle délègue à une politique user moins stricte ou non vérifiée.
- **limites :**
- La vérification globale de l’autorité des politiques n’est pas démontrée.
- **exécution :** `null`

### E-20261008-CH-002 — `source_inspection`

- **acteur :** `chock`
- **URL :** <https://github.com/open-coder-ai/chock/blob/ab90feb4755d9c2168c2f3014cb66cbb18a699f8/src/chock/gate/stop_roots.py>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `2026-10-07T10:15:29Z`
- **source publiée à :** `null`
- **révision :** `ab90feb4755d9c2168c2f3014cb66cbb18a699f8`
- **chemin ou localisateur :** `src/chock/gate/stop_roots.py`
- **proposition étayée :** Le contrôle Stop examine cwd et les workspace roots représentés par repository, agrège les verdicts et retient la sévérité maximale.
- **limites :**
- Portée limitée aux roots observables par le hook et au périmètre compilé.
- **exécution :** `null`

### E-20261008-CH-003 — `tests_inspected`

- **acteur :** `chock`
- **URL :** <https://github.com/open-coder-ai/chock/blob/ab90feb4755d9c2168c2f3014cb66cbb18a699f8/tests/test_guardrails_turn_end.py>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `ab90feb4755d9c2168c2f3014cb66cbb18a699f8`
- **chemin ou localisateur :** `tests/test_guardrails_turn_end.py`
- **proposition étayée :** Tests présents pour refus de drift, suppression de toggle et cas de fallback qui serait moins strict.
- **limites :**
- Non exécutés dans cet environnement.
- **exécution :** `null`

### E-20261008-AG-001 — `documentation`

- **acteur :** `agentops`
- **URL :** <https://github.com/boshu2/agentops/blob/4e5be46c0295ff9b93c2c798497f062f6be04f6c/docs/trust-factory.md>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `4e5be46c0295ff9b93c2c798497f062f6be04f6c`
- **chemin ou localisateur :** `docs/trust-factory.md`
- **proposition étayée :** AgentOps explicite acceptance immuable, exact subject digest, fresh independent review et verdict PASS/FAIL/NOT_PROVEN; le caller reste responsable de Git/CI/merge/release.
- **limites :**
- Déclaration architecture; les opérations de preuve ont été inspectées séparément.
- **exécution :** `null`

### E-20261008-AG-002 — `source_inspection`

- **acteur :** `agentops`
- **URL :** <https://github.com/boshu2/agentops/blob/4e5be46c0295ff9b93c2c798497f062f6be04f6c/cli/internal/evidence/store.go>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `4e5be46c0295ff9b93c2c798497f062f6be04f6c`
- **chemin ou localisateur :** `cli/internal/evidence/store.go`
- **proposition étayée :** StoreVerdict vérifie le manifest du sujet réel et lie intent digest, subject digest, contexte et verdict dans un artifact content-addressed; VerifySubject vérifie le sujet courant, intent digest et un verdict PASS.
- **limites :**
- VerifySubject précise ne pas juger sémantiquement les evidence references; provenance/fraîcheur peut venir d’une attestation du runtime/caller.
- **exécution :** `null`

### E-20261008-AG-003 — `source_inspection`

- **acteur :** `agentops`
- **URL :** <https://github.com/boshu2/agentops/blob/4e5be46c0295ff9b93c2c798497f062f6be04f6c/cli/internal/verdictcheck/verdictcheck.go>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `4e5be46c0295ff9b93c2c798497f062f6be04f6c`
- **chemin ou localisateur :** `cli/internal/verdictcheck/verdictcheck.go`
- **proposition étayée :** ValidateShape impose pour PASS des identités author/validator distinctes, freshness attestation, checked non vide, not_checked vide et preuves pour tous critères.
- **limites :**
- Le contrôle structurel ne démontre pas l’indépendance effective du reviewer ni la correction de son jugement.
- **exécution :** `null`

### E-20261008-AG-004 — `documentation`

- **acteur :** `agentops`
- **URL :** <https://github.com/boshu2/agentops/blob/4e5be46c0295ff9b93c2c798497f062f6be04f6c/docs/architecture/rpi-traversal.md>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `null`
- **source publiée à :** `null`
- **révision :** `4e5be46c0295ff9b93c2c798497f062f6be04f6c`
- **chemin ou localisateur :** `docs/architecture/rpi-traversal.md`
- **proposition étayée :** Le contrat de traversal distingue accepted intent, checks, final fresh review, NOT_PROVEN et autorité du caller pour changer acceptance.
- **limites :**
- Document autorisé comme conception, pas preuve que chaque intégration suit le workflow.
- **exécution :** `null`

### E-20261008-GL-001 — `documentation`

- **acteur :** `gitlab-governed-factory`
- **URL :** <https://about.gitlab.com/press/releases/2026-10-06-gitlab-announces-the-foundation-for-the-governed-software-factory/>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `2026-10-06`
- **source publiée à :** `2026-10-06`
- **révision :** `null`
- **chemin ou localisateur :** `Communiqué officiel GitLab du 2026-10-06`
- **proposition étayée :** GitLab présente Governed Software Factory avec /goal, Custom Flows, Artifact Central, Dependency Firewall, Orbit et Impact Analytics; statuts de disponibilité hétérogènes, plusieurs beta/early access.
- **limites :**
- Annonce publiée avant la baseline précédente mais découverte aujourd’hui; aucune chaîne d’autorité Ring end-to-end inspectée.
- **exécution :** `null`

### E-20261008-GL-002 — `documentation`

- **acteur :** `gitlab-governed-factory`
- **URL :** <https://about.gitlab.com/press/releases/2026-06-10-gitlab-announces-new-capabilities-to-give-enterprises-speed-control-at-agentic-scale/>
- **observé à :** `2026-10-08T07:04:24Z`
- **événement à :** `2026-06-10`
- **source publiée à :** `2026-06-10`
- **révision :** `null`
- **chemin ou localisateur :** `Communiqué officiel GitLab du 2026-06-10`
- **proposition étayée :** GitLab Governance for Agents est annoncé en private beta et vise identity, policy, audit, approval sur des actions agents.
- **limites :**
- Composant fermé ou non inspecté techniquement; annonce seule insuffisante pour un rating garanti.
- **exécution :** `null`

## 10. Références historiques et corrections

- **rapports précédents :** `RCW-20261007T065552Z`
- **rapports corrigés :** aucun
- **acteurs précédents :** `nool`, `mneme`, `codespeak`, `qodo`, `packmind`, `tessl`, `microsoft-agt`, `acs`, `chainloop`, `entire`, `langsmith`, `braintrust`, `langfuse`, `phoenix`, `weave`, `kiro`, `augment-intent`, `8090`, `coderabbit`, `greptile`, `endor-labs`, `rippletide`, `google-agent-governance`, `github-agent-platform`, `openai-codex`, `anthropic-claude-code`, `imandra`, `antithesis`, `opa`, `in-toto`, `spec-kit`, `openspec`, `jama`, `strongdm-factory`, `prime-intellect`, `swe-gym`, `swe-smith`, `r2e-gym`, `poolside`, `chock`, `dynosai`, `vectimus`
- **nouvelles admissions :** `agentops`, `gitlab-governed-factory`
- **radar courant :** `nool`, `mneme`, `codespeak`, `qodo`, `packmind`, `tessl`, `microsoft-agt`, `acs`, `chainloop`, `entire`, `langsmith`, `braintrust`, `langfuse`, `phoenix`, `weave`, `kiro`, `augment-intent`, `8090`, `coderabbit`, `greptile`, `endor-labs`, `rippletide`, `google-agent-governance`, `github-agent-platform`, `openai-codex`, `anthropic-claude-code`, `imandra`, `antithesis`, `opa`, `in-toto`, `spec-kit`, `openspec`, `jama`, `strongdm-factory`, `prime-intellect`, `swe-gym`, `swe-smith`, `r2e-gym`, `poolside`, `chock`, `dynosai`, `vectimus`, `agentops`, `gitlab-governed-factory`
- **arrêts demandés par l’utilisateur :** aucun
- **références des instructions utilisateur :** aucun

Les informations de continuité ci-dessus sont celles du passage historique. Elles ne sont pas réécrites en fonction de l’état actuel de l’archive.
