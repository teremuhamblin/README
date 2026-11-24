# Feuille de route

> Pistes d’évolution du portfolio, et non engagements de livraison. `index.html` est la page web principale ; les autres fichiers assurent sa documentation, son identité visuelle, son résumé accessible et sa maintenance GitHub.

## Priorités — cohérence et fiabilité

- [x] Page statique `index.html` à la racine.
- [x] Interface responsive avec thème clair/sombre.
- [x] Respect de la préférence de réduction des animations.
- [x] Navigation adaptée aux petits écrans.
- [x] Accessibilité de base : lien d’accès direct, navigation balisée et états de focus.
- [x] Documentation d’architecture, de déploiement et des projets.
- [x] Publication du guide de contribution.
- [x] Publication de la politique de sécurité et de divulgation responsable.
- [x] Documentation de la charte visuelle.
- [x] Création du dossier `.github` avec modèles d’issues et de pull requests.
- [x] Définition d’un workflow de vérification documentaire et d’analyse des secrets.
- [x] Définition d’un workflow de déploiement GitHub Pages.
- [ ] Vérifier et corriger toutes les URL de remplacement ou mal formées dans les appels à l’action.
- [ ] Harmoniser les URLs du README, de `index.html` et de GitHub Pages.
- [ ] Harmoniser les statuts du site, du `README.md` et des fiches projets.
- [ ] Étayer les affirmations externes avec des références publiques autorisées.
- [ ] Ajouter les identifiants GitHub Pages aux liens internes du README si nécessaire.

## Qualité et accessibilité

- [x] Prévoir une navigation clavier dans l’interface principale.
- [x] Prévoir des textes alternatifs pour les visuels informatifs.
- [x] Définir des états visuels distincts pour les interactions et le focus.
- [ ] Tester la navigation clavier sur toutes les pages et tous les composants.
- [ ] Tester le site avec plusieurs lecteurs d’écran.
- [ ] Vérifier les contrastes des thèmes clair et sombre.
- [ ] Vérifier le comportement du site avec zoom 200 % et 400 %.
- [ ] Contrôler le fonctionnement sans JavaScript.
- [ ] Contrôler le fonctionnement si le stockage local est indisponible.
- [ ] Vérifier les ancres et liens sur mobile et ordinateur.
- [ ] Vérifier l’ordre de lecture des éléments avec les technologies d’assistance.
- [ ] Ajouter des études de cas expurgées uniquement si leur publication est autorisée.

## Sécurité et divulgation

- [x] Définir les principes d’autorisation préalable et de périmètre borné.
- [x] Interdire la publication de secrets et données sensibles dans le dépôt.
- [x] Documenter les règles de divulgation responsable.
- [x] Ajouter un modèle GitHub pour les signalements de sécurité.
- [x] Ajouter une vérification automatisée des secrets courants dans les contributions.
- [ ] Activer les Dependabot alerts et les mises à jour de sécurité.
- [ ] Activer les protections contre les secrets dans les paramètres du dépôt.
- [ ] Configurer un ruleset obligatoire pour la branche `main`.
- [ ] Vérifier les résultats du workflow Pages avant activation définitive.
- [ ] Définir une procédure pour les données sensibles qui ne peuvent pas être publiées.

## GitHub Pages et automatisation

- [x] Définir une architecture autonome dans `index.html`.
- [x] Ajouter un workflow de publication GitHub Pages.
- [x] Ajouter un workflow de contrôle documentaire.
- [x] Ajouter un workflow de revue des dépendances.
- [x] Ajouter Dependabot pour les actions GitHub.
- [ ] Configurer `main` comme branche de publication dans GitHub Pages.
- [ ] Sélectionner **GitHub Actions** comme source de déploiement.
- [ ] Activer HTTPS sur GitHub Pages.
- [ ] Vérifier le domaine final du portfolio après déploiement.
- [ ] Ajouter une vérification des liens internes dans le workflow de qualité.
- [ ] Ajouter une vérification des ancres HTML dans le workflow de qualité.
- [ ] Ajouter une vérification Markdown et HTML lorsque des critères stables auront été définis.

## Contribution et maintenance

- [x] Rédiger les règles de contribution.
- [x] Ajouter un modèle de pull request.
- [x] Ajouter des modèles d’issues pour les bugs, propositions et signalements.
- [x] Ajouter des labels orientés documentation, accessibilité, sécurité et maintenance.
- [x] Définir des règles d’association automatique des modifications.
- [ ] Attribuer des mainteneurs supplémentaires uniquement si nécessaire.
- [ ] Maintenir la cohérence entre `structure.md`, le README et l’arborescence réelle.
- [ ] Relire les documents après chaque évolution structurante du portfolio.

## Améliorations futures

- [ ] Envisager l’extraction CSS/JavaScript seulement si cela simplifie réellement la maintenance.
- [ ] Ajouter des automatisations de vérification documentaire après définition de critères stables.
- [ ] Ajouter une traduction uniquement si elle peut être tenue à jour.
- [ ] Évaluer l’ajout d’aperçus automatisés pour les pull requests.
- [ ] Évaluer un test visuel automatisé léger pour les thèmes clair et sombre.
- [ ] Ajouter une archive expurgée de rapports ou validations seulement si elle respecte les règles de confidentialité.

## Règle de priorité

La sécurité, l’accès autorisé, l’accessibilité, la cohérence et la vérifiabilité passent avant les effets visuels. Ne jamais inventer des preuves ou publier des détails confidentiels pour remplir une section.
