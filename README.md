
<p align="center">
  <a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a>
</p>

<p align="center">
  <a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
  <a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

# ⚡ **Electro** - Plateforme E-commerce

**Développée par Abdelfattah Hayeb**  
Une plateforme de commerce électronique spécialisée dans la vente de produits électroniques, construite avec **Laravel**, **React**, et **MySQL**.

---

## 🚀 **Fonctionnalités**

- **Catalogue Produit**  
  Parcourez une sélection de produits électroniques avec des descriptions, prix et spécifications.

- **Panier d'Achat**  
  Ajoutez des articles, ajustez les quantités et gérez vos commandes.

- **Gestion Utilisateur**  
  Inscription, authentification et gestion des comptes utilisateurs.

- **Administration**  
  Interface pour administrer les produits, gérer les commandes et surveiller les ventes.

---

## 📂 **Structure du Projet**

### 🛠 **Backend (Laravel)**  
Gère les APIs, les bases de données, et la logique métier.

#### Répertoires importants :
```
backend/
├── app/                # Contrôleurs, modèles, et logique
├── config/             # Configuration des services
├── database/           # Migrations et seeders
├── routes/             # Routes API
└── .env                # Configuration d'environnement
```

---

## 🖥 **Prérequis**

Assurez-vous d'avoir installé :

- [PHP 8.1+](https://www.php.net/)
- [Composer](https://getcomposer.org/)
- [Node.js & npm](https://nodejs.org/)
- [MySQL](https://www.mysql.com/)

---

## ⚙️ **Installation**

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/abdelfattah-hayeb/electro.git
   cd electro
   ```

2. Installez les dépendances backend :
   ```bash
   cd backend
   composer install
   ```

3. Configurez l'environnement :
   ```bash
   cp .env.example .env
   ```

   Modifiez `.env` pour inclure vos informations MySQL.

4. Exécutez les migrations :
   ```bash
   php artisan migrate
   ```

5. Lancez le serveur backend :
   ```bash
   php artisan serve
   ```

6. (Optionnel) Configurez le frontend en React pour une interface utilisateur moderne.

---

## 🌟 **Utilisation**

- Accédez au backend via `http://localhost:8000`.
- Connectez-vous ou inscrivez-vous pour utiliser les fonctionnalités de la plateforme.

---

## 📊 **Points de Terminaison API**

### 🔐 Authentification
- `POST /api/register` : Inscription d'un utilisateur.
- `POST /api/login` : Connexion.

### 🛒 Panier d'achat
- `GET /api/cart` : Voir le panier.
- `POST /api/cart` : Ajouter un produit.
- `DELETE /api/cart/{id}` : Supprimer un produit.

### 📦 Commandes
- `GET /api/orders` : Récupérer les commandes.
- `POST /api/orders` : Créer une commande.

---

## 🛠 **Technologies Utilisées**

| **Technologie** | **Description**                          |
|------------------|------------------------------------------|
| **Laravel**      | Framework backend robuste pour API REST |
| **MySQL**        | Base de données relationnelle           |
| **React**        | Framework frontend pour l'interface UI  |

---

## 🤝 **Contribuer**

Les contributions sont les bienvenues ! Pour contribuer :

1. **Forkez ce projet.**
2. Créez une branche dédiée :  
   ```bash
   git checkout -b feature/nouvelle-fonctionnalite
   ```
3. Validez vos modifications :  
   ```bash
   git commit -m "Ajout d'une nouvelle fonctionnalité"
   ```
4. Poussez la branche :  
   ```bash
   git push origin feature/nouvelle-fonctionnalite
   ```
5. Créez une pull request.

---

## 📞 **Contact**

Pour toute question ou suggestion, contactez-moi :

- **Abdelfattah Hayeb**  
- ✉️ Email : cvnm0061@gmail.com  
- 📞 Téléphone : +212 6 23 34 93 06  
- 💼 LinkedIn : [Abdelfattah Hayeb](https://www.linkedin.com/in/abdelfattah-hayeb-195914311)

---

## 📜 **Licence**

Ce projet est sous licence **MIT**.  
Consultez le fichier `LICENSE` pour plus d'informations.
