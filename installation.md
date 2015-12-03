Git > logiciel de gestion de versions décentralisé (pas local, sur internet) sauvegarde incrémentale
Github > service web d'hébergement et de gestion de développement de logiciels, utilisant le logiciel de gestion de versions Git
Jekyll > logiciel open source permettant de générer des pages web statiques


1-Allumer la machine virtuelle

2-Ouvrir une fenêtre Terminal dans le répertoire "home"

3-Créer un répertoire "sites": atc123@linux-van:/home$ sudo mkdir sites

4-Entrer dans le répertoire "sites" : atc123@linux-van:/home$ cd sites/

5-Créer un fichier README.txt : atc123@linux-van:/home/sites$ sudo touch README.txt

6-Installer Jekyll : atc123@linux-van:/home/sites$ sudo apt-get install jekyll

7-Lancer Jekyll : atc123@linux-van:/home/sites$ jekyll &

8-Créer un nouveau site : sudo jekyll new MonSiteMarina

9-Renter dans le dossier "MonSiteMarina" : cd MonSiteMarina

10-Lancer le serveur : sudo jekyll serve
->Server address : http://0.0.0.0:4000/

11-Installer Ruby : sudo apt-get install ruby-full

12-Mise à jour de jekyll : sudo gem update jekyll
 

Git:
- git status
- git add + nom fichier > ajouter un ficher 
- git add . > ajouter tous les fichiers
- git commit -am "_" > commentaire > fait une photographie de ton travail à un instant T > permet de revenir en arrière pour chaque commentaire enregistré 
- git log >
- git push > envoyer les modifications sur Github