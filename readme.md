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

- fichier **LICENCE.md** qui permet d'avoir un contrat avec les utilisateurs de votre projet
   - [Licence logiciel](https://fr.wikipedia.org/wiki/Licence_de_logiciel)
   - [Licence juridique](https://fr.wikipedia.org/wiki/Licence_(juridique))
   - [Pourquoi vous devriez vous intéresser aux licences de vos logiciels ?](https://fr.linkedin.com/pulse/pourquoi-vous-devriez-int%C3%A9resser-aux-licences-de-vos-logiciels-madet?trk=pulse-article_more-articles_related-content-card)

## Créer un nouveau dépôt en ligne de commande

```
touch README.md LICENCE.md .gitignore
git init
git add *
git commit -m "Debut du prjet initialisation"
git branch -M main (renommer branche principale si besoin)
git remote add origin https://github.com/user/nom-depot.git
git push -u origin main
```

## Envoyer(push) un dépôt existant en ligne de commande

```
git init
git remote add origin https://github.com/user/nom-depot.git
git branch -M main (renommer branche principale si besoin)
git push -u origin main
```
