<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# 🎓 CED Doctoral Process Management – Laravel Web App


This project is a Laravel-based web application developed to manage the doctoral process lifecycle for the **Centre des Études Doctorales (C.E.D.)** at the Université Cadi Ayyad, Marrakech.

It offers an intuitive interface and a robust backend system for handling user registration, research structures, application forms, and doctoral student records.

---

## 📌 Table of Contents

- [Features](#️features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Author](#author)
- [License](#license)

---

## ✅ Features

- 👤 **User Management** (admin, staff, student roles)
- 🏛️ **Research Structures** creation and management
- 📄 **Pre-registration Forms** with validation
- 📁 **Doctoral Dossier** submission and tracking
- 🔐 **Secure Authentication** (Laravel Auth / Sanctum)
- 🗃️ **Database Integration** (PostgreSQL or MySQL)
- 🧾 **Admin Dashboard** for record monitoring

---

## 🧰 Technologies Used

- **Backend Framework:** Laravel 10.x (PHP)
- **Frontend:** Blade templates, HTML5, CSS3, Bootstrap
- **Database:** PostgreSQL or MySQL
- **Authentication:** Laravel Auth / Laravel Breeze
- **Developer Tools:** Artisan CLI, Laravel Debugbar, Laravel Tinker

---

## ⚙️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/ced-doctoral-process-management.git
cd ced-doctoral-process-management

# 2. Install dependencies
composer install
npm install && npm run dev

# 3. Copy .env and configure
cp .env.example .env
php artisan key:generate

# 4. Configure your DB credentials in .env

# 5. Run migrations
php artisan migrate

# 6. Launch the dev server
php artisan serve


