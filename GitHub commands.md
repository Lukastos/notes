
Activer dossier comme dépôt Git:
>git init

Ajouter fichier au dépôt:
>git add nimdufichier.md

Ajouter tous les fichiers du dossier:
> git add .

Faire un commit:
>git commit -m "les modifs que j'ai faites à nomdufichier.md"

Ajouter et commit d'un fichier (il est nécessaire de faire les deux pour enregistrer les modificaitions d'un fichier)
>git commit -a -m "création et ajout de nomdufichier.md"

Historique des commits:
>git log

Se positionner sur un commit
>git checkout SHADuCommit

retour à la branche principale
>git checkout master 

retour à la branche principale et ignore les changements non enregistrés
>git checkout -f master 

crée un brouillon récupérable plus tard:
>git stash

rétablir commit
>git revert SHAducommit

Modifier texte du dernier commit
>git commit --amend -m "Votre nouveau message"

Annuler toutes les modifs depuis le dernier commit
>git resert --hard

Cloner un dépôt:
>git clone lienFourniParGitHub 

Pousser une commander git:
>git push origin master
