I - Conifguration des hôtes virtuelles 

Création d'un nouveau repertoire pour le projet Ansible

mkdir ansible-apache

cd ansible-apache



II - Création d'un fichier d'inventaire 
il faut créer un fichier d'inventaire pour spécifier l' hôte cible.

touch inventory.ini

Il faut créer un fichier playbook Ansible pour ajouter les contenus.

[Virtual_Host]

www.hei.school

api.hei.school

front.hei.school

back.hei.school




III - Création d'un fichier d'inventaire Apache2

Connecter à l'hôte cible où Apache2 est installé.
verification de l'emplacement du dossier de configuration principal d'Apache2

 apache2ctl -V
 
 Une fois dans l'emplacement
 
 nano www.hei.school.conf

nano api.hei.school.conf

nano front.hei.school.conf

nano back.hei.school.conf
