on accede d'abord aux données du site avec ```dig @challenge01.root-me.org -p 54011 ch11.challenge01.root-me.org``` dig sert à acceder aux données du domaine</br>
on trouve un serveur qu'on essaye de ping pour voir qu'il existe bien et voir a quoi ressemble notre cible </br>
désormais on peut utiliser AXFR qui est un mechanisme qui qui assure que toutes les données sont bien passées entre 2 serveurs DNS ce qui peut permettre de récupérer certaines données sensible</br>
on rajoute just axfr à la précédente commande ce qui nous donne le flag