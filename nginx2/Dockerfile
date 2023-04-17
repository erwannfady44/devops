#Choix de l'image
FROM nginx:stable
#Mise à jour
RUN apt update && apt upgrade
#Création de la page d'accueil
RUN echo "Hello from serveur 2" > /usr/share/nginx/html/index.html
#Ouverture du port
EXPOSE 80