# Dockerfile

FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app
COPY package*.json ./
RUN npm i
COPY src src

CMD npm start

# RUN te permet d'exécuter une commande comme tu le ferais dans ton terminal.
# WORKDIR définit un répertoire de travail
# COPY copie le fichier indiqué de ta machine dans l'image.
