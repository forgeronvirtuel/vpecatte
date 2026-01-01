# Skills Roadmap — Product-Oriented Full-Stack Engineer

## Objectif du document

Ce document décrit les capacités techniques et transverses nécessaires
pour **concevoir, construire, déployer et maintenir seul un produit logiciel**
dans un cadre professionnel rentable (missions au forfait, produits propres).

Ce n’est ni un CV, ni une liste exhaustive de technologies.
C’est une **cartographie de responsabilités et de maîtrise**.

## Niveaux de maîtrise (référentiel interne)

- **Fondations** : je comprends, je sais exécuter avec support
- **Autonomie** : je livre seul en production
- **Maîtrise** : je fais des choix, j’anticipe les problèmes
- **Expertise pragmatique** : je simplifie, j’optimise, je transmets

## 1. Architecture & Conception Produit (cœur)

### Fondations

- Comprendre un besoin métier et le traduire en fonctionnalités concrètes
- Identifier le périmètre minimal livrable (MVP réel, pas théorique)
- Séparer clairement domaine métier, infrastructure et interfaces

### Autonomie

- Concevoir une architecture simple, maintenable, évolutive
- Justifier chaque choix technique par un coût / bénéfice
- Refuser la complexité prématurée

### Maîtrise

- Anticiper la dette technique et la rendre explicite
- Concevoir pour l’évolution sans sur-ingénierie
- Savoir dire non à une feature mal définie

## 2. Backend Engineering (socle principal)

### Fondations

- APIs HTTP robustes (validation, erreurs, statuts)
- Modélisation de données cohérente
- Gestion correcte des états et transactions

### Autonomie

- Écrire des services backend prêts pour la production
- Sécuriser les accès (auth, permissions, secrets)
- Gérer les migrations et la compatibilité

### Maîtrise

- Optimiser les performances réelles (pas micro-optimisation)
- Diagnostiquer bugs et comportements non déterministes
- Concevoir des backends observables et auditables

## 3. Bases de données & Persistance

### Fondations

- Modélisation relationnelle correcte
- Compréhension des index et contraintes
- Requêtes lisibles et prévisibles

### Autonomie

- Choisir une stratégie de stockage adaptée au produit
- Gérer la montée en charge raisonnable
- Sauvegardes, restaurations, migrations maîtrisées

### Maîtrise

- Arbitrer entre performance, cohérence et simplicité
- Identifier les vrais goulots d’étranglement
- Prévenir les corruptions et pertes de données

## 4. Frontend (objectif : autonomie produit)

### Fondations

- Comprendre le fonctionnement du navigateur
- HTML sémantique, CSS lisible, JS maîtrisé
- Consommer proprement une API

### Autonomie

- Construire une interface complète utilisable par des clients
- Gérer les états, erreurs, chargements
- Maintenir une base front sans dette explosive

### Maîtrise

- Simplifier l’UX sans framework magique
- Faire des choix UI orientés efficacité utilisateur
- Intégrer le front comme partie du produit, pas comme couche décorative

## 5. Infrastructure & Déploiement (outil, pas finalité)

### Fondations

- Comprendre le cycle de vie d’une application en production
- Déployer manuellement un service fonctionnel
- Gérer les variables d’environnement et secrets

### Autonomie

- Automatiser le déploiement (CI simple, scripts fiables)
- Mettre en place Docker comme outil de reproductibilité
- Comprendre les bases du réseau, du DNS, du TLS

### Maîtrise

- Déployer sans interruption de service
- Diagnostiquer incidents de production
- Choisir la solution la plus simple qui fonctionne

## 6. Qualité, Fiabilité & Maintenance

### Fondations

- Tests unitaires utiles (pas décoratifs)
- Logs exploitables
- Gestion des erreurs explicite

### Autonomie

- Mettre en place monitoring et alertes minimales
- Écrire du code maintenable par soi-même dans 6 mois
- Corriger rapidement en production sans panique

### Maîtrise

- Réduire le coût de maintenance dans le temps
- Savoir quand ne pas tester
- Construire des systèmes robustes par design

## 7. Delivery & Travail au Forfait (critique)

### Fondations

- Découper un projet en livrables concrets
- Estimer honnêtement ce que l’on sait faire
- Identifier les zones de risque

### Autonomie

- Vendre une solution, pas une techno
- Protéger son temps et son périmètre
- Documenter juste ce qu’il faut

### Maîtrise

- Anticiper les dérives de scope
- Transformer un besoin flou en contrat clair
- Livrer sans s’épuiser

## 8. IA & Sujets Avancés (side quests structurées)

> Ces compétences **ne sont jamais prioritaires sur la capacité à livrer**.

### Fondations

- Comprendre les concepts clés (ML, DL, LLM, entraînement, inférence)
- Utiliser l’IA comme outil d’accélération, pas comme fin

### Autonomie

- Intégrer une brique IA simple dans un produit
- Comprendre les limites, coûts et risques

### Maîtrise (long terme)

- Choisir quand l’IA est réellement pertinente
- Éviter le solutionnisme technologique
- Rester pragmatique face au hype cycle

## Philosophie générale

- La valeur vient de ce qui est **livré**, pas de ce qui est connu
- La simplicité est une compétence avancée
- Chaque choix technique est un pari économique
- L’objectif final est l’autonomie, pas l’expertise isolée

## Utilisation recommandée

- Révision mensuelle rapide
- Mise à jour après chaque projet significatif
- Versionnement assumé (ce document évolue)
