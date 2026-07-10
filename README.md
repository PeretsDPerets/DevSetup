# DevSetup

> Mon premier environnement de développement Full Stack.

Ce dépôt a été réalisé dans le cadre de la **Phase 1 - Module 0** de la formation FullStack d'Akieni Academy.

L'objectif est de mettre en place un environnement de développement complet, apprendre les bases de Git et GitHub, ainsi que documenter les premières connaissances acquises.

---

# Objectifs

Ce projet permet de :

- Installer et configurer Visual Studio Code
- Installer Node.js
- Installer et configurer Git
- Créer un compte GitHub
- Comprendre les bases du Terminal
- Découvrir le fonctionnement d'un dépôt Git
- Réaliser ses premiers commits

---

# Structure du projet

```text
DevSetup/
│
├── notes/
│   ├── git.md
│   ├── terminal.md
│   └── vscode.md
│
├── .gitignore
├── .editorconfig
└── README.md
```

---

# Outils utilisés

| Outil | Description |
|--------|-------------|
| VS Code | Éditeur de code |
| Git | Gestionnaire de versions |
| GitHub | Hébergement du code |
| Node.js | Environnement JavaScript |
| Terminal | Interface en ligne de commande |

---

# Configuration

## Vérifier Node.js

```bash
node -v
```

## Vérifier npm

```bash
npm -v
```

## Vérifier Git

```bash
git --version
```

---

# Configuration Git

Configurer son identité Git :

```bash
git config --global user.name "Votre Nom"
git config --global user.email "votre@email.com"
```

Vérifier la configuration :

```bash
git config --list
```

---

# Initialiser un dépôt Git

Créer un dépôt :

```bash
git init
```

Ajouter les fichiers :

```bash
git add .
```

Créer un commit :

```bash
git commit -m "Initial commit"
```

Connecter GitHub :

```bash
git remote add origin URL_DU_REPO
```

Envoyer le projet :

```bash
git push -u origin main
```

---

# Contenu du dossier notes

Le dossier **notes** contient les premières documentations personnelles.

- **git.md**
  - Les commandes Git essentielles.
  - Workflow Git.

- **terminal.md**
  - Les commandes de base du terminal.
  - Navigation dans les dossiers.

- **vscode.md**
  - Installation.
  - Extensions recommandées.
  - Raccourcis clavier utiles.

---

# Extensions VS Code recommandées

- ESLint
- Prettier
- GitLens
- Markdown All in One
- Error Lens
- Auto Rename Tag
- Path Intellisense

---

# Workflow Git

```text
Créer un fichier
        │
git add .
        │
git commit
        │
git push
        │
GitHub
```

---

# Progression

- [x] Installer VS Code
- [x] Installer Git
- [x] Installer Node.js
- [x] Configurer Git
- [x] Créer un compte GitHub
- [x] Créer un dépôt GitHub
- [x] Réaliser plusieurs commits
- [ ] Maîtriser Git Branch
- [ ] Découvrir Git Flow

---

# Ressources

- Documentation Git
- Documentation Node.js
- Documentation VS Code
- Documentation GitHub

---

# Auteur

Nom : NDINGA Samuel Dorval De Francis

Formation : Akieni Academy - Cohorte 3

Phase 1 - Module 0

Année : 2026

---

# Licence

Projet réalisé uniquement dans le cadre de la formation FullStack Akieni Academy.