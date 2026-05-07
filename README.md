# osyniaTrade
pine scripts

indicateurs:
-MACD
-RSI
-SMA
-VIDYA

## Maintenance
### Créer une branche feature
git checkout -b feature/ma-fonctionnalite

### Faire vos modifications et commits
git add .
git commit -m "feat: Description de la fonctionnalité"

### Retourner sur main et fusionner
git checkout main
git merge feature/ma-fonctionnalite

### Envoyer les modifications
git push origin HEAD

### Tagger la version après deploiement

- mettre à jour Readme.md + VERSION + CHANGELOG.md
- git tag -a v0.0.0 -m "Version 0.0.0 : Création du projet"
- git push origin v0.0.0
