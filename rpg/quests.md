# RPG — Quêtes

Ce document liste les quêtes actives du système RPG.  
Il ne définit pas les objectifs : il référence et structure ceux issus de `roadmap.md` et `side-quests.md`.

---

## Main Quests

### MQ-01 — Backend template prêt pour la production

- Standardiser la structure d’un service backend réutilisable
- Clarifier conventions d’API, gestion des erreurs et validation des entrées
- Éliminer les patterns fragiles récurrents

**Livrable attendu**

- Un dépôt backend prêt à être cloné pour un projet client

---

### MQ-02 — Produit full-stack minimal

- Construire une UI complète consommant une API backend
- Gérer formulaires, états de chargement et erreurs
- Assumer des choix simples et robustes

**Livrable attendu**

- Un produit full-stack fonctionnel, utilisable par un tiers

---

### MQ-03 — Service déployé et opéré

- Déployer un service en production
- Formaliser le processus de déploiement
- Comprendre et documenter les points de défaillance

**Livrable attendu**

- Un service accessible publiquement ou en environnement réel
- Une documentation de déploiement et d’exploitation

---

### MQ-04 — Découpage d’un forfait simple

- Définir le périmètre d’un projet fictif
- Identifier risques, zones floues et dépendances client
- Découper le projet en livrables vendables

**Livrable attendu**

- Un document de cadrage de forfait simple

---

### MQ-05 — Déploiement automatisé avec rollback

- Introduire Docker comme outil de reproductibilité
- Mettre en place un déploiement automatisé simple
- Être capable de rollback rapidement

**Livrable attendu**

- Un pipeline de déploiement automatisé documenté

---

## Side Quests

### SQ-01 — Exploration Docker

- Comprendre les bases de Docker et Docker Compose
- Tester sans imposer en production

**Livrable attendu**

- Un projet de test documenté

---

### SQ-02 — Intégration IA simple

- Intégrer une brique IA dans un produit existant
- Identifier coûts, limites et valeur réelle

**Livrable attendu**

- Une fonctionnalité IA fonctionnelle ou un POC documenté

---

### SQ-03 — Concepts systèmes ciblés

- Explorer un concept système précis (IO, mémoire, concurrence, etc.)
- Appliquer à un cas concret

**Livrable attendu**

- Une note technique liée à un cas réel

---

## Règles de validation

- Toute quête doit produire un livrable identifiable
- Toute validation doit être enregistrée dans `log.md`
- L’impact sur les statistiques doit être explicite et justifié
- Une quête non livrée est considérée comme non accomplie
