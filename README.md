# Modules de formation

Ce dépôt contient une collection de modules de formation structurés.

## Structure

Chaque dossier représente un module distinct de formation:
```
ModuleX/
├── src/            # Sources MARP
│   ├── slides.md
│   └── assets/     # Images et autres ressources
└── slides.pdf      # Exports PDF du cours
```

## Utilisation

Les présentations sont créées avec [MARP](https://marp.app/), un outil permettant de créer des diapositives à partir de fichiers Markdown.

### Pour consulter les formations:
- Naviguez simplement vers le dossier du module souhaité
- Consultez les fichiers PDF dans le dossier racine du module

### Pour modifier les formations:
1. Installez MARP CLI: `npm install -g @marp-team/marp-cli`
2. Modifiez les fichiers source dans le dossier `src/` du module concerné
3. Générez un nouveau PDF: `marp --pdf src/slides.md -o export/slides.pdf`

## Licence

© 2025 Clément AMELINE

Ce projet est sous licence [GPL-3.0](LICENSE.md). Toute utilisation, modification ou distribution doit mentionner l'auteur original.
