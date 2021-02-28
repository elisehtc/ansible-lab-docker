# ansible-lab-docker

Après avoir cloné depuis le dépôt
git clone https://github.com/LMtx/ansible-lab-docker.git

j'ai tout de suite modifié la version de l'image ubuntu de 17.10 vers 18.04

puis j'ai changé l'encodage des fins de ligne du fichier ansible/hosts/run.sh pour qu'elles soient en Linux/Unix (LF).

Je n'ai eu ensuite aucun problème pour lancer les images et les containers -> voir images.jpg et containers.jp

Pas de problème non plus pour faire le ping après avoir créé les clés SSH -> voir ping.jpg

Aucun soucis pour installer PHP ni pour copier les données entre les fichiers locaux et les containers.

Ensuite il n'y avait plus qu'à faire le ménage.
