# Six ateliers reproductibles — données et documents fictifs

Toutes les situations et toutes les valeurs sont **fabriquées pour la formation**. Il ne s'agit pas de statistiques VIH/TB du Maroc. Les activités sont simulées et ne comportent aucune donnée individuelle.

## Atelier 1 — Classer les usages et les données (M1)

**Scénario :** un collaborateur veut demander à un outil externe de mettre en forme (a) une note administrative sans nom ni secret ; (b) un tableau de noms de patients ; (c) une feuille de dépenses internes ; (d) un fichier fictif d'indicateurs. **Tâche :** classer chaque cas « utilisable selon autorisation », « validation nécessaire » ou « interdit par défaut ». **Sortie :** fiche d'usage. **Contrôle :** la donnée de santé personnelle est systématiquement interdite dans l'outil non autorisé.

## Atelier 2 — Construire prompt-structure-v1.md (M2)

**Scénario :** préparation d'un tableau de suivi de 12 régions codées R01–R12. **Tâche :** écrire un prompt avec rôle, entrée fictive, colonnes, contrôle des dénominateurs, format de tableau et phrases de limite. **Sortie :** `prompt-structure-v1.md` et révision V2. **Contrôle :** comparer le prompt à la rubrique C2 de l'évaluation.

## Atelier 3 — Produire une note et contrôler les sources (M3)

**Scénario :** une direction fictive commande une note d'organisation d'un atelier informatique pour professionnels. **Tâche :** synthétiser un faux TDR d'une page fourni par le formateur, produire une note et relier les éléments à la source. **Sortie :** note d'une page. **Contrôle :** ne pas ajouter de date, coût, organisme ou métrique non fourni.

## Atelier 4 — Exploiter le CSV et produire un reporting (M4)

**Entrée :** `donnees_indicateurs_100pourcent_fictives.csv` avec deux lignes par région codée (VIH et TB). **Tâche :** vérifier le schéma, sommer, calculer les taux de réalisation et de complétude, repérer les écarts. **Sortie :** tableau + note expliquant les constats, **sans prétendre expliquer les causes**.

**Formules :** taux activités = 100 × somme(activites_realisees) / somme(activites_prevues) ; taux rapports = 100 × somme(rapports_recus) / somme(rapports_attendus) ; exécution budget = 100 × somme(depenses_fictives_mad) / somme(budget_fictif_mad). Ces formules sont **pondérées par les effectifs** ; ne pas faire la moyenne naïve des taux régionaux.

## Atelier 5 — Auditer un prompt de santé publique (M5)

**Scénario :** un prompt contient un identifiant de patient fictif, une date de naissance fictive et demande une décision clinique. **Tâche :** rejeter, identifier les catégories problématiques et reformuler vers un exercice synthétique et non clinique. **Sortie :** rapport d'audit « accepter / corriger / rejeter ». **Contrôle :** aucune décision clinique automatisée.

## Atelier 6 — Mini-portfolio de suivi (M6)

**Mission :** un responsable de projet fictif doit préparer un point de gestion sur les activités prévues/réalisées, rapports et budgets simulés. **Tâche :** établir cadre, prompt, tableau vérifié, note, présentation rapide et plan à 30 jours. **Sortie :** pack personnel avec `prompt-v2`, `reporting`, `note`, `checklist`, `plan-action`.

## Fiche commune d'observation

| Élément | Rempli par participant |
|---|---|
| Tâche / besoin | [ ] |
| Entrée admissible | [ ] |
| Prompt V1 et corrections | [ ] |
| Résultat et source | [ ] |
| Calcul / vérification | [ ] |
| Décision humaine / correction | [ ] |
| Preuve finale | [ ] |

**Règle de facilitation :** ne jamais laisser une réponse de modèle être la seule référence d'un indicateur ou d'une décision de terrain.
