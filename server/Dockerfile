# Utiliser l'image de base
FROM node:lts-alpine

# Définir le répertoire de travail
WORKDIR /app

# Copier les fichiers package*.json
COPY package*.json ./

# Installer les dépendances
RUN npm install

# Copier le reste des fichiers
COPY . .

# Exposer le port 9000
EXPOSE 9000

# Démarrer l'application
CMD ["npm", "start"]
