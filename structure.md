# Structure du dépôt — v1.0

> **État :** structure documentaire initiale.  
> **Date :** 2026-11-24.

## Arborescence actuelle

```text
.
├── README.md          # Portfolio principal : présentation, domaines, méthode et projets
├── structure.md       # Structure v1.0 et propositions d’évolution
└── docs/
    └── README.md      # Conventions de documentation, sécurité et contribution
```

## Rôle des fichiers

| Chemin | Responsabilité |
|:--|:--|
| `README.md` | Page d’accueil du portfolio. Contient le sommaire, les principes, la méthode Mermaid, les domaines, les projets et les règles de collaboration. |
| `docs/README.md` | Guide de publication et de contribution. Rappelle les règles de confidentialité et de divulgation responsable. |
| `structure.md` | Référence de l’arborescence actuelle et point de départ pour les versions futures. |

## Conventions

- Rédiger en français, avec des termes techniques cohérents et des titres explicites.
- Garder le README concis à parcourir : sommaire, tableaux et légendes doivent aider à trouver l’information.
- Utiliser Mermaid pour expliquer un processus ou une relation, pas pour détailler une procédure d’intrusion.
- N’ajouter un lien de projet ou de réalisation qu’après vérification de sa destination et de son autorisation de publication.
- Ne pas committer de secrets, d’identifiants, de données personnelles ou de contenu confidentiel.
- Distinguer clairement les projets proposés, en cours et terminés.

## Évolution envisagée

Cette arborescence est volontairement minimale pour `v1.0`. Si le portfolio s’étoffe, une évolution possible — à confirmer selon les besoins — serait :

```text
.
├── README.md
├── structure.md
├── docs/
│   ├── README.md
│   ├── projets.md          # Index de projets avec liens publics vérifiés
│   └── securite.md         # Politique de publication et signalement
└── assets/
    └── images/             # Visuels créés pour le portfolio, sans contenu sensible
```

Les fichiers proposés dans cette évolution ne sont pas encore créés. Ajouter uniquement ceux qui ont un contenu maintenu et utile.

## Historique

| Version | Changement |
|:--|:--|
| `1.0` | Création du portfolio principal, du guide documentaire et de la structure initiale. |
