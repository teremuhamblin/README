# Projet : ShadowStrike

> **Catégorie :** Framework de laboratoire Red Team  
> **Statut :** 🟣 En développement  
> **Périmètre :** environnement isolé et explicitement autorisé

## Objectif

Étudier l’organisation de scénarios Red Team défensifs : chronologie, preuves, contrôles de sécurité, journalisation et restitution.

## Livrables envisagés

- [ ] Modèles de cadrage documentaire.
- [ ] Jeux de données synthétiques.
- [ ] Guides de validation dans un laboratoire isolé.
- [ ] Procédures de nettoyage et de conservation des preuves.
- [ ] Exemple de rapport expurgé orienté remédiation.

## Limites

Aucune procédure, configuration ou artefact publiés ici ne doit être utilisé hors d’un mandat écrit. Le projet ne constitue pas une autorisation d’accès à un système tiers.

---

# Projet : ZeroDay-Lab

> **Catégorie :** Recherche en laboratoire  
> **Statut :** 🧪 Recherche / expérimentation  
> **Périmètre :** applications, logiciels et matériels prévus à cet effet

## Objectif

Documenter des exercices de découverte et de validation de vulnérabilités sur des cibles dédiées à l’apprentissage.

## Axes

- Revue statique et dynamique.
- Compréhension des conditions nécessaires à un constat reproductible.
- Réduction des effets pendant les essais.
- Description des impacts et mesures correctives.
- Rédaction de rapports factuels sans données sensibles.

## Exclusions

Ce dépôt ne publie pas de payload opérant, de méthode d’exploitation applicable à une cible réelle ni de données permettant d’identifier une victime.

---

# Projet : CTF-Mastermind

> **Catégorie :** Formation offensive défensive  
> **Statut :** 🔄 En cours  
> **Périmètre :** environnements de compétition ou machines locales

## Objectif

Concevoir des défis pédagogiques, une progression par niveaux et des corrigés axés sur les principes de sécurité.

## Livrables envisagés

- Énoncés anonymisés.
- Architectures de machines isolées.
- Indications graduelles.
- Solutions explicatives orientées compréhension et remédiation.
- Tests de reproductibilité.

## Critères de qualité

- Aucun accès à un réseau tiers requis.
- Aucun secret réel embarqué.
- Objectifs pédagogiques clairement identifiés.
- Correction vérifiable en environnement local.

---

# Projet : ReconX

> **Catégorie :** Automatisation  
> **Statut :** 🟡 Prototype  
> **Périmètre :** actifs explicitement autorisés

## Objectif

Centraliser des contrôles d’inventaire sûrs, des validations documentées et une restitution lisible pour les équipes concernées.

## Principes

- Prévenir toute collecte excessive.
- Exiger une liste d’actifs autorisés.
- Conserver les journaux minimaux nécessaires.
- Séparer les données brutes des synthèses publiées.
- Fournir une traçabilité des décisions et paramètres.

## Résultats attendus

- Inventaire vérifié.
- Liste des contrôles exécutés.
- Erreurs et limites documentées.
- Synthèse destinée à la remédiation.

---

# Projet : SmartContract-Sentinel

> **Catégorie :** Audit blockchain  
> **Statut :** 🔵 En évolution  
> **Périmètre :** code source, contrats de laboratoire ou audits mandatés

## Objectif

Organiser une revue méthodique des contrats intelligents et produire des recommandations vérifiables.

## Axes possibles

- Contrôles d’accès.
- Gestion des erreurs et des états.
- Opérations arithmétiques.
- Séparation des responsabilités.
- Compatibilité des appels externes.
- Vérifications de tests et de déploiement.

## Forme de restitution

Chaque constat doit distinguer : gravité estimée, contexte, reproduction contrôlée, risque, mesure correcte et validation de la correction.

> Aucun contrat réel ne doit être publié avec des clés, fonds, données privées ou mécanismes exploitables hors d’un mandat adapté.

---

# Fiche commune de projet

Utiliser cette structure pour ajouter un projet :

```markdown
# Nom du projet

> **Catégorie :** ...
> **Statut :** ...
> **Périmètre :** ...

## Objectif

## Livrables

## Validation

## Limites

## Références publiques

## Statut de divulgation
```
