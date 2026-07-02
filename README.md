<div align="center">

# 🛒 RTL Panel

### A full-stack, RTL-ready Laravel e-commerce platform with a complete admin dashboard, product catalog, cart, orders, and PayPal checkout.

<p>
  <img src="https://img.shields.io/github/license/morpheusadam/BazaarPanel?style=for-the-badge&color=4c1" alt="License" />
  <img src="https://img.shields.io/github/stars/morpheusadam/BazaarPanel?style=for-the-badge&color=ffca28" alt="Stars" />
  <img src="https://img.shields.io/github/forks/morpheusadam/BazaarPanel?style=for-the-badge&color=42a5f5" alt="Forks" />
  <img src="https://img.shields.io/github/last-commit/morpheusadam/BazaarPanel?style=for-the-badge&color=8e44ad" alt="Last commit" />
  <img src="https://img.shields.io/github/repo-size/morpheusadam/BazaarPanel?style=for-the-badge&color=e67e22" alt="Repo size" />
</p>

<p>
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel" />
  <img src="https://img.shields.io/badge/Bootstrap-4-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white" alt="Bootstrap" />
  <img src="https://img.shields.io/badge/Vue.js-2-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white" alt="Vue.js" />
  <img src="https://img.shields.io/badge/MySQL-Database-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/PayPal-Checkout-00457C?style=for-the-badge&logo=paypal&logoColor=white" alt="PayPal" />
</p>

</div>

---

## 📖 Overview

**RTL Panel** is a complete **Laravel e-commerce application** that ships with both a customer-facing storefront and a powerful **admin panel**. Built on Laravel with a Bootstrap 4 + Vue 2 front end, it delivers everything an online shop needs out of the box: products, brands, categories, a shopping cart, coupons, orders, shipping, product reviews, wishlists, and a built-in blog.

The project is designed to work cleanly in **right-to-left (RTL) layouts**, making it a great starting point for Persian, Arabic, and Hebrew online stores. Authentication, social login, real-time messaging, and PDF invoice generation are wired in, so developers can focus on customizing the shop rather than rebuilding the plumbing.

It is ideal for **web developers, agencies, and indie makers** who want a ready-made, extensible online store with a clean MVC structure and a modern admin dashboard.

> 🔎 **Keywords:** laravel ecommerce, rtl admin panel, laravel dashboard, online shop, shopping cart, paypal checkout, product catalog, php ecommerce template, bootstrap admin, vue laravel.

---

## ✨ Features

- 🛍️ **Full e-commerce flow** — products, brands, categories, cart, coupons, orders, and shipping.
- 🧑‍💼 **Admin dashboard** — manage catalog, banners, orders, users, and site settings from a dedicated backend.
- 💳 **PayPal checkout** — integrated payments via `srmklive/paypal`.
- 🔐 **Authentication & social login** — Laravel UI auth plus OAuth via Laravel Socialite.
- ⭐ **Reviews & wishlists** — customers can rate products and save favourites.
- 📰 **Built-in blog** — posts, categories, tags, and comments.
- 💬 **Real-time messaging & notifications** — powered by Pusher and Laravel Echo.
- 🧾 **PDF invoices** — generated with `barryvdh/laravel-dompdf`.
- 🖼️ **Media management** — image processing (Intervention Image) and a file manager (UniSharp).
- 📧 **Newsletter** — subscriber management via `spatie/laravel-newsletter`.
- 🌍 **RTL-friendly** — layouts suited to Persian, Arabic, and Hebrew stores.

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=laravel,php,mysql,bootstrap,vue,js" alt="Tech stack" />
</p>

| Layer | Technology |
| --- | --- |
| Framework | Laravel (PHP) |
| Front end | Blade, Bootstrap 4, Vue 2 |
| Build | Laravel Mix (webpack), Sass |
| Real-time | Pusher, Laravel Echo |
| Payments | PayPal (srmklive/paypal) |
| Media | Intervention Image, UniSharp File Manager |
| Auth | Laravel UI, Laravel Socialite, Sanctum |

---

## 🚀 Getting Started

### Prerequisites

- **PHP** with the required extensions (incl. `imagick` for image processing)
- **Composer**
- **Node.js & npm**
- **MySQL** (or another supported database)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/morpheusadam/BazaarPanel.git
cd rtl-panel

# 2. Install PHP and JS dependencies
composer install
npm install

# 3. Configure your environment
cp .env.example .env
php artisan key:generate

# 4. Set your database credentials in .env, then migrate & seed
php artisan migrate --seed

# 5. Link storage and build assets
php artisan storage:link
npm run dev

# 6. Serve the application
php artisan serve
```

Then open `http://127.0.0.1:8000` in your browser.

---

## ⚙️ Configuration

Set these values in your `.env` file:

- **Database** — `DB_*` connection settings.
- **PayPal** — sandbox/live credentials for checkout.
- **Pusher** — `PUSHER_*` keys for real-time messaging and notifications.
- **Mail** — SMTP settings for password resets and the newsletter.

---

## 🗂️ Project Structure

```text
rtl-panel/
├── app/
│   ├── Http/Controllers/   # Storefront & admin controllers
│   ├── Models/             # Product, Order, Cart, Post, User, ...
│   └── Notifications/       # Status & order notifications
├── public/
│   ├── backend/            # Admin panel assets
│   └── frontend/           # Storefront assets
├── resources/views/        # Blade templates
├── routes/                  # web.php / api.php
└── database/                # Migrations & seeders
```

---

## 🤝 Contributing

Contributions are welcome! Open an [issue](https://github.com/morpheusadam/BazaarPanel/issues) or submit a pull request with new features, fixes, or improvements.

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for details.

---

<div align="center">

### 👤 Author — Morpheus Adam

Web developer & cheerful hacker · PHP · Laravel · Go

<p>
  <a href="https://github.com/morpheusadam"><img src="https://img.shields.io/badge/GitHub-morpheusadam-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://sam.zeonic.me"><img src="https://img.shields.io/badge/Website-sam.zeonic.me-4c1?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
  <a href="mailto:morpheusadam95@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

⭐ **If this project helped you, consider giving it a star!** ⭐

</div>


---

## ⭐ Star History

<a href="https://star-history.com/#morpheusadam/BazaarPanel&Date">
  <img src="https://api.star-history.com/svg?repos=morpheusadam/BazaarPanel&type=Date" alt="rtl-panel — Star History Chart" width="70%" />
</a>

<div align="center">

### If this project helps you, please give it a ⭐

A star helps other developers discover **rtl-panel** and supports continued development.

</div>
