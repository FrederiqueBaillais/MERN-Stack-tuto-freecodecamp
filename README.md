# MERN-Stack-tuto-freecodecamp

Tutorial [MERN](https://www.youtube.com/watch?v=7CqJlxBYj-M) Stack by freeCodeCamp.org
nouvelle version du tuto [ici](https://www.youtube.com/watch?v=mrHNSanmqQ4&t=0s)

**Etapes :**

+ Se connecter à MongoDB
++ Créer un nouveau projet
++ Créer un nouveau Cluster
++ Se connecter au cluster : pour les besoins de ce tuto, on mettra notre adresse IP actuelle, Add my IP Address, créer un utilisateur et son mot de passe, create database user, choose a connection method et choisir connect your application, sélectionner driver : node.js, version : 3.6 or later, close
++ cliquer sur ... et sélectionner Load simple dataset puis load simple dataset
++ cliquer sur collections, sélectionner sample_restaurants puis restaurants

+ Vérifier que node est installé ```node -v```
Ici, j'ai v10.19.0

+ créer l'application avec les différentes dépendances qui seront installées automatiquement
```npx create-react-app restaurants-reviews```

+ aller dans le dossier nouvellement créé
```cd restaurants-reviews```

+ dans ce tuto nous allons créer d'abord le back-end et ensuite le front-end

+ créer un nouveau dossier nomme backend
```mkdir backend```

+ aller dans le dossier nouvellement créé
```cd backend```

+ initialiser le dossier backend et y insérer un package.json
```npm init -y```

+ installer les dépendances
```npm install express cors mongoose mongodb dotenv```

+ installer la console nodemon
```npm install -g nodemon``` ou ```sudo npm install -g nodemon```

+ ajouter une ligne dans package.json : en dessous de main, ajouter "type": "module"

+ dans backend, créer un nouveau fichier nommé ```server.js```

+ remplir le fichier server.js

+ créer un nouveau fichier .env, aller chercher dans mongoDB les informations de connection de la DB
++ connect, connect your application, copy le code proposé pour la connection à la DB
++ revenir dans .env et indiquer les valeurs des variables RESTREVIEWS_DB_URI, RESTREVIEWS_NS et PORT

+ créer un nouveau fichier index.js et le compléter

+ créer un nouveau dossier api et créer un nouveau fichier 

+ tester l'application dans le terminal nodemon server (vérifier que je suis bien dans le dossier backend pour lancer nodemon)

+ aller voir dans l'explorer sut http://localhost:5000 (où 5000 est le port en lecture, sinon 8000)

+ 