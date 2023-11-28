#Workshop Docker

##Étape 1: Introduction à Docker
Exercice : Installation de Docker

Installez Docker sur votre machine en suivant les instructions officielles : Guide d'installation Docker

##Étape 2: Concepts de base de Docker
Commande docker ps

Cette commande liste les conteneurs Docker en cours d'exécution sur votre machine.

bash

docker ps

La sortie affiche les détails des conteneurs actuellement en cours d'exécution, tels que leur ID, le nom, l'image utilisée, le statut, les ports exposés, etc.
Commande docker images

Cette commande liste toutes les images Docker présentes sur votre machine.

bash

docker images

La sortie affiche des informations sur les images Docker disponibles, y compris leur ID, le référentiel, la version, la date de création, et la taille.
Commande docker run

Cette commande crée et exécute un conteneur à partir d'une image Docker spécifiée.

bash

docker run -d -p 8080:80 --name mon_conteneur mon_image

Options utilisées dans cet exemple :
    -d: Lance le conteneur en arrière-plan (détaché).
    -p 8080:80: Mappe le port 8080 de l'hôte au port 80 du conteneur.
    --name mon_conteneur: Donne un nom au conteneur.
    mon_image: Spécifie l'image à utiliser pour le conteneur.

##Étape 3: Création d'Images Docker

Créez votre propre image Docker en rédigeant un fichier Dockerfile. Utilisez ce Dockerfile pour construire une image et exécutez un conteneur basé sur cette image.

##Étape 4: Gestion des Volumes
Exercice : Comprendre l'importance des volumes

Créez un conteneur avec un volume, effectuez des modifications dans le volume, et observez comment ces changements persistent.

##Étape 5: Docker Compose pour l'Orchestration
Exercice : Écrire un fichier docker-compose.yml

Définissez et orchestrez un ensemble de services. Exécutez ces services ensemble en utilisant Docker Compose.
##Étape 6: Réseau Docker
Exercice : Exploration de la mise en réseau dans Docker

Créez un réseau Docker, attachez des conteneurs à ce réseau, et testez la communication entre les conteneurs.

N'oubliez pas d'encourager les participants à poser des questions tout au long de l'atelier. Bonne chance avec votre workshop Docker !
