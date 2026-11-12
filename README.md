# Portfolio — Samir Gueblaoui

Portfolio en français, en HTML et CSS, sans dépendance. Thème sombre : fond presque noir, surfaces anthracite et typographie système, adaptée à macOS/iOS et aux autres appareils.

## Ouvrir le site

Ouvrir `index.html` dans un navigateur. Tous les fichiers et liens internes fonctionnent directement en local.

Pour utiliser un serveur local depuis ce dossier :

```sh
python3 -m http.server 8000 --bind 127.0.0.1
```

Puis ouvrir http://127.0.0.1:8000.

## Modifier le contenu

- `index.html` : textes, projets, liens, schéma SVG et coordonnées.
- `style.css` : couleurs, typographie, mise en page et adaptations mobile.
- `cv_samir.pdf` : CV proposé par les deux boutons du site ; remplacer ce PDF pour actualiser le document téléchargé.
- `favicon.svg` : icône de l'onglet.

Le dessin expression → AST → MPI illustre le principe du projet ; il ne représente ni un résultat de benchmark ni une capture du compilateur.
Le contenu reprend `cv_samir.pdf` : expériences LACL, Crédit Agricole CIB et Kepler Cheuvreux ; projets CatOpt (en cours), Merton-Jump et Heston ; compétences et formations. Le M2 LMFI est présenté avec la mention « stage validé en 2026 », sans affirmer que le diplôme est obtenu.

Les détails du projet LACL s'ouvrent avec « Mes contributions », sans JavaScript.

## Publication sur GitHub Pages

Placer `index.html`, `style.css`, `favicon.svg`, `.nojekyll`, `cv_samir.pdf` à la racine du dépôt `samirgueblaoui.github.io`.
Dans Settings → Pages : Deploy from a branch → main → / (root) → Save.

Aucun domaine personnalisé n'est configuré. Le site utilise des polices système et ne dépend d'aucune ressource distante pour s'afficher. Les liens GitHub et email fonctionnent par navigation.

## Évolution

Ajouter un lien LinkedIn quand l'adresse du profil est confirmée. Une future étude de cas de parallélisation pourra présenter des mesures réelles et leur protocole. Aucun résultat de performance n'a été inventé.

