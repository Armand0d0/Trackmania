# Trackmania

Le jeu de course Trackmania stocke les données du jeu sous forme de fichiers .gbx, notamment le fichier "replay" qui contiennent les données d'une course jouée par un joueur. Décoder ses fichiers permet donc d'accéder aux positions, rotatons de la voiture à chaque frame, ainsi qu'aux input que le joueur réalisé. Trackmania est un jeu déterministe, donc les mêmes entrées produisent la même course, on pourait donc utiliser ces données pour reproduire une partie de course informatiquement et creer des "checkpoint" virtuels.
 
 Sur l'encodage des .GBX :
 https://wiki.xaseco.org/wiki/GBX

