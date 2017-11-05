# Installation de l'environnement php apache mysql

Cet environnement permet de développer sur le langage PHP

## Installation de Docker


### Telecharger Docker:

  Si votre système est sous windows 7/8/10 famillial: https://www.docker.com/products/docker-toolbox
  
  Si votre système est sous linux / mac os /windows 10 pro : https://www.docker.com/
  
  Une fois téléchargé, installer le et laisser les paramètres par défaut.
  
### Installation de l'environnement php apache mysql :
  
  Créer un répertoire avec le nom de l'image.
  
  Clonner/Télécharger le dépot Github.
  
  Ouvrir un teminal (sous linux/mac os) ou invite de commande ou PowerShell (Windows).
  
  Se rendre dans le répertoire où il y a le clone du dépot GitHub via le terminal.
  
  Puis Exécuter les commandes suivantes:
  
  ```
  #/> docker-compose build
  #/> docker-compose up -d //cette commande permet de lancer les containers concernés
  ```
  
  Une fois lancé, vous pouvez aller sur votre navigateur et taper l'adresse suivante pour vous connectez sur votre environnment:
  
    -Windows 7/8/10 famillial : 192.168.99.100:8081
    
    -linux /mac os/windows 10 : localhost:8081
  
  
  Pour arrêter l'environnement il suffit d'exécuter cette commande:
  
  ```
  #/> docker-compose down
  ```
