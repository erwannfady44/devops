#Choix de l'imgage
FROM nginx:stable
#Mise à jour
RUN apt update && apt upgrade
#Copie du fichier de configuration
COPY ./nginx.conf /etc/nginx/nginx.conf
#Ouverture du port 80
EXPOSE 80