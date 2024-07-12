# Mémo Git et GitHub

# différence entre git et github

Git est un projet open source d egestion de code, créee par Linux Torvalds.

Github est un eplatforme  d'hébergement de projets Git

## Céer des clées :
- aller dans le terminal et se mettre dans le bon repertoire
- entrer le code suivant: ssh-keygen -t ed25519 -C "your_email@example.com"
- verifier que les clés ont bien été créees
- créeer l'agent shh: eval "$(ssh-agent -s)"
-  ajouter notre clé privée à l'agent ssh: ssh-add ~/.ssh/id_ed25519

## Workflow git et github de base:
- faire une modification en local (ex sur VS code)
- git add . (le ' .' c'est pour add tout le repertoire)
- git commit -m "message de commit" (mettre un vrai message)
- git push origin main (pousser les modifs locales vers github) (git push -u origin main : le ' -u' n'est mis que sur le 1er commit pour synchroniser notre fichier en local avec github. Il n'e pas necessaire de le rajouter sur les commits suivants)

## configurer Git:
git config –global user.name “”
git config –global user.email “”

## Créer un dossier:
mkdir monprojet

## Aller dans un dossier:
cd mondossier

## initialiser un repertoir git:
git init

## Voir l’état actuel de git:
git status

## photographier tous les fichiers:
git add --all

## Faire un commit:
git commit -m “nom de mon commit”

## Voir si un fichier a été modifié:
git status –short

## Voir l’historique des commits :
git log


## Voir toutes les commandes possibles sur git:
git help –all

## Voir les options disponibles pour une comùmande spécifique:
git commande -help

## Créer une branche:
git branch mabranche

## Verifier une branche:
git checkout mabranche
Possibilité d’utiliser l’option -b sur checkout  pour créer une nouvelle branche et l’ouvrir si elle est encore inexistante

## fusionner:
git merge mabranche

## Supprimer une branche:
git branch -d mabranche

## Entrer dans une branche:
git checkout mabranche


