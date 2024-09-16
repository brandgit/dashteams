# Utiliser une version LTS de Node.js
FROM node:18

# Définir le répertoire de travail
WORKDIR /usr/src/app/api

# Copier le code de l'application depuis le volume
COPY . .

# Installer les dépendances
RUN npm install

# Exposer le port de l'application
EXPOSE 3000

# Démarrer l'application
CMD [ "node", "app.js" ]
