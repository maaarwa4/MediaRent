<div align="center">

# 🎬 MediaRent

**Plateforme de location de matériel audiovisuel professionnel**

`Laravel 12` · `Livewire` · `Tailwind CSS` · `Alpine.js` · `MySQL`

</div>

---

## 📌 Présentation

MediaRent met en relation des **propriétaires** de matériel audiovisuel (caméras, éclairage, son…) et des **clients** qui souhaitent le louer.
La plateforme fonctionne en **double face** : chaque profil dispose de son propre espace, et un back-office permet à l'administrateur de piloter l'activité.

---

## 👥 Profils et fonctionnalités

### 🧑‍💼 Propriétaire
- Publication d'annonces de matériel, avec photos et localisation
- Gestion des **disponibilités** et activation / désactivation des annonces
- Suivi des réservations reçues
- Option **annonce premium** pour gagner en visibilité

### 🙋 Client
- **Recherche avancée** avec filtres et **carte interactive**
- Réservation de matériel et suivi de ses locations
- Notifications et réclamations
- Évaluation des propriétaires et du matériel loué

### 🛡️ Administrateur
- **Tableau de bord** avec indicateurs et graphiques
- Modération des annonces, des utilisateurs, des réservations et des évaluations
- **Export des données** au format CSV

---

## ⚙️ Règles métier

- ⭐ **Évaluation mutuelle** : propriétaires et clients s'évaluent après une location
- 📅 Contrôle des dates de réservation : pas de date passée, date de fin postérieure au début
- 🗓️ Disponibilités du matériel gérées par le propriétaire
- 💎 Les annonces premium sont mises en avant dans les résultats
- 🚚 Gestion des livraisons associées aux réservations

---

## 🛠️ Stack technique

| Couche | Technologie |
|---|---|
| Backend | PHP 8.2, Laravel 12, Livewire 3 |
| Frontend | Blade, Tailwind CSS, Alpine.js, Vite |
| Base de données | MySQL |
| Cartographie | Leaflet, OpenStreetMap |
| Visualisation | Chart.js |

---

## 📁 Structure du projet

```
MediaRent/
├── app/
│   ├── Http/Controllers/   # Contrôleurs (Admin, Client, Propriétaire, Auth)
│   └── Models/             # Annonce, Objet, Reservation, Evaluation, Livraison…
├── database/
│   └── migrations/         # Schéma de la base de données
├── resources/views/        # Vues Blade
├── routes/                 # Routes web
└── public/                 # Ressources publiques
```

---

## 🚀 Installation

**Prérequis :** PHP 8.2+, Composer, Node.js et MySQL

```bash
# 1. Cloner le dépôt
git clone https://github.com/maaarwa4/MediaRent.git
cd MediaRent

# 2. Installer les dépendances
composer install
npm install

# 3. Configurer l'environnement
cp .env.example .env    # puis renseigner les accès à la base de données
php artisan key:generate

# 4. Créer la base de données
php artisan migrate

# 5. Compiler les ressources et lancer l'application
npm run build
php artisan serve
```


---

<div align="center">

Réalisé par **Marwa BOUNOUA** · [LinkedIn](https://linkedin.com/in/marwa-bounoua-877300263) · [GitHub](https://github.com/maaarwa4)

</div>
