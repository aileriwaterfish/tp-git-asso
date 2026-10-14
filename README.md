# tp-git-asso

Site web statique (HTML/CSS) pour l'association fictive « Les Codeurs », réalisé pour un TP Git en binôme (branches, conflits, rebase, revert, étiquettes, pull requests).

## Prérequis
- Un navigateur web récent
- Git
- Un éditeur de code (par exemple Visual Studio Code)

Aucune dépendance : pas de Node.js ni de base de données.

## Installation
```bash
git clone https://github.com/aileriwaterfish/tp-git-asso.git
cd tp-git-asso
code .
```

## Lancement
Ouvrir `index.html` dans un navigateur (double-clic). Il n'y a pas de serveur à démarrer.

## Structure
```text
tp-git-asso/
├── index.html   # structure et contenu de la page
├── style.css    # mise en forme
├── .gitignore   # fichiers ignorés par Git
└── README.md    # ce fichier
```

## Contribution
1. `git switch main && git pull`
2. `git switch -c feature/ma-branche`
3. Commits clairs, puis `git push -u origin feature/ma-branche`
4. Ouvrir une pull request vers `main`
