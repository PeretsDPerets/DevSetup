# Git - Mes notes

## Qu'est-ce que Git ?

Git est un système de gestion de versions (Version Control System - VCS).

Il permet de :

- sauvegarder l'historique d'un projet ;
- collaborer avec plusieurs développeurs ;
- revenir à une version précédente ;
- créer des branches pour développer des fonctionnalités indépendamment.

---

# Workflow Git

Le cycle de travail est généralement le suivant :

```text
Modifier un fichier
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

# Commandes essentielles

## Initialiser un dépôt

```bash
git init
```

---

## Vérifier l'état

```bash
git status
```

---

## Ajouter les fichiers

Ajouter un fichier :

```bash
git add fichier.txt
```

Ajouter tous les fichiers :

```bash
git add .
```

---

## Créer un commit

```bash
git commit -m "feat: initial project setup"
```

---

## Voir l'historique

```bash
git log
```

Version condensée :

```bash
git log --oneline
```

---

## Connecter un dépôt GitHub

```bash
git remote add origin URL_DU_REPO
```

---

## Envoyer le projet

```bash
git push -u origin main
```

---

## Télécharger les dernières modifications

```bash
git pull
```

---

## Cloner un projet

```bash
git clone URL_DU_REPO
```

---

# Les types de commits

- feat
- fix
- docs
- refactor
- style
- test
- chore
- perf
- build
- ci

Exemple :

```bash
git commit -m "feat(auth): add login page"
```

---

# Bonnes pratiques

Faire des commits fréquents.

Écrire des messages explicites.

Une seule modification importante par commit.

Pousser régulièrement son travail.

---

# Ressources

https://git-scm.com/doc
