# DockerProject
Pour la réalisation du projet Docker comme option, j'ai choisi la une. 
Le projet m'a permis de mettre en pratique Docker, Docker compose et Azure.
Le but de ce projet est de conteneuriser une application pour créer nos propres images.
Vous trouverez sous formet .Zip quelques captures mettant en pratique ce que vous aurez à lire au sujet de ce projet: 
Ce projet m'a permis de déployer deux conteneurs qui sont Python et Redis en plus de Ubuntu qui a déja été déployé grace aux séances précédentes.
J'ai utilisé un fichier App.py qui est une petite application utilisant le Framework Flask et qui permet d'afficher un "Bonjour", le nom de la machine sur laquelle l'application est entrain de tourner, plus le nombre de visiteurs.
Pour que cette application fontionne, y avait une liste de dépendances à installer qui sont contenues dans le fichier requirements.txt.
Flask qui est le Framework que Python utilise et Redis qui est le Driver qui permet de se connecter à une base de données Redis.
Dockerfile est un fichier qui va me permettre de de créer une image.
Les liens dockerhub : 
https://hub.docker.com/_/python?tab=tags 
https://hub.docker.com/_/redis?tab=tags 
