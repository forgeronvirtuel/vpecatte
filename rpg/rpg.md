# RPG — Règles de progression

## Objectif du système

Ce système de type RPG sert à **mesurer et piloter une progression réelle**, basée exclusivement sur des livrables concrets, en cohérence avec :

- `skills.md`
- `roadmap.md`
- `side-quests.md`

Il ne définit pas les objectifs.  
Il ne remplace aucun document.  
Il sert uniquement à **rendre la progression explicite et traçable**.

## Principe fondamental

> **Aucune progression n’est accordée sans livrable vérifiable.**

Lecture, veille, réflexion ou expérimentation sans résultat exploitable ne donnent lieu à aucune progression.

## Structure du système

### Niveau (Level)

Le niveau représente l’**étendue du champ d’action réel**, pas un statut.

- Il augmente uniquement après validation de quêtes majeures.
- Il n’a pas de plafond prédéfini.

### Statistiques

Le système repose sur **5 statistiques maximum** :

- **Engineering**  
  Qualité du code, architecture, robustesse technique.

- **Delivery**  
  Capacité à livrer dans un cadre réel (délais, contraintes, périmètre).

- **Autonomy**  
  Capacité à travailler sans dépendance critique (technique ou organisationnelle).

- **Product Sense**  
  Capacité à faire des choix orientés usage, valeur et impact.

- **Leverage**  
  Capacité à réutiliser, automatiser et réduire le coût marginal.

Les statistiques sont des **entiers**.  
Aucune progression fractionnaire n’est autorisée.

## Quêtes

### Quêtes principales (Main Quests)

- Issues directement de `roadmap.md`
- Structurantes pour la progression
- Liées à un livrable significatif

Validation requise pour :

- montée de niveau
- progression majeure des statistiques

### Quêtes secondaires (Side Quests)

- Issues de `side-quests.md`
- Non bloquantes
- Bornées dans le temps

Elles peuvent améliorer une statistique de manière limitée, sans impact majeur sur le niveau.

## Validation d’une quête

Une quête est considérée comme validée uniquement si :

1. Un livrable existe (code, service, document, outil, etc.)
2. Le livrable est référencé dans `log.md`
3. L’impact sur les statistiques est explicitement justifié

Sans ces trois éléments, la quête est invalide.

## Attribution de la progression

- Toute progression doit être :
  - rare
  - justifiée
  - traçable
- Il est volontairement difficile de monter rapidement.

Si une progression paraît “facile”, c’est que les règles sont mal appliquées.

## Anti-règles

- Pas d’XP basée sur le temps passé
- Pas de progression automatique
- Pas de récompense pour la simple intention
- Pas d’optimisation du système au détriment de la livraison

## Révision du système

- Les règles peuvent être ajustées avec du recul
- Toute modification doit simplifier le système, jamais l’alourdir
- Le système doit rester compréhensible en une lecture rapide

## Rappel

Le RPG est un **outil de discipline**, pas de gratification.  
S’il cesse d’aider à **build, livrer et vendre**, il doit être simplifié ou abandonné.
