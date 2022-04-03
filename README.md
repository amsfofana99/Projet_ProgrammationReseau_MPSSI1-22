# Projet_ProgrammationReseau_MPSSI1-22
Projet de Programmation Réseau réalisé par Mouhamed Sarr et Amadou Mame Samba Fofana.

Ceci n'est qu'une  briève explication de l'environnement technique du projet.

Pour mener à bien ce projet, mais également faute de ressources suffisantes, nous avons utilisé deux machines virtuelles à système d'exploitation Ubuntu 21 dont l'une est à interface graphique et l'autre est en ligne de commande (serveur). Nous avons implémenté sur la machine à interface graphique  les services suivants: DHCP, DNS, Messagerie(MAIL), Base de données(MySQL) et analyseur de paquets par le biais d'un autre programme indépendant de wireshark que nous n'avons pu avoir faute de ressources suffisantes.  

Pour lancer l'exécution des programmes, on tape d'abord la commande "python3 server.py" sur le terminal de la machine server et on en fait autant avec la commande "python3 client.py" sur la machine cliente. On peut ainsi observer sur la machine cliente qu'on nous propose 3 options différentes à savoir: 
                                         1- S'inscrire
                                         2- Se connecter
                                         3- Quitter .  
Pour voir à l'oeuvre notre analyseur de paquets, après avoir lancé les deux commandes précédentes  sur leurs machines respectives, on ouvre deux autres fenêtres de terminal sur la machine server où sur l'une on écrit "python3 analyser.py 60" et sur l'autre "python3 Sendmail.py 30". L'utilité de ces deux dernières commandes est de lancer le programme d'analyse de paquets pour une durée de 60s et la seconde va récupérer le résultat de l'analyseur et va l'envoyer par mail à l'administrateur du parc informatique. Les mails pourront être lus par l'administateur sur un navigateur bien évidemment via la machine server qui dispose d'une interface graphique.

La vidéo jointe de la simulation illustre plus en détails cette situation de mise en pratique de notre projet.


                                      
