Git par la pratique
===================

* Mettez vous en binôme.
* [Installez Git et configurez-le pour GitHub](http://help.github.com/set-up-git-redirect/)
* Dupliquez (*fork*) le projet TP-Git dans votre espace public.
* Récupérez sur votre disque dur les sources du projet.

        git clone git@github.com:votrecompte/TP-Git.git

* Indiquez le dépôt officiel :

        cd TP-Git
        git remote add official git@github.com:benel/TP-Git.git 

* Sur votre disque dur, ajoutez à la fin de ce fichier le prénom et le nom d'un des membres du binôme. La ligne doit commencer par une étoile. Corrigez la liste pour que la dernière ligne se termine par un point et les autres par des virgules.
* Faites une révision et publiez-la dans votre espace public:

        git add README.md
        git commit
        git push

* Dans GitHub faites une demande d'intégration (*pull request*). 
* Mettez à jour votre disque dur jusqu'à ce que vous récupériez les modifications de quelqu'un d'autre.

        git pull official 

* Ajoutez le prénom et le nom de l'autre membre du binôme et recommencez la procédure.


Liste des étudiants ayant suivi ce TP
-------------------------------------

* 
