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
