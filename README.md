# Test GitHub Page HTML

## Présentation

Ce projet est un petit test de site web en HTML.

Le projet est hébergé sur GitHub sous le nom [test-github-html-page](https://github.com/Winsmo/test-github-html-page)

## Utilisation des commandes git

Lorsque le projet est modifié, par exemple lorsqu'on corrige une page HTML, CSS, etc. ou lorsqu'on ajoute ou supprime
des fichiers du projets, on peut valider ces changement dans le référenciel git local.

Les commandes sont les suivantes :

```shell
git add nom_du_fichier.ext   # ajoute un (ou plusieurs) fichier(s) dans l'index de git
git add .  # ajoute tous les fichiers modifiés du répertoire dénoté par "."
git commit -m "Message décrivant les modifications effectuées"````
```

Les fichiers sont maintenant référencé dans le dépôt git local (dans le dossier caché `.git/`).

Pour affichier l'historique des chamgements, on peut utiliser la commande `git log`, par exemple :

```shell
git log --all --decorate --oneline --graph
```

Produira :

```text
* 3d2e892 (HEAD -> main, origin/main) Corrections de Gladys
* 537ae95 test image
* 913f8f0 ajout image shiba
* 65d9da1 Ajout page test
* 9f4f120 test html
* a85b518 ajout coucouc
* c564a6d Ajout du sous-titre
* ec19bba Ajout de la page principale
* a2c663f Mon premier commit
```

## Publication du site web

Maintenant que tout est à jour dans le dépôt git local, on peux télécharger les modifications sur GitHub.
Pour ce faire, il convient simplement d'utiliser la commande `git push` :

```shell
git push
```

Le "push" déclenche automatiquement une action dans GitHub pour construire et publier les pages HTML dans GitHub Pages.
Le résultat est disponible à l'adresse [https://winsmo.github.io/test-github-html-page/](https://winsmo.github.io/test-github-html-page/)


## Références et tutos

- [HTML (HyperText Markup Language)](https://developer.mozilla.org/fr/docs/Web/HTML) **LA** référence du langage HTML
- [HTML5 Tutorial](https://www.w3schools.com/html/) toturiels simple pour commencer avec HTML5 / CSS / JavaScript
- [Aide mémoire des commandes git](https://training.github.com/downloads/fr/github-git-cheat-sheet/)
- [Ignorer des fichiers](https://docs.github.com/fr/get-started/getting-started-with-git/ignoring-files) avec un `.gitignore`
- Créer des notes avec [Markdown](https://docs.github.com/fr/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github)
