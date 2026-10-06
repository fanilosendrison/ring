---
okf_version: "1.0"
kind: "KnowledgeAsset"
asset_type: "report-projection-template"
domain: "ring-competitive-watch"
severity: "strict"
name: "Competitive Guarantee Watch Report Template"
---

# Veille Ring / Ring Cloud — Rapport du {{date_locale}}

- **report_id :** `{{report_id}}`
- **type :** `{{report_kind}}`
- **fenêtre observée :** `{{period_start}}` → `{{period_end}}`
- **généré à :** `{{generated_at}}`
- **référence Ring :** `{{basis.ring_repository}}@{{basis.ring_commit}}`
- **version du schéma :** `{{schema_version}}`
- **version de la méthode :** `{{methodology_version}}`
- **statut de Ring Cloud :** `{{basis.cloud_status}}`
- **caractère partiel éventuel :** `{{partiality_statement}}`

Ce modèle est une projection de `report.json`. Il ne contient aucune
observation concurrentielle. Le rendu ne doit ajouter aucun jugement, niveau,
fait, source ou conclusion absent du JSON.

## 1. Fenêtre d’observation et base de comparaison

{{observation_window_and_basis}}

Présenter les sources de référence et leurs révisions immuables, y compris la
méthode, le schéma et le modèle lorsqu'ils sont utilisés. Distinguer la période
couverte de la date de génération et expliciter toute histoire indisponible.

## 2. Synthèse

{{summary}}

Préserver les limites, inconnues et couvertures partielles. Une absence de
preuve publique ne devient pas une preuve d'absence de capacité.

## 3. Tableau des niveaux de menace

<!-- markdownlint-disable MD013 -->

| Acteur / composant | Garanties Ring | Signal Cloud | Usages downstream | Confiance | Disponibilité | Dernière observation | Réévalué pendant ce passage ? |
| ------------------ | -------------- | ------------ | ----------------- | --------- | ------------- | -------------------- | ------------------------------ |
| {{display_name}} / `{{component_id}}` | {{ring_guarantees_color}} {{ring_guarantees_label}} | {{cloud_signal_color}} {{cloud_signal_label}} | {{cloud_downstream_color}} {{cloud_downstream_label}} | {{dimension_confidences}} | {{availability}} | {{last_observed_at}} | {{revalidated_this_run}} |

<!-- markdownlint-enable MD013 -->

Afficher la couleur **et** le libellé depuis chaque `level` :

- `U` — ⚪ INDETERMINATE ;
- `L0` — 🟢 ADJACENT_OR_COMPLEMENTARY ;
- `L1` — 🟡 ISOLATED_PRIMITIVE ;
- `L2` — 🟠 SUBSTANTIAL_PARTIAL_SUBSTITUTE ;
- `L3` — 🔴 NEAR_EQUIVALENCE ;
- `L4` — 🟣 DEMONSTRATED_SCOPED_EQUIVALENCE.

Représenter tous les acteurs conservés dans le radar, y compris ceux dont les
notes sont reconduites, ceux qui sont dormants ou arrêtés par instruction, et
ceux dont l'évaluation reste indéterminée. Ne calculer aucune moyenne globale.

### Détails par acteur et composant

#### {{display_name}} — `{{actor_id}}` / `{{component_id}}`

- **rôles :** {{roles}}
- **résumé :** {{actor.summary}}
- **périmètre, justification et preuves des trois notes :** {{rating_details}}
- **dépendances externes :** {{external_dependencies}}
- **axes R1–R8 et C1–C5 :** {{axis_assessments}}
- **dernière inspection de code :** {{monitoring.last_code_inspection_at}}
- **prochaine échéance :** {{monitoring.next_review_due_at}}
- **couverture :** {{monitoring.coverage_status}}
- **cycle de vie :** {{monitoring.actor_lifecycle}}
- **questions et investigations en attente :** {{monitoring.pending_investigations}}

## 4. Évolutions techniques et constats

{{findings}}

Chaque constat indique son identifiant stable, son acteur et composant, son
cycle de vie, ses axes, ses causes de changement et ses `evidence_ids`. Une
fermeture de constat ne retire pas l'acteur. Une correction indique clairement
ce qui était faux dans le rapport antérieur et référence le constat corrigé sous
la forme `<report_id>#<finding_id>`.

## 5. Recherche de nouveaux entrants et compositions

- **statut de découverte :** {{discovery.status}}
- **recherches réellement effectuées :** {{discovery.searches}}
- **acteurs admis :** {{discovery.admitted_actor_ids}}
- **candidats en attente :** {{discovery.pending_candidates}}
- **doublons, forks, renommages et lignées :** {{discovery.duplicates_and_lineage}}
- **limites :** {{discovery.limitations}}

{{new_entrants_and_available_compositions}}

Ne présenter une composition comme disponible que lorsque ses composants et
ses frontières sont réellement accessibles et adéquats.

## 6. Trajectoires

{{trajectories}}

Dans le rapport hebdomadaire du premier lundi du mois, cette section porte la
synthèse mensuelle. Distinguer `implementation_change`, `new_evidence`,
`assessment_correction`, `ring_baseline_change` et `methodology_change`. Seul
`implementation_change` établit une progression technique concurrente.

## 7. Implications pour le positionnement

{{positioning_implications}}

Ces implications restent des observations de recherche. Elles ne modifient ni
le Product Intent, ni les rationales, ni le statut candidat de Ring Cloud.

## 8. Couverture, retards et investigations ouvertes

{{coverage}}

- **acteurs en retard :** {{radar_continuity.overdue_actor_ids}}
- **questions ouvertes :** {{open_questions}}
- **continuité du radar :** {{radar_continuity.status}}
- **notes de réconciliation :** {{radar_continuity.reconciliation_notes}}

Un passage non réalisé reste `not_checked` ou `overdue`; ses dates et curseurs
ne sont pas avancés. Exposer les dates reconduites et définir
`revalidated_this_run` à `false` lorsqu'aucune nouvelle observation n'a eu lieu.

## 9. Sources et éléments de preuve

{{evidence}}

Pour chaque élément, afficher son identifiant, sa catégorie, son URL, les dates
d'événement/publication/observation disponibles, la révision et le chemin
éventuels, la proposition étayée, les limites et, pour `reproduced`, les détails
d'exécution. Ne pas confondre code lu, tests lus, tests exécutés et preuve
vérifiée.

## 10. Références historiques et corrections

- **rapports précédents :** {{previous_report_ids}}
- **rapports corrigés :** {{corrects}}
- **acteurs précédents :** {{radar_continuity.previous_actor_ids}}
- **nouvelles admissions :** {{radar_continuity.newly_admitted_actor_ids}}
- **radar courant :** {{radar_continuity.current_actor_ids}}
- **arrêts demandés par l'utilisateur :** {{radar_continuity.user_stopped_actor_ids}}
- **références des instructions utilisateur :** {{radar_continuity.user_instruction_refs}}

{{historical_references_and_corrections}}

La mise en forme ne remplace jamais les limites et incertitudes. Le tableau et
les détails sont rendus depuis le JSON ; ils ne sont pas édités indépendamment
pour changer une couleur ou une conclusion.
