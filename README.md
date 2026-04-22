# CloudStream Repo prêt à remplir

## Fichiers
- `repo.json`
- `plugins.json`
- `builds/` pour tes fichiers `.cs3`

## Étapes
1. Crée un dépôt GitHub nommé `cloudstream-repo`
2. Envoie ces fichiers à la racine du dépôt
3. Active GitHub Pages dans les paramètres du dépôt
4. Remplace `TONPSEUDO` dans `repo.json` et `plugins.json` par ton pseudo GitHub
5. Ajoute dans CloudStream :
   `https://TONPSEUDO.github.io/cloudstream-repo/repo.json`

## Mise à jour
À chaque nouvelle build d’un plugin :
- remplace le fichier `.cs3` dans `builds/`
- augmente `version` dans `plugins.json`
- push sur GitHub
