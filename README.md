# Documentation du tuto Github avec Git

## Initialisation du dépôt

```bash
git init
git remote add origin SSH_REPO
```

## Rédiger un commit (bonne pratique)

```
Titre du commit

Description de notre commit avec des informations sur
l'évolution du projet
```

## Envoyer un commit sur le dépôt distant

```bash
git add .
git commit -m "Titre du commentaire"
git push origin main
```

## Création d'une branche

```bash
git checkout -b nom_de_la_branche
```

Pour les bonnes pratiques, on va intégrer la notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur le dépôt distant, puis créer une pull request pour demander une revue de code.