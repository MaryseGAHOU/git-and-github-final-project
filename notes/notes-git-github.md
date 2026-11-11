# 📝 Notes d'apprentissage Git & GitHub

## Pourquoi le contrôle de version ?

Un projet logiciel implique plusieurs personnes (front-end, back-end, DBA...). Le contrôle de version permet de :
- Tracer **qui** a modifié **quoi**, **quand** et **pourquoi**
- Revenir à n'importe quelle version du projet
- Travailler en parallèle grâce aux **branches**
- Fusionner les contributions proprement

## Vocabulaire clé

- **Dépôt (repository)** : projet suivi par Git avec tout son historique
- **Commit** : instantané des modifications + message descriptif
- **Branche** : ligne de développement indépendante (par défaut : `main`)
- **Pull Request** : proposition de fusion d'une branche, avec relecture
- **Fork** : copie d'un dépôt sur son propre compte GitHub
- **Clone** : copie locale d'un dépôt distant

## Commandes du quotidien

```bash
git clone <url>              # copier un dépôt
git status                   # voir l'état des fichiers
git add .                    # préparer les modifications (staging)
git commit -m "message"      # enregistrer un instantané
git push origin main         # publier vers GitHub
git pull origin main         # récupérer les changements distants
git checkout -b branche      # créer et basculer sur une branche
git merge branche            # fusionner une branche
```

## Licences open source

- **MIT** : la plus permissive et la plus simple (choisie ici)
- **Apache 2.0** : permissive + clause brevets
- **GPL** : copyleft — les dérivés restent open source
