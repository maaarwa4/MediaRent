<a href="https://github.com/maaarwa4">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:F97316,50:EC4899,100:9333EA&height=190&section=header&text=MediaRent&fontSize=56&fontColor=ffffff&fontAlignY=36&desc=Professional%20audiovisual%20equipment%20rental%20marketplace&descSize=16&descAlignY=60&animation=fadeIn" alt="MediaRent" />
</a>

<div align="center">

<a href="https://laravel.com"><img src="https://img.shields.io/badge/Laravel_12-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel" /></a>
<a href="https://livewire.laravel.com"><img src="https://img.shields.io/badge/Livewire_3-4E56A6?style=for-the-badge&logo=livewire&logoColor=white" alt="Livewire" /></a>
<a href="https://tailwindcss.com"><img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" /></a>
<a href="https://alpinejs.dev"><img src="https://img.shields.io/badge/Alpine.js-8BC0D0?style=for-the-badge&logo=alpinedotjs&logoColor=black" alt="Alpine.js" /></a>
<a href="https://www.mysql.com"><img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" /></a>

</div>

<br>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Light%20Bulb.png" width="32" align="center" />&nbsp; Overview</h2>

MediaRent connects **owners** of professional audiovisual equipment (cameras, lighting, sound…) with **clients** who want to rent it.
The platform is **two-sided**: each profile has its own dedicated space, while a back office lets the administrator oversee the whole activity.

<br>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Gear.png" width="32" align="center" />&nbsp; Features by Profile</h2>

<table>
<tr>
<td width="33%" valign="top">

**Owner**

- Publish equipment listings with photos and location
- Manage **availability** and enable / disable listings
- Track incoming bookings
- **Premium listings** for more visibility

</td>
<td width="33%" valign="top">

**Client**

- **Advanced search** with filters and an **interactive map**
- Book equipment and track rentals
- Notifications and complaints
- Rate owners and rented equipment

</td>
<td width="34%" valign="top">

**Administrator**

- **Dashboard** with KPIs and charts
- Moderation of listings, users, bookings and reviews
- **CSV data export**

</td>
</tr>
</table>

<br>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Briefcase.png" width="32" align="center" />&nbsp; Business Rules</h2>

- **Mutual reviews**: owners and clients rate each other after a rental
- **Booking date validation**: no past dates, end date after start date
- Equipment **availability** managed by the owner
- **Premium listings** ranked first in search results
- **Delivery** management linked to bookings

<br>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Laptop.png" width="32" align="center" />&nbsp; Tech Stack</h2>

| Layer | Technology |
|:---|:---|
| Backend | PHP 8.2 · Laravel 12 · Livewire 3 |
| Frontend | Blade · Tailwind CSS · Alpine.js · Vite |
| Database | MySQL |
| Maps | Leaflet · OpenStreetMap |
| Charts | Chart.js |

```
MediaRent/
├── app/
│   ├── Http/Controllers/   # Admin, Client, Owner and Auth controllers
│   └── Models/             # Annonce, Objet, Reservation, Evaluation, Livraison…
├── database/migrations/    # Database schema
├── resources/views/        # Blade views
├── routes/                 # Web routes
└── public/                 # Public assets
```

<br>

<h2><img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png" width="32" align="center" />&nbsp; Getting Started</h2>

**Prerequisites:** PHP 8.2+, Composer, Node.js and MySQL

```bash
# 1. Clone the repository
git clone https://github.com/maaarwa4/MediaRent.git
cd MediaRent

# 2. Install dependencies
composer install
npm install

# 3. Configure the environment
cp .env.example .env    # then fill in your database credentials
php artisan key:generate

# 4. Create the database schema
php artisan migrate

# 5. Build assets and run the app
npm run build
php artisan serve
```

<br>

<div align="center">

Built by **Marwa Bounoua**

<a href="https://linkedin.com/in/marwa-bounoua-877300263"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://github.com/maaarwa4"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>

</div>

<a href="https://github.com/maaarwa4">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:F97316,50:EC4899,100:9333EA&height=100&section=footer" alt="" />
</a>
