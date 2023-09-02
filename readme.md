# Dcumentation git

- [Manual](https://git-scm.com/doc)
- [Livre Pro-Git](https://git-scm.com/book)

# Demarrage

Un dépôt **git** doit contenir 3 fichiers :

- un fichier **readme.md** qui introduit et explique votre projet :
    - [https://www.makeareadme.com/](https://www.makeareadme.com/)
    - [https://readme.so/fr](https://readme.so/fr)
    - [https://github.com/matiassingers/awesome-readme](https://github.com/matiassingers/awesome-readme)

- un fichier **.gitingore** qui permet de spécifier les fichiers,dossiers à ne pas suivre
    - [https://gitignore.io](https://gitignore.io)
    - [https://github.com/github/gitignore](https://github.com/github/gitignore)

## Créer un nouveau dépôt en ligne de commande

```
echo "# depart-git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/formeka/depart-git.git
git push -u origin main
```

## Envoyer(push) un dépôt existant en ligne de commande

```
git init
git remote add origin https://github.com/formeka/depart-git.git
git branch -M main
git push -u origin main
```
