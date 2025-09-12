---
description: Retrouvez ici toutes les informations vous permettant de nous aider à modifier ce wiki
---

# Contribution

Bienvenue ! Ce guide vous accompagnera pas à pas dans la <mark style="color:blue;">**contribution**</mark> au wiki du projet <mark style="color:blue;">**Evolucraft**</mark> sur <mark style="color:blue;">**GitHub**</mark>.

## 📋 <mark style="color:blue;">Pré-requis</mark>

* Créez un compte GitHub : [Inscription GitHub](https://github.com/join).
* Installez Git sur votre ordinateur : [Télécharger Git](https://git-scm.com/downloads).
* Choisissez un éditeur simple et convivial comme [Visual Studio Code](https://code.visualstudio.com/).

## ⚙️ Installer et configurer Git

Après l'installation, ouvrez votre terminal et configurez votre nom et email (ceux utilisés pour GitHub) :

```bash
git config --global user.name "Votre Nom"
git config --global user.email "votre-email@example.com"
```

## 🚀 <mark style="color:blue;">Faire une contribution</mark>

### <mark style="color:blue;">1.</mark> <mark style="color:blue;">Forker le Repository</mark>

* Rendez-vous sur [wiki-evolucraft](https://github.com/Rivrs-OSS/wiki-evolucraft)
* Cliquez sur le bouton <mark style="color:blue;">**Fork**</mark> en haut à droite pour créer une copie du repository sur votre compte.

### <mark style="color:blue;">2. Cloner votre Fork sur votre ordinateur</mark>

Copiez le lien de votre fork puis dans votre terminal :

```bash
git clone https://github.com/VOTRE-NOM-UTILISATEUR/wiki-evolucraft.git
cd wiki-evolucraft
```

### <mark style="color:blue;">3. Créer une nouvelle branche</mark>

Créer une branche par sujet traité pour bien organiser vos contributions :

```bash
git checkout -b nom-de-votre-branche
```

Exemple : `git checkout -b ajout-guide-capture`

### <mark style="color:blue;">4. Modifier le Wiki</mark>

* Utilisez Visual Studio Code pour éditer les fichiers markdown (`.md`).
* Vous pouvez également créer de nouveaux fichiers, par exemple `comment-creer-ma-box.md`.

Exemple de structure markdown simple :

```markdown
# Titre principal

## Sous-titre

Votre contenu ici...

- Liste à puces
- Second point

[Un lien utile](http://example.com)
```

### <mark style="color:blue;">5. Ajouter vos modifications à Git</mark>

Dans votre terminal, ajoutez et validez vos changements :

```bash
git add .
git commit -m "Ajout du guide sur les métiers"
```

### <mark style="color:blue;">6. Envoyer votre contribution</mark>

Envoyez vos modifications sur GitHub :

```bash
git push origin nom-de-votre-branche
```

### <mark style="color:blue;">7. Ouvrir une Pull Request (PR)</mark>

* Retournez sur votre fork du projet GitHub.
* Cliquez sur <mark style="color:blue;">**Compare & pull request**</mark>.
* Décrivez votre contribution clairement puis validez en cliquant sur <mark style="color:blue;">**Create pull request**</mark>.

## 💡 <mark style="color:blue;">Bonnes pratiques et conseils</mark>

* Restez clair et concis dans vos explications.
* Vérifiez l'orthographe et la grammaire.
* Structurez bien vos pages markdown.
* Utilisez les prévisualisations markdown de Visual Studio Code (Ctrl + Shift + V) avant de soumettre.

## 🛠️ <mark style="color:blue;">En cas de problème</mark>

N'hésitez pas à créer une [issue](https://github.com/Rivrs-OSS/wiki-evolucraft/issues) sur GitHub pour demander de l'aide ou poser une question.

Merci pour votre contribution ! ✨
