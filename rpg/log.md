# RPG — Journal de progression

Ce document enregistre **exclusivement** les quêtes validées.

Chaque entrée doit être :

- factuelle,
- datée,
- liée à un livrable identifiable,
- cohérente avec les règles définies dans `rpg.md`.

Aucune entrée ne doit être ajoutée sans validation réelle d’une quête.

## Entrées

2026-01-01
Quête: MQ-01 — Backend template prêt pour la production
Type: Main Quest

Impact:

- Level: +1
- Engineering: +1
- Autonomy: +1

Livrable:

- Dépôt backend Go prêt à être cloné (structure standardisée, API conventions, erreurs typées, validation frontière, corrections de patterns fragiles)

Notes:

- Template orienté production Horizon 1
- Patterns fragiles explicitement identifiés et corrigés
- Hors scope assumé: DB, auth, Docker, CI/CD

```
// Exemple d'entrée

### YYYY-MM-DD

**Quête**: MQ-XX / SQ-XX — Titre de la quête
**Type**: Main Quest | Side Quest
**Impact**:

- Level: +0 / +1
- Engineering: +0 / +1
- Delivery: +0 / +1
- Autonomy: +0 / +1
- Product Sense: +0 / +1
- Leverage: +0 / +1

**Livrable**:

- Lien vers dépôt, service déployé, document ou preuve tangible

**Notes**:

- Faits observables uniquement (problèmes rencontrés, décisions prises)
- Pas d’auto-évaluation vague
```
