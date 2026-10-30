# CV en ligne – Ndoungue Essoh Abel Thomas

CV interactif présenté sous forme de site web statique, réalisé en HTML et CSS. Le site ne nécessite ni JavaScript ni dépendance externe et peut être publié directement avec GitHub Pages.

## Aperçu du projet

Le site présente le profil professionnel, les compétences, la formation, les expériences, les projets et les loisirs d'Abel Thomas.

## Pages du site

| Page | Contenu |
| :--- | :--- |
| `index.html` | Présentation, compétences et formation |
| `experiences.html` | Expériences professionnelles, stages et projets |
| `hobbies.html` | Loisirs et centres d'intérêt |

## Structure du projet

```text
.
├── index.html
├── experiences.html
├── hobbies.html
├── css/
│   └── style.css
├── img/
│   ├── profil.jpg
│   └── favicon.svg
└── doc/
    └── CV au format PDF
```

## Technologies utilisées

- HTML5
- CSS3
- GitHub Pages

## Modifier le contenu

| Élément à modifier | Emplacement |
| :--- | :--- |
| Couleurs ou police | `css/style.css`, section « Variables » |
| Nouveau projet | Ajouter une fiche dans `experiences.html` |
| Nouvelle compétence | Modifier une catégorie `<dd>` dans `index.html` |
| Nouvelle formation | Ajouter une fiche `<article>` dans `index.html` |
| Coordonnées | Pied de page commun aux trois pages HTML |
| CV téléchargeable | Remplacer le PDF dans le dossier `doc/` |

L'en-tête et le pied de page sont répétés dans les trois fichiers HTML. Toute modification globale doit donc être appliquée sur chaque page.

## Liste des améliorations à finaliser

- [ ] Ajouter des photos illustratives pour les projets
- [ ] Remplacer la photo actuelle par un portrait de face sur fond neutre

## Publication sur GitHub Pages

1. Versionner et publier les modifications :

   ```bash
   git add .
   git commit -m "Refonte du CV en ligne"
   git push
   ```

2. Ouvrir les paramètres du dépôt sur GitHub.
3. Accéder à **Settings > Pages**.
4. Choisir la branche `main` ou `master` dans le menu **Branch**.
5. Sélectionner le dossier `/ (root)` puis enregistrer.
