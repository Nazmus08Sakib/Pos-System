# Laravel POS System 🚀  

A **Point of Sale (POS) System** built with **Laravel Jetstream, Livewire, and AdminLTE** for managing products, cart, and checkout functionality.

## Features 🎯
- 🔐 **Authentication** (Admin & Cashier roles)
- 📦 **Product Management** (CRUD with multi-step form)
- 🛒 **Cart Management** (Session-based)
- 💰 **Checkout System** (Subtotal, Discount, Tax Calculation)
- 🎨 **AdminLTE Integration** (Styled UI)
- 📊 **Yajra DataTables** (For product listing)

---

## Installation 🛠️

### 1️⃣ Clone the Repository  
```sh
git clone https://github.com/yourusername/laravel-pos-system.git
cd laravel-pos-system
2️⃣ Install Dependencies
sh
Copy
Edit
composer install
npm install && npm run dev
3️⃣ Configure .env File
Copy .env.example to .env and update database credentials:

ini
Copy
Edit
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=pos_system
DB_USERNAME=root
DB_PASSWORD=
4️⃣ Run Migrations & Seed Database
sh
Copy
Edit
php artisan migrate --seed
5️⃣ Install Laravel Jetstream
sh
Copy
Edit
php artisan jetstream:install livewire
npm run dev
6️⃣ Serve the Application
sh
Copy
Edit
php artisan serve
Visit: http://127.0.0.1:8000

Usage 🚀
🏗️ Admin Panel
Login as Admin
Manage Products (Create, Read, Update, Delete)
Track Sales & Orders
🛒 POS System
Click a product to add to cart
Adjust quantity using + or - buttons
Click Pay to complete the order
Technologies Used 🛠️
Laravel 10 + Jetstream + Livewire
MySQL (Database)
Bootstrap & AdminLTE
JavaScript (Session-based cart)
License 📜
This project is licensed under the MIT License.

Contributors 💡
Your Name (@yourgithub)
pgsql
Copy
Edit

Would you like to add **API integration** for order history? 🚀
