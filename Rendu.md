Dans ce repos, vous trouverez 2 dossier :
bdd: on y retrouve tous les .yaml pour deployer la base redis
serveur: on y retrouve tous les .yaml pour deployer le serveur node-redis
bonus:

=> Pour deployer la base redis, j'utilise la dernière version de l'image docker officiel "redis:latest". 
Et, je fais un deploiement d'un replicat en l'exposant sur le port 6379.

=> Pour deployer le serveur, j'utilise l'image du serveur fourni et l'expose sur le port 8080 et je communique avec la base redis via l'adresse ip"10.3.183.121" et l'écoute sur le port 6379 

