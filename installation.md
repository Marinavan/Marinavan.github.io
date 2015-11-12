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
