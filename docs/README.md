# Documentation du dépôt

> **Version :** 1.1  
> **Rôle :** guide de contribution et de publication pour le portfolio TheMadDoG.tmdg.

## Objectif

Ce dépôt présente un portfolio professionnel de sécurité informatique. La documentation doit rendre les projets, leurs limites et leurs références compréhensibles, sans exposer de secrets ni fournir d’instructions destinées à compromettre des systèmes tiers.

## Navigation

- [`../README.md`](../README.md) — page d’accueil et portfolio.
- [`PROJETS.md`](PROJETS.md) — fiches détaillées des projets.
- [`SECURITE.md`](SECURITE.md) — confidentialité, contribution responsable et divulgation.
- [`../structure.md`](../structure.md) — arborescence du dépôt.

## Principes de publication

1. **Autorisation et contexte :** décrire les exercices comme des travaux sur des environnements détenus, de laboratoire ou explicitement autorisés.
2. **Pas de données sensibles :** ne jamais publier de secrets, d’identifiants, de données personnelles, de journaux bruts ou d’informations confidentielles sur une cible.
3. **Références vérifiables :** ajouter des liens publics uniquement lorsque la publication est autorisée et qu’ils étayent directement l’affirmation.
4. **Précision :** distinguer les projets en cours des projets achevés ; présenter les compétences comme des axes de pratique sauf preuve à l’appui.
5. **Orientation défensive :** privilégier les constats synthétiques, les limites, les mesures correctives et l’impact sur la sécurité.
6. **Divulgation responsable :** coordonner toute publication de vulnérabilité avec les parties concernées et respecter les délais et règles applicables.

## Mettre à jour le portfolio

- Garder le sommaire du README synchronisé avec les titres de section.
- Pour chaque nouveau projet, préciser sa finalité, son statut et son périmètre autorisé.
- Ajouter une référence ou une démonstration non sensible lorsque disponible.
- Vérifier les liens et le rendu des diagrammes Mermaid avant publication.
- Utiliser des exemples synthétiques ; ne pas embarquer de données réelles de client ou de cible.
- Mettre à jour [`structure.md`](../structure.md) lors de l’ajout d’un fichier ou dossier fonctionnel.

## Contribuer

Les corrections de forme et les améliorations documentaires peuvent être proposées par pull request. Pour signaler une vulnérabilité dans un projet réel ou partager des informations confidentielles, ne pas utiliser une issue ou une pull request publique : contacter d’abord l’organisation concernée par son canal officiel.

## Vérification avant publication

- [ ] Aucun secret, jeton, mot de passe ou donnée personnelle n’est présent.
- [ ] Les affirmations et références sont exactes et autorisées à la publication.
- [ ] Le statut des projets et les liens sont à jour.
- [ ] Le périmètre et les limites sont décrits sans divulguer de détails sensibles.
- [ ] Le Markdown et les blocs Mermaid sont correctement formés.
- [ ] Les informations sensibles ont été expurgées conformément à [`SECURITE.md`](SECURITE.md).
