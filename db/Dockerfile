#Choix de l'image
FROM postgres:15.2-alpine
#Mise à jour
RUN apk update && apk upgrade
#Création du répertoire de logs
RUN mkdir /var/log/postgres
RUN chown -R postgres /var/log/postgres
#Ouverture du port
EXPOSE 5432
