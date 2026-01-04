# RPG — Journal de progression

Ce document enregistre **exclusivement** les quêtes validées.

Chaque entrée doit être :

- factuelle,
- datée,
- liée à un livrable identifiable,
- cohérente avec les règles définies dans `rpg.md`.

Aucune entrée ne doit être ajoutée sans validation réelle d’une quête.

## Entrées

### [2026-01-04] — MQ-02 VALIDÉE — Produit full-stack minimal

#### Statut

**VALIDÉE**

#### Résumé

La quête **MQ-02 — Produit full-stack minimal** est validée.  
Le livrable constitue un produit full-stack fonctionnel et utilisable par un tiers, répondant strictement aux critères de la quête et de l’Horizon 1.  
L’application _Tasks Manager_ démontre une autonomie produit complète : conception, développement, intégration frontend ↔ backend, gestion des erreurs, chargements et déploiement local.

---

#### Preuves clés de validation

##### UI complète consommant une API backend

- 3 pages fonctionnelles :
  - Liste : `src/app/tasks/page.tsx`
  - Création : `src/app/tasks/new/page.tsx`
  - Détail : `src/app/tasks/[id]/page.tsx`
- Client HTTP centralisé avec gestion d’erreurs standardisée :  
  `src/lib/api/http.ts`
- Endpoints consommés :  
  `GET /api/v1/tasks`, `POST /api/v1/tasks`, `GET /api/v1/tasks/:id`
- Proxy Next.js configuré via `next.config.ts`
- Backend REST exposant les routes Tasks (Go)

##### Formulaires robustes

- Validation côté client (champ requis, longueur, trim)
- Feedback utilisateur explicite (“Task name is required.”)
- État de soumission géré (`isSubmitting`)
- Validation backend cohérente (DTO + binding)
- Accessibilité minimale : `aria-invalid`, message associé

##### Gestion explicite des chargements et erreurs

- Loader réutilisable (`components/Loader.tsx`)
- Loading UI par route (`tasks/loading.tsx`, `tasks/[id]/loading.tsx`)
- Gestion d’erreurs typée via `ApiError` (`network`, `http`, `unknown`)
- Distinction claire erreurs réseau vs erreurs HTTP
- Affichage du `request_id` pour diagnostic
- Erreur 404 spécifique pour tâche inexistante

##### Produit utilisable par un tiers

- Parcours utilisateur documenté dans le README
- Instructions de démarrage claires (frontend + backend)
- Navigation intuitive et auto-suffisante
- États vides gérés (“No tasks yet”)
- Rafraîchissement explicite via `RefreshButton`

##### Choix simples, assumés et robustes

- Stack : Go + Next.js App Router, monorepo simple
- Architecture minimale : 3 pages, 3 endpoints
- Hors scope explicitement documenté (auth, pagination, filtres)
- État local uniquement (pas de store global)
- Contrat API standardisé `{ data, meta } / { error, meta }`
- Aucune complexité prématurée (pas de cache avancé, pas d’optimistic update)

---

#### Bloquants

Aucun. La quête est validée sans réserve.

---

#### Améliorations optionnelles (non bloquantes)

- Accessibilité avancée (focus management, skip links)
- UX : confirmations, toasts, animations
- Robustesse : retry automatique, debounce validation
- Observabilité : logs frontend, métriques
- Performance : pagination, cache stratégique

> Ces améliorations sont volontairement hors scope Horizon 1.

---

#### Conclusion

La quête **MQ-02** est validée sur la base de preuves code concrètes et d’une documentation suffisante.  
Le produit atteint l’objectif _“autonomie produit minimale et fiable”_ défini pour l’Horizon 1.

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
