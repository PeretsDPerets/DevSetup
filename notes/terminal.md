# Terminal - Mes notes

## Qu'est-ce que le terminal ?

Le terminal est une interface permettant de communiquer directement avec le système d'exploitation à l'aide de commandes.

Il est utilisé quotidiennement par les développeurs.

---

# Navigation

Afficher le dossier courant

```bash
pwd
```

Lister les fichiers

```bash
ls
```

Lister avec détails

```bash
ls -la
```

Changer de dossier

```bash
cd nom-du-dossier
```

Revenir au dossier précédent

```bash
cd ..
```

Revenir au dossier personnel

```bash
cd ~
```

---

# Création

Créer un dossier

```bash
mkdir mon-dossier
```

Créer un fichier

```bash
touch fichier.txt
```

---

# Suppression

Supprimer un fichier

```bash
rm fichier.txt
```

Supprimer un dossier vide

```bash
rmdir mon-dossier
```

Supprimer un dossier avec son contenu

```bash
rm -r mon-dossier
```

---

# Copier

```bash
cp fichier.txt copie.txt
```

---

# Déplacer ou renommer

```bash
mv ancien.txt nouveau.txt
```

---

# Effacer l'écran

```bash
clear
```

Sous Windows PowerShell :

```powershell
cls
```

---

# Vérifier les versions

Git

```bash
git --version
```

Node

```bash
node -v
```

npm

```bash
npm -v
```

---

# Bonnes pratiques

- Utiliser les flèches ↑ ↓ pour retrouver les commandes précédentes.
- Utiliser la touche TAB pour l'autocomplétion.
- Lire attentivement les messages d'erreur.
- Toujours vérifier le dossier courant avant d'exécuter une commande.

---

# Ressources

https://www.gnu.org/software/bash/

https://learn.microsoft.com/powershell/