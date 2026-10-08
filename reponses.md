
## Partie 3

1. Identifiant court du premier commit : 0fcc2ba
2. Commit correspondant à l'ajout de la page Contact : 9b60256
3. Nombre actuel de commits : 7
4. Commande utilisée pour afficher l'historique sous forme graphique : git log --oneline --graph

Commande utilisée pour examier un commit correspondant à la fonctionnalité Contact : git show de6b9d0

## Partie 5

J'ai choisi la commande : git reset --soft HEAD~1. Les modifications sont toujours présentes grâce au "--soft". Si à la place du soft on mettais "--hard", les modifications ne serraient plus présentes.

### Mission 9

Dans cette mission on a utilisé git revert plutot que git reset car l'équipe à déjà récupéré le commit, donc avec un reset on aurait eu un log différent de l'équipe.

## Partie 7

La commande utilisée est : git cherry-pick 3918126 (pour mon cas), car elle permet de récupérer seulement le commit 3918126. Une fusion classique aurait pris aussi les commits 1 et 3.

## Partie 8

Pour ce qui est du tag v1.0.0, le premier chiffre représente une modification majeure, le 2e une modification mineure, et le 3e un correctif.
 - Correction de bug mineur : 1.0.1
 - Nouvelle fonctionnalité compatible : 1.1.0
 - Refonte majeur incompatible : 2.0.0


## Questions finales

1. Ce sont les 3 zones en lien avec GIT. La zone de travail, c'est la zone dans laquelle on retrouve nos fichiers/dossiers sur notre ordinateur. La zone de staging c'est lorsque l'on fait git add. Et l'historique, c'est en quelques sortes la zone pour retrouver nos commit.
2. Ca permet d'isoler le travail en cours.
3. Reset fais disparaître le commit, revert ajout un nouveau commit pour annuler le précédent.
4. Lorsque tu dois changer de branche en urgence mais que tu ne peux pas commit.
5. Lorsque l'on ne souhaite pas fusionner toute la branche mais juste des commits précis.
6. HEAD est un pointeur qui indiquie ou est ce qu'on est dans l'historique.
7. Le commit situé 2 commits avant HEAD.
8. Un tag donne un nom précis à un commit.
9. Ils sont plus facils à manipuler, à lire et à modifier que des gros commits.
10. Car ils peuvent être sensible (contients des mdp) par exemple.