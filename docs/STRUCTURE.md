# Structure du dépôt — v1.3

> **État :** page web statique et documentation alignée.  
> **Dernière mise à jour :** 2026-11-24.

## Arborescence

```text
.
├── index.html                 # Site portfolio autonome (HTML, CSS et JavaScript intégrés)
├── README.md                  # Présentation textuelle et navigation vers le site
├── CONTRIBUTING.md            # Règles de contribution
├── structure.md               # Arborescence et historique
├── assets/
│   └── brand/
│       ├── README.md          # Index des illustrations
│       ├── banner.svg         # Bannière originale
│       └── mark.svg           # Marque compacte
└── docs/
    ├── README.md              # Guide documentaire
    ├── ARCHITECTURE.md        # Architecture de index.html
    ├── CHARTE_VISUELLE.md     # Palette, typographie et usage des visuels
    ├── DEPLOIEMENT.md         # Publication GitHub Pages
    ├── PROJETS.md             # Fiches projets
    ├── ROADMAP.md             # Pistes d’évolution
    └── SECURITE.md            # Confidentialité et divulgation responsable
```

## Rôle des fichiers

| Chemin | Responsabilité |
|:--|:--|
| `index.html` | Interface web principale, autonome et statique. |
| `README.md` | Résumé textuel du site et liens vers les ressources. |
| `CONTRIBUTING.md` | Règles de contribution et vérifications. |
| `structure.md` | Arborescence et historique de version. |
| `assets/brand/` | Illustrations vectorielles du portfolio. |
| `docs/README.md` | Guide de documentation et publication. |
| `docs/ARCHITECTURE.md` | Fonctionnement et sections du site. |
| `docs/CHARTE_VISUELLE.md` | Palette du site et des illustrations, principes d’accessibilité. |
| `docs/DEPLOIEMENT.md` | Guide de publication sur GitHub Pages. |
| `docs/PROJETS.md` | Descriptions et limites des projets présentés. |
| `docs/ROADMAP.md` | Pistes d’amélioration. |
| `docs/SECURITE.md` | Politique de confidentialité et de divulgation. |

## Navigation

- [Portfolio web](https://teremuhamblin.github.io/README/)
- [Architecture](docs/ARCHITECTURE.md)
- [Déploiement](docs/DEPLOIEMENT.md)
- [Documentation](docs/README.md)
- [Contribution](CONTRIBUTING.md)

## Conventions de maintenance

- La page racine `index.html` est la source visuelle principale ; conserver le README comme résumé fidèle et accessible.
- Synchroniser les identifiants des sections, les statuts des projets et les liens entre site et documentation.
- Vérifier les liens de navigation et d’action après chaque changement.
- Respecter l’accessibilité, les préférences de thème et la réduction des animations.
- Ne pas committer de secrets, de données personnelles ou de contenus confidentiels.
- Distinguer les statuts déclaratifs des preuves publiques vérifiables.

## Historique

| Version | Changement |
|:--|:--|
| `1.0` | Portfolio principal, guide documentaire et structure initiale. |
| `1.1` | Ajout des fiches projets et de la politique de sécurité. |
| `1.2` | Ajout des illustrations de marque, charte visuelle, contribution et feuille de route. |
| `1.3` | Documentation alignée avec `index.html`, ajout de l’architecture et du déploiement, README refondu comme page d’entrée du site. |

### Construire une structure `.github`

Complète adaptée à ce README, avec templates d’issues/PR, workflows, configuration de communauté, sécurité, dépendabot et publication GitHub Pages. 

Je commencerais par vérifier les fichiers déjà présents pour éviter les conflits.Je vais créer une configuration cohérente avec le périmètre autorisé du README :
- Modèles d’issues/PR, contribution, politique sécurité, codeowners, dépendabot, labels et validation automatisée légère.
- D’abord je vérifie l’arborescence existante pour éviter d’écraser les réglages déjà présents.Je vais ajouter une structure `.github` légère et cohérente pour un portfolio HTML statique, sans automatiser des tests de sécurité sur du contenu non exécutable.
- érifie d’abord les conventions existantes, notamment `CONTRIBUTING.md` et les docs.Je vais construire une configuration `.github` adaptée au dépôt, en français, avec sécurité, contribution, traçabilité des PR et automatisations compatibles GitHub Pages.

Proposition du dossier :

```text
.github/
├── CODEOWNERS
├── FUNDING.yml
├── dependabot.yml
├── ISSUE_TEMPLATE/
│   ├── bug_report.yml
│   ├── documentation.yml
│   ├── feature_request.yml
│   ├── security.yml
│   └── config.yml
├── PULL_REQUEST_TEMPLATE/
│   └── pull_request_template.md
├── workflows/
│   ├── pages.yml
│   ├── quality.yml
│   └── dependency-review.yml
├── labeler.yml
└── labels.yml
```
