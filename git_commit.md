# Commande git commit

git commit permet de créer un commit à partir des modifications en cours.

Il est nécessaire d'indiquer à git quels fichiers doivent être pris en compte pour le commit (staging). Pour cela, il faut utiliser la commande git add (ou via un IDE).

## Ajouter des fichier au staging

- `git add nom_fichier` : Ajouter un fichier au staging

## Consulter les fichiers en staging

- `git status` : Consulter les fichiers en staging

## Créer un commit

- `git commit -m "message du commit"` : Créer un commit

Seul les fichiers en staging sont pris en compte pour le commit.

> TODO : créer 2 fichiers et faire un commit contenant un seul fichier, puis un commit contenant le second fichier.

## Modifier le dernier commit

- `git commit --amend -m "nouveau message"` : Modifier le message du dernier commit

> TODO : créer un 3ème fichier et l'intégrer au dernier commit
