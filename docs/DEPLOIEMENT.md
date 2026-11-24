# Déploiement du portfolio

> **Version :** 1.3  
> **Page publiée :** [https://teremuhamblin.github.io/TheMadDoG.tmdg/](https://teremuhamblin.github.io/TheMadDoG.tmdg/)  
> **Page principale :** [`../index.html`](../index.html)

## GitHub Pages

Le dépôt utilise une page statique à la racine. Pour vérifier ou configurer sa publication :

1. Ouvrir **Settings → Pages** dans le dépôt.
2. Sélectionner **GitHub Actions** comme source de déploiement.
3. Vérifier que `.github/workflows/pages.yml` est présent sur la branche `main`.
4. Conserver `main` comme branche contenant le contenu publié.
5. Attendre la fin du workflow **Deploy portfolio to GitHub Pages**.
6. Ouvrir l’URL publique et contrôler les liens, le rendu mobile et les thèmes.
7. Activer HTTPS lorsque GitHub Pages le propose.

En cas d’utilisation d’un domaine personnalisé, remplacer l’URL publique dans le README, `index.html`, les documents et les annonces du dépôt sans conserver d’ancienne destination.

## Déploiement automatique

Le workflow prévu upload l’intégralité du dépôt comme contenu statique puis publie l’artefact via GitHub Pages. Il ne contient aucune étape de compilation : `index.html` doit donc rester à la racine.

Toute modification effectuée sur `main` peut déclencher un nouveau déploiement. Les changements importants doivent passer par une pull request afin de conserver une revue vérifiable.

## Vérifications avant publication

- `index.html` est présent à la racine.
- Les liens vers les sections `synthese`, `identite`, `cycle`, `arsenal`, `operations`, `validation` et `communications` fonctionnent.
- Les ancres du README correspondent aux identifiants HTML réels.
- Les URLs publiques utilisent la même adresse GitHub Pages.
- Les boutons, liens externes et ressources ont une destination réelle.
- Le navigation clavier fonctionne sur écran étroit et écran large.
- Les thèmes clair/sombre et la réduction des animations sont testés.
- Aucun secret, jeton, mot de passe, donnée personnelle ou contenu confidentiel n’est publié.
- Le README, `index.html` et les fiches projets restent cohérents.

## Dépannage

| Symptôme | Vérification |
|:--|:--|
| Page non publiée | Vérifier les paramètres Pages, le workflow et l’état du dernier déploiement. |
| Ancienne version visible | Attendre la fin du workflow, vider le cache et vérifier le commit publié. |
| Erreur 404 | Vérifier que `index.html` existe à la racine et que Pages pointe vers la bonne source. |
| Lien d’ancre inactif | Comparer le `href` avec l’`id` exact de la section HTML. |
| Apparence différente | Tester les préférences système, le thème mémorisé et la largeur d’écran. |
| Problème JavaScript | Vérifier la console et conserver un contenu essentiel utilisable sans JavaScript. |
