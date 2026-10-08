# Veille Ring / Ring Cloud — Rapport du 07/10/2026 08:55:52 CEST

<!-- markdownlint-disable MD007 MD013 MD024 MD029 MD032 -->

- **report_id :** `RCW-20261007T065552Z`
- **type :** `baseline`
- **fenêtre observée :** `null` → `2026-10-07T06:55:52Z`
- **généré à :** `2026-10-07T06:55:52Z`
- **référence Ring :** `fanilosendrison/ring@2dba6f54e9eac14b9e304d54a0f2e564dcc9111c`
- **version du schéma :** `2`
- **version de la méthode :** `1.2.0`
- **statut de Ring Cloud :** Ring Cloud remains a non-authoritative candidate/future consideration; this report does not promote it.
- **historique disponible lors du passage :** `true`

Ce document est une projection mécanique de `report.json`.

## 1. Fenêtre d’observation et base de comparaison

La fenêtre s’étend de `null` à `2026-10-07T06:55:52Z`. Le rapport a été généré à `2026-10-07T06:55:52Z` avec Ring à la révision `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c`.

### Sources de base

- `docs/specification/ring-spec.md` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Ring Product Intent and normative meaning
- `docs/product/ring-product-rationale.md` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Non-normative Ring product rationale
- `docs/product/ring-cloud-product-rationale.md` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Non-normative Ring Cloud candidate rationale
- `docs/vision/ring-cloud.md` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Non-authoritative Ring Cloud future consideration
- `docs/product/positioning.md` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Non-normative positioning
- `docs/research/competitive-watch/methodology.md` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Competitive watch methodology 1.2.0
- `docs/research/competitive-watch/report.schema.json` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Report schema v2
- `docs/research/competitive-watch/watchlist.json` @ `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c` — Discovery seed roster

## 2. Synthèse

Première baseline formelle. Sept acteurs/composants ont été évalués techniquement: DynosAI, Mneme, Chock, Vectimus, ACS, Microsoft AGT core et Chainloop. Aucun L3/L4 n'est établi. DynosAI, Mneme, Chock, Vectimus et Chainloop atteignent L2 sur au moins une dimension; trois nouveaux entrants (DynosAI, Chock, Vectimus) sont admis au radar permanent. La découverte ouverte a aussi produit plusieurs candidats à approfondir. Aucun test tiers n'a été exécuté: code et tests ont été inspectés statiquement.

⚪ U signifie indéterminé, pas faible menace.

Aucun test tiers n'a été exécuté pendant ce passage; les tests cités ont été inspectés, pas reproduits.

## 3. Tableau des niveaux de menace

| Acteur / composant | Garanties Ring | Signal Cloud | Usages downstream | Confiance | Disponibilité | Dernière observation | Réévalué pendant ce passage ? |
| ------------------ | -------------- | ------------ | ----------------- | --------- | ------------- | -------------------- | ------------------------------ |
| Nool / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Mneme / `mneme-core` | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟡 ISOLATED_PRIMITIVE | high/medium/medium | released | 2026-10-07T06:55:52Z | true |
| CodeSpeak / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Qodo / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Packmind / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Tessl / `unverified-seed` | ⚪ INDETERMINATE | ⚪ INDETERMINATE | ⚪ INDETERMINATE | low/low/low | unknown | null | false |
| Microsoft Agent Governance Toolkit / `policy-engine-core` | 🟡 ISOLATED_PRIMITIVE | 🟡 ISOLATED_PRIMITIVE | 🟢 ADJACENT_OR_COMPLEMENTARY | high/medium/medium | released | 2026-10-07T06:55:52Z | true |
| Agent Control Specification / `acs-runtime` | 🟡 ISOLATED_PRIMITIVE | 🟡 ISOLATED_PRIMITIVE | 🟢 ADJACENT_OR_COMPLEMENTARY | high/high/high | prerelease | 2026-10-07T06:55:52Z | true |
| Chainloop / `policies-attestation` | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟡 ISOLATED_PRIMITIVE | high/high/medium | released | 2026-10-07T06:55:52Z | true |
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
| Chock / `chock-core` | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟡 ISOLATED_PRIMITIVE | 🟢 ADJACENT_OR_COMPLEMENTARY | medium/medium/medium | released | 2026-10-07T06:55:52Z | true |
| DynosAI / `dynosai-core` | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | medium/medium/medium | released | 2026-10-07T06:55:52Z | true |
| Vectimus / `vectimus-core` | 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE | 🟡 ISOLATED_PRIMITIVE | 🟢 ADJACENT_OR_COMPLEMENTARY | medium/medium/medium | released | 2026-10-07T06:55:52Z | true |

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
- **résumé :** Concurrent partiel sérieux; D1 renforce fortement l'autorité canonique, mais le roadmap confirme que des sémantiques centrales d'applicabilité/précédence restent à construire.
- **dernière observation :** `2026-10-07T06:55:52Z`
- **réévalué pendant ce passage :** `true`
- **disponibilité :** `released`

##### Garanties Ring — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** Décisions architecturales canoniques, autorité d'écriture, enforcement et lineage.
- **justification :** Mneme possède une autorité canonique et des chemins fail-closed significatifs, mais son propre roadmap place encore après D1 les sémantiques DG1 d'autorité/applicabilité/précédence/waiver et la résolution de la décision effective.
- **preuves :** `E-MN-001`, `E-MN-002`, `E-MN-003`
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
- **R2 — `partial` :** Enforcement/applicability existe pour des règles typées. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `DG1 scope/applicability des décisions est explicitement futur.`.
- **R3 — `partial` :** Versioning, supersession et collisions fail-closed. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Cycle complet de gouvernance des changements reste en fermeture D1/DG1.`.
- **R4 — `partial` :** Persistance canonique et vérification de snapshot. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Trusted execution attestation reste différé.`.
- **R5 — `supported` :** Plusieurs chemins refusent migration/collision plutôt que réparer implicitement. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Étendre à toutes les frontières de gouvernance.`.
- **R6 — `partial` :** CLI/API administrent plusieurs opérations gouvernées. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `D1 pas clos; DG1 à venir.`.
- **R7 — `supported` :** Decision Index canonique, version identity et lineage. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `D1E-D1F à clôturer.`.
- **R8 — `partial` :** Séparation authority/proposals/enforcement documentée. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Résolution effective cross-decision et fédération restent futures.`.
- **C1 — `partial` :** Enforcement/evidence et décisions canoniques produisent un signal structuré. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Attestation d'exécution de tests et couverture complète non établies.`.
- **C2 — `partial` :** Version lineage et supersession aident la validité longitudinale. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Repair versus requirement revision n'est pas encore un contrat complet.`.
- **C3 — `limited` :** Signal de conformité architecturale exploitable. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Labels de réparation/escalade Ring Cloud non établis.`.
- **C4 — `limited` :** Audit/research/benchmark existent. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Pas de plateforme longitudinale équivalente démontrée.`.
- **C5 — `partial` :** Provenance canonique et corpus de tests présents. Preuves : `E-MN-001`, `E-MN-002`, `E-MN-003`. Lacunes : `Reproductibilité de toutes les observations runtime non établie.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `2026-10-07T06:55:52Z`
- **dernier contrôle de signal :** `2026-10-07T06:55:52Z`
- **dernière inspection de code :** `2026-10-07T06:55:52Z`
- **dernière évaluation :** `2026-10-07T06:55:52Z`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
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
- **réévalué pendant ce passage :** `true`
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
- **dernier contrôle de signal :** `2026-10-07T06:55:52Z`
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
- **réévalué pendant ce passage :** `true`
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
- **dernier contrôle de signal :** `2026-10-07T06:55:52Z`
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
- **résumé :** Meilleur producteur de signal structuré parmi les composants inspectés aujourd'hui, mais pas une autorité complète sur le sens produit.
- **dernière observation :** `2026-10-07T06:55:52Z`
- **réévalué pendant ce passage :** `true`
- **disponibilité :** `released`

##### Garanties Ring — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** Policies attachées aux matériaux et attestations de supply-chain.
- **justification :** Chainloop fournit une chaîne substantielle policy→material→evaluation→gate avec références/digests, mais ne démontre pas que l'autorité et la complétude de ces policies représentent tout le sens produit gouverné.
- **preuves :** `E-CL-001`, `E-CL-002`
- **confiance :** `high`
- **dépendances externes :** aucun

##### Signal Cloud — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** PolicyEvaluation et attestation structurées.
- **justification :** Le signal est riche: matériau, policy digest/reference, requirements, skipped reasons, raw I/O, commit/auth/runner peuvent être conservés. L'autorité de l'évolution des exigences reste toutefois externe.
- **preuves :** `E-CL-001`, `E-CL-002`
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
- **R5 — `partial` :** skipped + reasons explicites. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Certaines policies peuvent être ignorées/désactivées par définition/configuration.`.
- **R6 — `limited` :** Verifier/gating automatiques. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Administration produit/repository plus large hors périmètre.`.
- **R7 — `supported` :** Références, digests, raw results, runtime overrides. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Autorité sémantique des policies externe.`.
- **R8 — `partial` :** Attestation et policy engine composés. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Boundary d'autorité/host hors verifier.`.
- **C1 — `supported` :** PolicyEvaluation capture un signal observation-time riche. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `La qualité sémantique dépend des policies attachées.`.
- **C2 — `limited` :** Références/digests permettent comparaison de versions. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Repair versus authorized requirement revision non natif.`.
- **C3 — `partial` :** Violations/skips/requirements constituent des labels utiles. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Ils ne qualifient pas seuls la légitimité d'une révision.`.
- **C4 — `partial` :** Audit et exploitation d'attestations possibles. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Pas d'équivalence Ring Cloud complète établie.`.
- **C5 — `supported` :** Attestation/CAS/raw results et contexte runner/auth structurent reproductibilité/audit. Preuves : `E-CL-001`, `E-CL-002`. Lacunes : `Réutilisation/licences des données non évaluées.`.

##### Surveillance

- **première observation :** `null`
- **première évaluation :** `2026-10-07T06:55:52Z`
- **dernier contrôle de signal :** `2026-10-07T06:55:52Z`
- **dernière inspection de code :** `2026-10-07T06:55:52Z`
- **dernière évaluation :** `2026-10-07T06:55:52Z`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
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
- **résumé :** Nouvel entrant important sur enforcement et intégrité de policy; pas encore équivalent aux garanties d'évolution gouvernée de Ring.
- **dernière observation :** `2026-10-07T06:55:52Z`
- **réévalué pendant ce passage :** `true`
- **disponibilité :** `released`

##### Garanties Ring — `L2` 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE

- **périmètre :** Enforcement de politiques/guardrails, couverture déclarée, lockfile et drift.
- **justification :** Chock couvre de façon substantielle l'enforcement et l'intégrité de certaines politiques, avec un toggle human-controlled qui reste activé sous drift; il ne démontre pas une chaîne générale Product Intent→autorité→obligations→évolution autorisée.
- **preuves :** `E-CH-001`, `E-CH-002`, `E-CH-003`
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
- **R5 — `supported` :** Certaines erreurs et drift gardent les guardrails actifs/fail closed. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Audit exhaustif des host failures restant.`.
- **R6 — `partial` :** CLI et hooks administrent enforcement. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Remédiation gouvernée générale non démontrée.`.
- **R7 — `supported` :** Digests/lockfile/drift explicites. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Autorité sémantique des changements distincte de l'intégrité.`.
- **R8 — `partial` :** Plusieurs surfaces hook/CI/git. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Certaines défaillances hôte restent bornées par les capacités d'intégration.`.
- **C1 — `partial` :** Évidence de policy/coverage/gates. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Contexte d'autorité complet non capturé.`.
- **C2 — `limited` :** Lockfile permet de suivre certains changements. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Repair/revision/weakening non distingués génériquement.`.
- **C3 — `unknown` :** Pas de label d'apprentissage gouverné évalué. Preuves : aucun. Lacunes : `Évaluer les exports/événements éventuels.`.
- **C4 — `unknown` :** Pas d'usage longitudinal évalué. Preuves : aucun. Lacunes : `Évaluer les surfaces analytiques éventuelles.`.
- **C5 — `partial` :** Hashes et evidence basis structurent la reproductibilité. Preuves : `E-CH-001`, `E-CH-002`, `E-CH-003`. Lacunes : `Rétention/autorisation downstream non évaluées.`.

##### Surveillance

- **première observation :** `2026-10-07T06:55:52Z`
- **première évaluation :** `2026-10-07T06:55:52Z`
- **dernier contrôle de signal :** `2026-10-07T06:55:52Z`
- **dernière inspection de code :** `2026-10-07T06:55:52Z`
- **dernière évaluation :** `2026-10-07T06:55:52Z`
- **prochaine échéance :** `2026-10-14T06:55:52Z`
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
- **réévalué pendant ce passage :** `true`
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
- **dernier contrôle de signal :** `2026-10-07T06:55:52Z`
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
- **réévalué pendant ce passage :** `true`
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
- **dernier contrôle de signal :** `2026-10-07T06:55:52Z`
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

## 4. Évolutions techniques et constats

### RCW-F-001 — Agent-callable decision path can create accepted workflow decisions

- **acteur / composant :** `dynosai` / `dynosai-core`
- **cycle de vie :** `new`
- **causes de changement :** `new_evidence`
- **constats précédents :** aucun
- **axes :** `R1`, `R3`, `C2`, `C3`
- **preuves :** `E-DY-003`, `E-DY-004`, `E-DY-005`
- **changement observé :** Baseline: le chemin MCP dynosai_register_decision est disponible pour l'agent et appelle register_decision, qui persiste status=accepted.
- **effet sur les garanties :** Cela empêche de considérer la séparation proposition/acceptation comme structurellement fermée sur ce chemin.
- **effet downstream :** Une décision ainsi créée peut contaminer l'interprétation downstream si elle est traitée comme autorité humaine sans provenance distincte.
- **lacune restante :** Établir ou ajouter une frontière d'autorité qui empêche l'agent de créer seul une décision accepted.
- **prochaine investigation :** Rechercher toutes les écritures dans decisions et les tests de provenance/elicitation; reproduire le scénario dans un environnement isolé.

### RCW-F-002 — Substantial governed workflow and evidence chain

- **acteur / composant :** `dynosai` / `dynosai-core`
- **cycle de vie :** `new`
- **causes de changement :** `new_evidence`
- **constats précédents :** aucun
- **axes :** `R2`, `R4`, `R6`, `R7`, `C1`, `C4`
- **preuves :** `E-DY-001`, `E-DY-002`, `E-DY-003`
- **changement observé :** Baseline: spec/plan approvals, stale-plan checks, worktrees, independent result verification and requirement-to-evidence integrity are implemented.
- **effet sur les garanties :** DynosAI constitue un substitut partiel substantiel sur l'administration gouvernée et la preuve de travail.
- **effet downstream :** Il produit déjà un corpus structuré de runs, validations, preuves et décisions exploitable pour évaluations.
- **lacune restante :** Fermer l'autorité des décisions et démontrer la distinction longitudinale repair/revision/weakening.
- **prochaine investigation :** Tester un changement de spec/test après échec et suivre le signal produit.

### RCW-F-003 — Canonical authority is real, but DG1 effective-decision semantics remain future work

- **acteur / composant :** `mneme` / `mneme-core`
- **cycle de vie :** `new`
- **causes de changement :** `new_evidence`
- **constats précédents :** aucun
- **axes :** `R1`, `R2`, `R3`, `R7`, `R8`
- **preuves :** `E-MN-001`, `E-MN-002`, `E-MN-003`
- **changement observé :** Baseline: D1 dispose de writers canoniques fail-closed; le roadmap place encore DG1 après D1 pour autorité source, applicability, precedence, waivers et effective-decision resolution.
- **effet sur les garanties :** Mneme couvre une partie substantielle de Ring mais ne ferme pas encore la chaîne générale d'applicabilité/autorité.
- **effet downstream :** Le signal de décision/enforcement est utile, sans équivalence complète aux labels longitudinaux Ring Cloud.
- **lacune restante :** Clôture D1 puis DG1, et attestation de tests confiable différée.
- **prochaine investigation :** Suivre chaque merge D1E/D1F puis le premier code DG1.

### RCW-F-004 — Guardrail toggle and policy drift protection provide real but scoped governance

- **acteur / composant :** `chock` / `chock-core`
- **cycle de vie :** `new`
- **causes de changement :** `new_evidence`
- **constats précédents :** aucun
- **axes :** `R1`, `R3`, `R5`, `R7`
- **preuves :** `E-CH-001`, `E-CH-002`, `E-CH-003`
- **changement observé :** Baseline: guardrail toggles modifiés hors chemin attendu sont ignorés, gardant les guardrails ON; lock/digests détectent drift et la couverture est explicitement graduée.
- **effet sur les garanties :** Chock dépasse le simple linting: il protège réellement certaines frontières de policy, sans établir une gouvernance générale du Product Intent.
- **effet downstream :** Produit de l'évidence de gating/drift mais peu de sémantique longitudinale démontrée.
- **lacune restante :** Autorité générale des mutations de policy et liaison complète à l'état accepté.
- **prochaine investigation :** Tracer les commandes de policy install/update/disable et leurs contrôles d'autorité.

### RCW-F-005 — Pre-action enforcement with cryptographic receipts, but receipt durability is best-effort

- **acteur / composant :** `vectimus` / `vectimus-core`
- **cycle de vie :** `new`
- **causes de changement :** `new_evidence`
- **constats précédents :** aucun
- **axes :** `R4`, `R5`, `R7`, `C1`, `C2`, `C5`
- **preuves :** `E-VE-001`, `E-VE-002`, `E-VE-003`, `E-VE-004`
- **changement observé :** Baseline: Vectimus fail-closes normalization, évalue avant action, peut signer les receipts; leur écriture est asynchrone, optional/best-effort et des rules peuvent être temporairement désactivées.
- **effet sur les garanties :** Enforcement réel mais autorité de l'évolution des policies non démontrée.
- **effet downstream :** Receipt utile comme primitive de signal, mais pas encore comme registre longitudinal garanti.
- **lacune restante :** Autorité des overrides/disables et durabilité obligatoire du signal.
- **prochaine investigation :** Auditer rule_cmd/config et server mode, puis reproduire perte/absence de receipt.

### RCW-F-006 — ACS deliberately stops at the policy-decision boundary

- **acteur / composant :** `acs` / `acs-runtime`
- **cycle de vie :** `new`
- **causes de changement :** `new_evidence`
- **constats précédents :** aucun
- **axes :** `R1`, `R4`, `R8`, `C1`, `C5`
- **preuves :** `E-AC-001`, `E-AC-002`
- **changement observé :** Baseline: ACS retourne verdict + policy_input et laisse enforcement, approval resolution, identity et record keeping à l'hôte.
- **effet sur les garanties :** ACS est une primitive composable, pas une chaîne Ring end-to-end autonome.
- **effet downstream :** Le signal est exploitable si l'hôte le capture correctement; ACS ne fournit pas la longitudinalité.
- **lacune restante :** Évaluer une composition hôte complète, pas seulement le moteur.
- **prochaine investigation :** Choisir une intégration hôte publique ACS et suivre interception→enforcement→audit.

### RCW-F-007 — AGT policy core has become an ACS compatibility shim

- **acteur / composant :** `microsoft-agt` / `policy-engine-core`
- **cycle de vie :** `new`
- **causes de changement :** `new_evidence`
- **constats précédents :** aucun
- **axes :** `R7`, `R8`, `C1`
- **preuves :** `E-MS-001`
- **changement observé :** Baseline: le core AGT réexporte ACS et documente une limite de provenance des URL-sourced manifests dans la version ACS ciblée.
- **effet sur les garanties :** Le niveau du core ne doit pas être compté séparément comme une seconde implémentation complète.
- **effet downstream :** Le signal dépend des mêmes responsabilités hôte/ACS.
- **lacune restante :** Audit du toolkit hors core et vérification de la version ACS réellement intégrée.
- **prochaine investigation :** Inspecter plugin/host integration et le correctif upstream de provenance.

### RCW-F-008 — Strong policy-evaluation attestation signal without general product-authority semantics

- **acteur / composant :** `chainloop` / `policies-attestation`
- **cycle de vie :** `new`
- **causes de changement :** `new_evidence`
- **constats précédents :** aucun
- **axes :** `R2`, `R4`, `R7`, `C1`, `C3`, `C5`
- **preuves :** `E-CL-001`, `E-CL-002`
- **changement observé :** Baseline: Chainloop relie policies, digests, requirements, material, violations/skips/raw results et attestation context.
- **effet sur les garanties :** Substitut partiel substantiel pour conformité/policy evidence, pas pour l'autorité complète du sens produit.
- **effet downstream :** Signal de haute valeur pour audit et datasets de conformité scoped; ne distingue pas seul réparation d'une révision d'exigence.
- **lacune restante :** Autorité des policy attachments/contracts et continuité de leur évolution.
- **prochaine investigation :** Tracer la mutation des contracts/policies et l'admission d'attestations après changement de gouvernance.

## 5. Recherche de nouveaux entrants et compositions

- **statut de découverte :** `partial`
- **acteurs admis :** `chock`, `dynosai`, `vectimus`
- **nouveaux entrants :** `chock`, `dynosai`, `vectimus`

### Recherches réellement effectuées

1. **web search** — `2026-10-07T06:55:52Z` — couverture `partial`
   - Requête : AI coding agent governance repository policy requirements traceability new open source
   - Résultat : Recherche sémantique effectuée; résultats filtrés pour pertinence Ring/Ring Cloud. Les claims décisifs ne sont pas acceptés sans source primaire/code.
   - Preuves : aucun
2. **web search** — `2026-10-07T06:55:52Z` — couverture `partial`
   - Requête : coding agent governance policy engine software repository agentic development
   - Résultat : Recherche sémantique effectuée; résultats filtrés pour pertinence Ring/Ring Cloud. Les claims décisifs ne sont pas acceptés sans source primaire/code.
   - Preuves : aucun
3. **web search** — `2026-10-07T06:55:52Z` — couverture `partial`
   - Requête : agentic software engineering requirements traceability coding agents new tool
   - Résultat : Recherche sémantique effectuée; résultats filtrés pour pertinence Ring/Ring Cloud. Les claims décisifs ne sont pas acceptés sans source primaire/code.
   - Preuves : aucun
4. **web search** — `2026-10-07T06:55:52Z` — couverture `partial`
   - Requête : AI coding agent repair dataset evaluation new framework software engineering agents
   - Résultat : Recherche sémantique effectuée; résultats filtrés pour pertinence Ring/Ring Cloud. Les claims décisifs ne sont pas acceptés sans source primaire/code.
   - Preuves : aucun
5. **web search** — `2026-10-07T06:55:52Z` — couverture `partial`
   - Requête : governed coding agents policy as code repository enforcement AI agents
   - Résultat : Recherche sémantique effectuée; résultats filtrés pour pertinence Ring/Ring Cloud. Les claims décisifs ne sont pas acceptés sans source primaire/code.
   - Preuves : aucun
6. **web search** — `2026-10-07T06:55:52Z` — couverture `partial`
   - Requête : software factory coding agents governance requirements tests intent agent
   - Résultat : Recherche sémantique effectuée; résultats filtrés pour pertinence Ring/Ring Cloud. Les claims décisifs ne sont pas acceptés sans source primaire/code.
   - Preuves : aucun
7. **web search** — `2026-10-07T06:55:52Z` — couverture `partial`
   - Requête : agent evaluation repair trajectory dataset coding agents 2026
   - Résultat : Recherche sémantique effectuée; résultats filtrés pour pertinence Ring/Ring Cloud. Les claims décisifs ne sont pas acceptés sans source primaire/code.
   - Preuves : aucun
8. **web search** — `2026-10-07T06:55:52Z` — couverture `partial`
   - Requête : formal verification coding agents requirements governance software agents 2026
   - Résultat : Recherche sémantique effectuée; résultats filtrés pour pertinence Ring/Ring Cloud. Les claims décisifs ne sont pas acceptés sans source primaire/code.
   - Preuves : aucun
9. **web search** — `2026-10-07T06:55:52Z` — couverture `partial`
   - Requête : Nool software governance agent code repository architecture policies state-bound execution
   - Résultat : Recherche sémantique effectuée; résultats filtrés pour pertinence Ring/Ring Cloud. Les claims décisifs ne sont pas acceptés sans source primaire/code.
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

### Doublons, forks, renommages et lignées

- Microsoft Agent Governance Toolkit policy-engine core is currently a compatibility shim over Agent Control Specification; both identities are retained but linked, not double-counted as independent core engines.

### Limites de découverte

- La découverte web n'est pas exhaustive.
- Les candidats pending n'ont pas encore reçu une inspection technique suffisante pour être notés.
- Les résultats de recherche secondaires servent à la découverte seulement; les ratings établis reposent sur des sources primaires/code inspecté.

## 6. Trajectoires

- Première baseline formelle: aucune trajectoire inter-rapport ne peut encore être attribuée à une évolution technique concurrente.

## 7. Implications pour le positionnement

- Le positionnement public de Ring doit continuer à mettre en avant la continuité d'autorité et la distinction repair/authorized evolution/unauthorized weakening, pas le simple fait d'avoir des policies ou des gates.
- Il serait prématuré d'affirmer publiquement qu'aucun concurrent ne couvre la chaîne: 32+ pistes restent non évaluées dans cette baseline et plusieurs nouveaux candidats crédibles ont été découverts.
- DynosAI devient une priorité élevée de veille car il combine gouvernance du workflow, états durables, gates, evidence et reprise; son écart d'autorité sur register_decision est précisément le type de différence que Ring doit pouvoir expliquer.
- Chainloop est une référence importante pour le signal Cloud: il montre qu'une partie des observations gouvernées peut être produite sans Ring, ce qui oblige Ring Cloud à se différencier sur la validité longitudinale du sens, pas sur la simple présence d'attestations.

## 8. Couverture, retards et investigations ouvertes

### Couverture

- **fanilosendrison/ring authority + watch framework — `complete` :** curseur `null` → `2dba6f54e9eac14b9e304d54a0f2e564dcc9111c`. Autorités, positionnement, méthodologie, schéma et watchlist lus à la tête observée.
- **open web discovery — `partial` :** curseur `null` → `2026-10-07T06:55:52Z`. Neuf recherches sémantiques ont été exécutées; couverture ouverte mais non exhaustive.
- **MnemeHQ/mneme — `partial` :** curseur `null` → `b4035655c5ada6cfcaa0ea153ea22caedd672e61`. Roadmap, writer canonique et tests ciblés inspectés; suite non exécutée.
- **pablo-cano/dynosai — `partial` :** curseur `null` → `019f46579e081cb9154fa63b49177e2654020203`. Architecture, validation integrity, engine, MCP et instructions agent inspectés; pas d'exécution.
- **open-coder-ai/chock — `partial` :** curseur `null` → `da248c38f0d3f3e82e00e8b0342e919879819f73`. Coverage, toggle et lock inspectés; pas d'exécution.
- **vectimus/vectimus — `partial` :** curseur `null` → `99ee6c7ad28e9a83306d3e17f0ce973a47e4d6b4`. Hook, receipts, loader et tests de disable inspectés; pas d'exécution.
- **responsibleai/agent-control-spec — `partial` :** curseur `null` → `f2334533651d726b4e9daac170e5116ac3135794`. README et runtime central inspectés.
- **microsoft/agent-governance-toolkit — `partial` :** curseur `null` → `c4d7e3375c985098e54e802eb32c965ddbc955c7`. Core policy-engine inspecté; toolkit complet non couvert.
- **chainloop-dev/chainloop — `partial` :** curseur `null` → `10df49bc7b7e16772a96a03096765da5bc67699c`. Policy verifier et attestation schema inspectés; control plane complet non couvert.
- **remaining discovery seeds — `not_checked` :** curseur `null` → `null`. Ces acteurs restent U et doivent être évalués dans les passages suivants; aucune faible menace n'est inférée de l'absence d'inspection.

- **acteurs en retard :** aucun
- **continuité du radar :** `verified`
- **notes de réconciliation :** Aucun rapport RCW antérieur n'a été trouvé dans le repository; cette baseline part des 39 discovery seeds installés et ajoute trois nouveaux entrants évalués. Les analyses de chat antérieures ne sont pas importées comme preuves vérifiées.

### Questions ouvertes

- DynosAI: le chemin agent-callable register_decision possède-t-il une protection d'autorité ailleurs dans une couche non inspectée?
- Mneme: quand D1E-D1F puis DG1 ferment-ils les écarts d'applicabilité/précédence/waiver?
- Chock: qui peut autoriser et publier une modification de policy en dehors du toggle de guardrails?
- Vectimus: quelle autorité gouverne project packs, rule disable et server-mode approvals?
- Chainloop: comment les policy attachments/contracts changent-ils sous autorité et comment ce changement est-il lié à l'attestation?
- Nool et les autres seeds U: identité, code accessible et garanties effectives doivent encore être établis avant notation.

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

## 10. Références historiques et corrections

- **rapports précédents :** aucun
- **rapports corrigés :** aucun
- **acteurs précédents :** aucun
- **nouvelles admissions :** `acs`, `chainloop`, `chock`, `dynosai`, `microsoft-agt`, `mneme`, `vectimus`
- **radar courant :** `nool`, `mneme`, `codespeak`, `qodo`, `packmind`, `tessl`, `microsoft-agt`, `acs`, `chainloop`, `entire`, `langsmith`, `braintrust`, `langfuse`, `phoenix`, `weave`, `kiro`, `augment-intent`, `8090`, `coderabbit`, `greptile`, `endor-labs`, `rippletide`, `google-agent-governance`, `github-agent-platform`, `openai-codex`, `anthropic-claude-code`, `imandra`, `antithesis`, `opa`, `in-toto`, `spec-kit`, `openspec`, `jama`, `strongdm-factory`, `prime-intellect`, `swe-gym`, `swe-smith`, `r2e-gym`, `poolside`, `chock`, `dynosai`, `vectimus`
- **arrêts demandés par l’utilisateur :** aucun
- **références des instructions utilisateur :** aucun

Les informations de continuité ci-dessus sont celles du passage historique. Elles ne sont pas réécrites en fonction de l’état actuel de l’archive.
