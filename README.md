#Documentation du tuto GitHub avec Git

## Initiation du depot

```bash
git init
git remote add origin git@github.com:fabio971/tuto_git.git
git status
git add README.md
git status
git commit -m “Commit init”
git branch -M main
git push origin main
```

## Rediger un commit

```
Titre commit

Description du commit avec des informations sur l'évolution du projet
```

## Envoyer un commit à distant
```bash
git add .
git commit -m "Titre commit"
git push origin main
```

## Création d'un branche
```bash
git checkout -b <nom_branche>
``` 
