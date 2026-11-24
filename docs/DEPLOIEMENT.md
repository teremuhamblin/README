# Déploiement du portfolio

> Le dépôt contient une page statique à la racine : `index.html`.

## GitHub Pages

Le site public du projet est : [https://teremuhamblin.github.io/README/](https://teremuhamblin.github.io/README/).

Pour vérifier ou configurer sa publication dans GitHub :

1. Ouvrir **Settings → Pages** dans le dépôt.
2. Vérifier la source de publication configurée par les administrateurs du dépôt.
3. Si la publication depuis une branche est utilisée, choisir `main` et le dossier `/ (root)`.
4. Enregistrer et attendre la fin du déploiement Pages.
5. Ouvrir l’URL publique et contrôler les liens, l’affichage mobile et les deux thèmes.

Les noms exacts des options disponibles peuvent varier selon la configuration de publication du dépôt. Ne pas ajouter de workflow de déploiement tant qu’un besoin spécifique n’est pas établi.

## Vérifications avant publication

- La page d’accueil servie correspond bien au fichier `index.html` à la racine.
- Les liens de navigation vers les identifiants `synthese`, `identite`, `cycle`, `arsenal`, `operations`, `validation` et `communications` fonctionnent.
- Les liens vers le dépôt et les ressources documentaires ne contiennent pas de valeurs de remplacement.
- La navigation est utilisable au clavier et sur écran étroit.
- Le thème clair, le thème sombre et la préférence de réduction des animations sont testés.
- Aucune information confidentielle, donnée personnelle ou clé n’est publiée.
- Le contenu de `README.md` reste cohérent avec le site.

## Dépannage

| Symptôme | Vérification |
|:--|:--|
| Page non publiée | Vérifier les paramètres Pages, la branche source et l’état du dernier déploiement. |
| Ancien rendu | Recharger sans cache et vérifier le commit servi par Pages. |
| Lien d’ancre inactif | Comparer le `href` du lien avec l’`id` de la section correspondante. |
| Apparence différente | Tester les préférences système, le thème mémorisé et la largeur d’écran. |
| Un contrôle ne fonctionne pas | Vérifier la console du navigateur et prévoir un comportement de repli sans JavaScript. |
