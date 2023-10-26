# RestoAPI
# API de gestion de restaurant

Ce projet est une API RESTful de base pour gérer les données d'un restaurant. Il utilise Node.js, Express.js et MySQL pour créer un serveur qui gère des opérations CRUD (Create, Read, Update, Delete) pour les éléments, les catégories et les formules du restaurant.

## Configuration requise

- 
- 

## Installation

1. Clonez le dépôt depuis GitHub :

```bash
git clone https://github.com/votre-utilisateur/restaurant-api.git
```

2. Accédez au répertoire du projet :

```bash
cd restaurant-api
```

3. Installez les dépendances du projet :

```bash
npm install
```

4. Configurez la base de données MySQL :
   - Assurez-vous que MySQL est installé et en cours d'exécution.
   - Créez une base de données nommée "restaurant" (vous pouvez personnaliser le nom dans le configuration du fichier `app.js`).
   - Vérifiez que les informations de connexion à la base de données (hôte, utilisateur, mot de passe) sont correctement configurées dans le fichier `app.js`.

5. Exécutez le serveur :

```bash
npm start
```

Le serveur démarre sur `http://localhost:3000`.

## Routes

### Éléments (Items)

- `GET http://localhost:3000/items`: Récupère tous les éléments du restaurant.
- `GET http://localhost:3000/items/:id_items`: Récupère un élément spécifique en fonction de son ID.
- `POST http://localhost:3000/items`: Ajoute un nouvel élément au restaurant.
- `PUT http://localhost:3000/items/:id_items`: Met à jour un élément existant en fonction de son ID.
- `DELETE http://localhost:3000/items/:id_items`: Supprime un élément en fonction de son ID.

### Catégories (Categories)

- `GET http://localhost:3000/category`: Récupère toutes les catégories du restaurant.
- `GET http://localhost:3000/category/:id_category`: Récupère une catégorie spécifique en fonction de son ID.
- `POST http://localhost:3000/category`: Ajoute une nouvelle catégorie au restaurant.
- `PUT http://localhost:3000/category/:id_category`: Met à jour une catégorie existante en fonction de son ID.
- `DELETE http://localhost:3000/category/:id_category`: Supprime une catégorie en fonction de son ID.

### Formules (Formulas)

- `GET http://localhost:3000/formulas`: Récupère toutes les formules du restaurant.
- `GET http://localhost:3000/formulas/:id_formulas`: Récupère une formule spécifique en fonction de son ID.
- `POST http://localhost:3000/formulas`: Ajoute une nouvelle formule au restaurant.
- `PUT http://localhost:3000/formulas/:id_formulas`: Met à jour une formule existante en fonction de son ID.
- `DELETE http://localhost:3000/formulas/:id_formulas`: Supprime une formule en fonction de son ID.

## Utilisation

Vous pouvez utiliser un outil comme [Postman](https://www.postman.com/) pour tester les différentes routes de l'API. Assurez-vous d'inclure les données requises dans le corps de la requête au format JSON.

## Contribuer

Si vous souhaitez contribuer à ce projet, n'hésitez pas à créer une demande de tirage (pull request) avec vos modifications.
