<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>


## Library App
A Laravel 10/11 web application for managing books and categories with authentication, CRUD operations, filtering, pagination, and ownership-based authorization.

## 🔧 Features
-User Authentication (Register / Login / Logout) <br>
-CRUD operations for Books<br>
-CRUD operations for Categories<br>
-Many-to-Many relationship between Books and Categories<br>
-Search, category filtering, and sorting<br>
-Pagination (5 items per page)<br>
-Ownership Policy (users can edit/delete only their own books)<br>
-Form validation and flash messages<br>

## 🛠 Tech Stack
-Laravel 10/11<br>
-PHP 8.2+<br>
-MySQL 8<br>
-Blade Templates<br>
-Eloquent ORM<br>

## 📚 Database Structure
-Users → Books (1:N)<br>
-Books ↔ Categories (N:N) via pivot table<br>

## ⚙️ Installation Guide

Follow these steps to run the project locally: <br>

1. Clone the repository<br>
   git clone https://github.com/'your-username'/first-app-fixing.git<br>
   cd first-app-fixing<br>

2. Install dependencies<br>
   composer install<br>

3. Copy environment file<br>
   cp .env.example .env<br>

4. Configure your database (.env file)<br>
   DB_DATABASE=your_db_name<br>
   DB_USERNAME=your_username<br>
   DB_PASSWORD=your_password<br>

5. Generate application key<br>
   php artisan key:generate<br>

6. Run migrations<br>
   php artisan migrate<br>

   (Optional)<br>
   php artisan db:seed<br>

7. Start the server<br>
   php artisan serve<br>

8. Open in browser<br>
   [http://127.0.0.1:8000](http://127.0.0.1:8000 (or http://localhost:8000))<br>

Thank you for checking out this project.<br>
Feedback and suggestions are always welcome.<br>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

You may also try the [Laravel Bootcamp](https://bootcamp.laravel.com), where you will be guided through building a modern Laravel application from scratch.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 2000 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.
