# Documentation du dépôt

> **Version :** 1.3  
> **Rôle :** guide de lecture, de contribution et de publication du portfolio TheMadDoG.tmdg.

## Objectif

Le dépôt contient une page web statique autonome (`index.html`), un README de présentation, des illustrations vectorielles et une documentation Markdown. Le site constitue la source visuelle principale ; le README en constitue l’entrée accessible et synthétique.

## Navigation

- [`../index.html`](../index.html) — page web principale.
- [`../README.md`](../README.md) — présentation et registre textuel.
- [`ARCHITECTURE.md`](ARCHITECTURE.md) — structure et fonctionnalités.
- [`DEPLOIEMENT.md`](DEPLOIEMENT.md) — publication GitHub Pages.
- [`PROJETS.md`](PROJETS.md) — fiches des projets.
- [`SECURITE.md`](SECURITE.md) — confidentialité et divulgation responsable.
- [`CHARTE_VISUELLE.md`](CHARTE_VISUELLE.md) — palette et usages des visuels.
- [`ROADMAP.md`](ROADMAP.md) — pistes d’évolution.
- [`../CONTRIBUTING.md`](../CONTRIBUTING.md) — guide de contribution.
- [`../structure.md`](../structure.md) — arborescence du dépôt.

## Principes de publication

1. **Autorisation et contexte :** décrire les exercices comme des travaux sur des environnements détenus, dédiés ou explicitement autorisés.
2. **Données minimales :** ne jamais publier de secrets, identifiants, données personnelles, journaux bruts ou informations confidentielles.
3. **Références vérifiables :** ajouter des liens publics uniquement lorsqu’ils sont autorisés et qu’ils étayent directement une affirmation.
4. **Précision :** distinguer les projets en cours des résultats confirmés ; ne pas transformer un axe de pratique en réalisation vérifiée.
5. **Orientation défensive :** privilégier les constats synthétiques, les limites, les mesures correctives et les effets sur la sécurité.
6. **Divulgation responsable :** coordonner toute vulnérabilité avec les parties concernées et respecter les règles applicables.

## Mettre à jour le portfolio

- Synchroniser les ancres du README avec les `id` de section de `index.html`.
- Mettre à jour simultanément les statuts du site, du README et des fiches projets.
- Vérifier tous les liens d’action du site et supprimer les anciennes destinations.
- Vérifier le rendu mobile, clavier, les thèmes et la réduction des animations.
- Utiliser des exemples synthétiques ; ne pas intégrer de données réelles de client ou de cible.
- Mettre à jour [`STRUCTURE.md`](STRUCTURE.md) lors de toute évolution de l’arborescence.

## Contribuer

Les corrections de contenu, d’accessibilité et de documentation peuvent être proposées par pull request. Les signalements sensibles doivent suivre [`SECURITE.md`](SECURITE.md) et ne doivent pas contenir de preuve active ou de données confidentielles.

## Vérification avant publication

- [ ] Aucun secret, jeton, mot de passe ou donnée personnelle n’est présent.
- [ ] Les affirmations et références sont exactes et autorisées.
- [ ] Les statuts du site, du README et des fiches projets sont cohérents.
- [ ] Les liens, ancres et boutons du site ont des destinations réelles.
- [ ] Le site reste lisible sur mobile et utilisable au clavier.
- [ ] Le Markdown, le HTML et les blocs Mermaid sont correctement formés.
- [ ] Les informations sensibles ont été expurgées conformément à [`SECURITE.md`](SECURITE.md).
