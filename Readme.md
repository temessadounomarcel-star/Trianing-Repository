# l'apprentissage de git hub

# Vérifier la version de tit hub

git -- version


# Vérifier le compte de connexion

git config --global --list


# pour voir les informations des utilisateur

git config --global user.name
git config --global user.email

# Afficher toutes les informations sur le depot actuel

git config --global --list

# Création de dépot local Git_learning
> mkdir Git_learning
> cd Git_learning

# Vérifier si git est déjà configuré
> git status  # pour ce debut ce sera une error : fatal: not a git repository (or any of the parent directories): .git

# Initié git sur votre dépot actuel
 > git init

# Vérifier la branche sur laquelle on se trouvre (main ou master au debut)

 > git branch --show-current

# Ajouter un nouveau fichier Readme.md ( Ce fichier doit au préalabre etre créer dans le depot courant)
# Toujours vérifier avec git status
 > git add Readme.md

# Créer un commmit, il enregistre dans l'historique local
> git commit -m "Le document Readme.md est bien ajouté"

# Il faut se rendre compte de la réalité, voir les logs

> git log --oneline



# Maintenant on va faire le push

# Dabord, vérifier le dépot présent, s'il n'est pas lié à un depot distant
> git remote -v

# si n'y a pas de depot github associé, il faut le créer et prendre ce lien qu'on propose
 > git remote add origin https://github.com/temessadounomarcel-star/Trianing-Repository.git

# Vérifier la branche sur laquelle vous vous trouver 
> git branch

# Renomer la branche si vous voulez bien 
> git branch -M NouveauNom

# faire le push sur cette branche : si -u la prochaine fois sur cette branch faire juste  git push 
>  git push -u origin main

# Vérifier que les branches on été envoyé
 > git branch -a

 # faire le merge sur la branch main

 > git switch main
 > git merge "branch_Name"

 # Une fois le travail fusionné, on peux supprimer la branche

 > git branch -d "Branch_Name"

 

