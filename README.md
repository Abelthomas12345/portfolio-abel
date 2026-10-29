# CV en ligne – Ndoungue Essoh Abel Thomas

Site statique (HTML + CSS, sans JavaScript, sans dépendance). Il se publie tel quel sur GitHub Pages.

## Structure

```
index.html          Accueil : présentation, compétences, formation
experiences.html    Expériences (stages) et projets
hobbies.html        Loisirs
css/style.css       Toute la mise en forme (voir le sommaire en haut du fichier)
img/profil.jpg      Photo de profil (480 x 600 px)
img/favicon.svg     Icône de l'onglet
doc/                CV au format PDF
```

## Modifier le contenu

| Je veux…                         | Où                                                              |
|----------------------------------|-----------------------------------------------------------------|
| Changer une couleur ou la police | `css/style.css`, section 1 « Variables »                        |
| Ajouter un projet                | `experiences.html` : copier un bloc `<article class="fiche fiche--simple">` |
| Ajouter une compétence           | `index.html` : modifier la ligne `<dd>` de la catégorie         |
| Ajouter une formation            | `index.html` : copier un bloc `<article class="fiche">`         |
| Changer mes coordonnées          | Pied de page, identique dans les 3 fichiers HTML                |
| Remplacer le CV                  | Remplacer le PDF dans `doc/` en gardant le même nom             |

L'en-tête et le pied de page sont répétés dans chaque page : en cas de modification, la refaire dans les 3 fichiers.

## À compléter avant de rendre le projet

- [ ] Remplacer les liens « Voir le code sur GitHub » par l'adresse exacte de chaque dépôt (`experiences.html`)
- [ ] Ajouter ton profil LinkedIn dans le pied de page (modèle déjà en commentaire)
- [ ] Relire et personnaliser les textes de `hobbies.html`
- [ ] Ajouter la lettre de recommandation dans `doc/` et un lien vers elle si nécessaire
- [ ] Remplacer la photo par un portrait de face sur fond neutre si possible

## Publier sur GitHub Pages

1. Copier le contenu de ce dossier à la racine du dépôt (remplacer les anciens fichiers, supprimer l'ancien `style.css` et le dossier `img/` d'origine).
2. `git add . && git commit -m "Refonte du CV en ligne" && git push`
3. Dans le dépôt : Settings, Pages, Branch `main` (ou `master`), dossier `/ (root)`.
