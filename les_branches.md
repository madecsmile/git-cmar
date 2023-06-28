# Les branches

## Créer une branche

- `git checkout -b nom_branche` : Créer une branche et se placer dessus
- `git branch nom_branche` : Créer une branche
- `git branch nom_branche hash_commit` : Créer une branche à partir d'un commit

## Les branches peuvent être protégées

- depuis l'interface web de github, dans la configuration du projet

Cela permet de sécuriser pour éviter une suppression par erreur par exemple.

## Se placer sur une branche

- `git checkout nom_branche` : Se placer sur une branche

## Renommer une branche

- `git branch -m ancien_nom nouveau_nom` : Renommer une branche

## Supprimer une branche

- `git branch -d nom_branche` : Supprimer une branche

## Déplacer une branche en force 

- `git branch -f nom_branche hash_commit` : Déplacer une branche en force

*Attention : cette commande peut faire perdre des commits, il faut être sûr de ce que l'on fait*

*Il ne faut pas être sur la branche que l'on déplace*

## Déplacer une branche en force (2)

- `git reset --hard hash_commit` : Déplacer une branche en force

*Peut être fait quand on est sur la branche*
modif
