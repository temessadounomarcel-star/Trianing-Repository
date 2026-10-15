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

 # Ajouter un nouveau fichier Readme.md et voir
 > git add README.md