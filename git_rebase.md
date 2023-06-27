# Commande git rebase

## Fusionner des commits avec rebase interactif

- `git rebase -i hash_commit` : rebase interactif

> TODO : créer 3 commits et les fusionner en 1 seul

> echo "1" > fichier1.txt && echo "2" > fichier2.txt && echo "3" > fichier3.txt && git add fichier1.txt && git commit -m "commit 1" && git add fichier2.txt && git commit -m "commit 2" && git add fichier3.txt && git commit -m "commit 3"

* hash_commit peut être HEAD~n (n = nombre de commit à remonter)

> git rebase -i HEAD~4

## Déplacer une branche avec rebase

- `git rebase nom_branche` : Déplacer une branche

> TODO : Déplacer la branche courante au dessus de la branche 'le_commit'

## "Couper" une branche et la placer sur une autre

- `git rebase --onto nom_branche_destination_ hash_commit_a_couper  nom_branche_a_deplacer` : Couper une branche et la placer sur une autre

> TODO : Déplacer la branche courante au dessus de la branche 'les branches' sans prendre en compte les commits de la branche 'le commit'