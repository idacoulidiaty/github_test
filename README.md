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

## faire un commit:
- vérifier l'état actuel du commit: git status
- ajouter le fichier


