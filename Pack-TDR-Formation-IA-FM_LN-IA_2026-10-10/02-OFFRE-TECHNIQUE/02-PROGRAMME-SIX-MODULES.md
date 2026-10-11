# Programme pédagogique proposé — six modules du TDR

**Proposition de dimensionnement :** 6 h pédagogiques par module et par participant, soit 36 h ; 30 % d'apports/démonstrations, 70 % d'atelier en moyenne. Ces durées sont **proposées**, non prescrites par les TDR. L'hypothèse suppose l'accès à un ordinateur par participant et à un logiciel approuvé.

## Module 1 — Comprendre l'IA générative et sécuriser son usage

**Durée proposée :** 6 h (2 h d'apports + 4 h de mise en situation). **But :** comprendre utilités et limites des outils et reconnaître les données non transmissibles.

- Concepts accessibles : IA générative, réponses probabilistes, erreurs, hallucinations, biais, limites de l'exactitude.
- Démonstration : partir d'une tâche de secrétariat/gestion sans donnée confidentielle ; observer une réponse correcte et une réponse trompeuse.
- Exercices : classer des situations « autorisé / à vérifier / interdit par défaut » ; reformuler une demande sans données personnelles.
- **Production et évaluation :** fiche d'usage et checklist pré-saisie. Critère : repère 100 % des cas contenant des informations médicales personnelles dans la série d'exercice.

## Module 2 — Maîtriser la formulation des prompts

**Durée :** 6 h (1,5 h de méthode + 4,5 h de pratique). **But :** produire un prompt métier testé et corrigé.

- Structure : rôle / tâche / contexte / documents admissibles / contraintes / format / critères de contrôle / demandes de clarification.
- Démonstration : transformer « résume ce rapport » en instruction cadrée avec audience et références documentaires.
- Exercices : rédiger un prompt V1, comparer à une grille, corriger la sortie et livrer V2.
- **Production et évaluation :** `prompt-structure-v1.md`, sortie V1/V2 et grille d'évaluation du résultat. Critère : présence des sept champs essentiels et contrôle explicite.

## Module 3 — Documents professionnels, recherche et synthèse

**Durée :** 6 h (1,5 h + 4,5 h). **But :** créer un document professionnel exploitable et sourcé.

- Cas : note administrative, fiche technique, TDR, compte rendu, plan de présentation, synthèse de sources publiques.
- Démonstration : extraire les obligations d'un faux TDR et construire une synthèse avec attribution des éléments à la source.
- Exercices : comparer résumé IA au texte fourni, repérer une citation fabriquée, améliorer une note.
- **Production :** note de synthèse d'une à deux pages + registre des vérifications. Critère : aucun chiffre présenté comme source s'il n'est pas présent dans le document.

## Module 4 — Excel, données, reporting et aide à la décision

**Durée :** 6 h (1,5 h + 4,5 h). **But :** exploiter un tableau fictif, vérifier les calculs et expliquer des écarts.

- Préparation : schéma CSV, types, valeurs manquantes et doublons ; somme, ratio, indicateur et graphiques simples.
- Démonstration : `donnees_indicateurs_100pourcent_fictives.csv` avec régions codées R01–R12 et activités fictives VIH/TB.
- Exercices : calculer réalisation = réalisées / prévues ; complétude = rapports reçus / attendus ; dépense / budget ; produire un tableau commenté.
- **Production :** tableau de reporting et note de décision sans attribution clinique. Critères : totaux recalculés manuellement, dénominateurs explicites, anomalies signalées.

## Module 5 — IA responsable, sécurité et approfondissements

**Durée :** 6 h (2 h + 4 h). **But :** appliquer une gouvernance opérationnelle de l'IA.

- Règles : confidentialité et secret professionnel, données sensibles, autorisations d'outil, traçabilité, supervision humaine.
- Atelier : audits croisés de prompts et résultats ; rejeter / corriger les entrées risquées.
- Approfondissements **optionnels** : automatisation légère, workflows, agents IA, n8n, QGIS — seulement si diagnostic et validation DELM le justifient, sans rogner le socle.
- **Production :** charte personnelle d'usage et protocole de contrôle d'un document/indicateur.

## Module 6 — Cas intégrateur, évaluation finale et plan d'action

**Durée :** 6 h (0,5 h consignes + 4,5 h réalisation et soutenance + 1 h bilan). **But :** réaliser une tâche complète et prouver l'autonomie.

- Cas simulé : préparation d'une note mensuelle de suivi d'activités associatives à partir de fichiers fictifs.
- Étapes : cadrage → prompt → brouillon → calcul indépendant → validation sources → correction → présentation de 5 minutes → plan d'action.
- **Production :** dossier final incluant note synthétique, indicateurs contrôlés, prompt révisé, checklist, plan d'usage individuel à 30 jours.
- **Évaluation :** même grille que l'entrée + rubriques de compétence. Aucun outil IA ne décide seul d'une action de santé publique.

## Attendus transversaux

À chaque module, les participants conservent les traces : **source admissible**, **prompt**, **sortie**, **contrôle**, **correction**, **preuve de compétence**. Des adaptations métier sont introduites pour gestion administrative, finances, surveillance et suivi-évaluation, en restant sur des dossiers simulés.

**Validation nécessaire :** niveau des apprenants, calendrier précis, compétences Excel, autorisations informatiques, accessibilité et choix des outils.
