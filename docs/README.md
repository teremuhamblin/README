# Documentation du dépôt

> **Version :** 1.3  
> **Rôle :** guide de contribution et de publication du portfolio TheMadDoG.tmdg.

## Objectif

Le dépôt contient une page web statique (`index.html`), un README de présentation, des illustrations et une documentation de projet. Le site constitue la présentation visuelle ; le README en donne une synthèse navigable et documentée.

## Navigation

- [`../index.html`](../index.html) — page web principale.
- [`../README.md`](../README.md) — présentation et navigation textuelle.
- [`ARCHITECTURE.md`](ARCHITECTURE.md) — structure et fonctionnalités du site.
- [`DEPLOIEMENT.md`](DEPLOIEMENT.md) — publication GitHub Pages.
- [`PROJETS.md`](PROJETS.md) — fiches détaillées des projets.
- [`SECURITE.md`](SECURITE.md) — confidentialité et divulgation responsable.
- [`CHARTE_VISUELLE.md`](CHARTE_VISUELLE.md) — palette et usages des visuels.
- [`ROADMAP.md`](ROADMAP.md) — pistes d’évolution.
- [`../CONTRIBUTING.md`](../CONTRIBUTING.md) — guide de contribution.
- [`../structure.md`](../structure.md) — arborescence du dépôt.

## Principes de publication

1. **Autorisation et contexte :** décrire les exercices comme des travaux sur des environnements détenus, de laboratoire ou explicitement autorisés.
2. **Pas de données sensibles :** ne jamais publier de secrets, d’identifiants, de données personnelles, de journaux bruts ou d’informations confidentielles sur une cible.
3. **Références vérifiables :** ajouter des liens publics uniquement lorsque la publication est autorisée et qu’ils étayent directement l’affirmation.
4. **Précision :** distinguer les projets en cours des projets achevés ; présenter les compétences comme des axes de pratique sauf preuve à l’appui.
5. **Orientation défensive :** privilégier les constats synthétiques, les limites, les mesures correctives et l’impact sur la sécurité.
6. **Divulgation responsable :** coordonner toute publication de vulnérabilité avec les parties concernées et respecter les délais et règles applicables.

## Mettre à jour le portfolio

- Garder les ancres du README synchronisées avec les `id` de section de `index.html`.
- Mettre à jour en même temps les statuts dans le site, le README et les fiches projets.
- Vérifier tous les liens d’action du site : retirer les URL de remplacement et corriger les destinations invalides.
- Vérifier le rendu mobile, clavier, les préférences de thème et de mouvement réduit.
- Utiliser des exemples synthétiques ; ne pas embarquer de données réelles de client ou de cible.
- Mettre à jour [`../structure.md`](../structure.md) lors de l’ajout d’un fichier ou dossier.

## Contribuer

Les corrections de forme, d’accessibilité et de documentation peuvent être proposées par pull request. Pour signaler une vulnérabilité dans un projet réel ou partager des informations confidentielles, ne pas utiliser une issue ou une pull request publique : contacter d’abord l’organisation concernée par son canal officiel.

## Vérification avant publication

- [ ] Aucun secret, jeton, mot de passe ou donnée personnelle n’est présent.
- [ ] Les affirmations et références sont exactes et autorisées à la publication.
- [ ] Le statut du site, du README et des fiches projets est cohérent.
- [ ] Les liens, ancres et boutons du site ont des destinations réelles.
- [ ] Le site reste lisible sur mobile et utilisable au clavier.
- [ ] Le Markdown, le HTML et les blocs Mermaid sont correctement formés.
- [ ] Les informations sensibles ont été expurgées conformément à [`SECURITE.md`](SECURITE.md).
