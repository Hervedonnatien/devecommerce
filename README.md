
```
$ cd ecommerce
```

### 1. Setup MongoDB

- Local MongoDB
  - (https://www.mongodb.com/try/download/community)
  - Créer un fichier .env dans le dossier du projet
   
- Atlas Cloud MongoDB
  - Créer DB sur [https://cloud.mongodb.com](https://cloud.mongodb.com)
  - Créer un fichier .env dans le dossier du projet
  

### 2. Run Backend

```
$ npm install
$ npm start
```

### 3. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm start
```

### 4. Seed Users and Products

- Taper sur chrome: http://localhost:5000/api/users/seed
- ça va retourner l'email et le mot de passe de l'Admin
- Taper sur chrome: http://localhost:5000/api/products/seed
- ça va créer 6 nouveaux produits

### 5. Admin Login

- Run http://localhost:3000/signin
- Entrer Email & mot de passe

