# Laravel 11 CRUD Application with MongoDB

[![Laravel](https://img.shields.io/badge/Laravel-11-red.svg)](https://laravel.com)
[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
![Status](https://img.shields.io/badge/status-active-brightgreen)

A simple CRUD web application built using **Laravel 11** and **MongoDB**, demonstrating basic Create, Read, Update, and Delete functionality using the `jenssegers/mongodb` driver.

---
## 🚀 Features

- CRUD (Create, Read, Update, Delete)
- MongoDB integration with Eloquent-style models
- Blade templating
- Request validation
- Laravel 11 routing and structure

---

## 🛠️ Setup Instructions

```bash
git clone https://github.com/Inc-cryp/Laravel-11-CRUD-Application-with-Mongodb.git
cd Laravel-11-CRUD-Application-with-Mongodb

composer install
npm install

cp .env.example .env
php artisan key:generate

Update .env to connect MongoDB:

DB_CONNECTION=mongodb
DB_HOST=127.0.0.1
DB_PORT=27017
DB_DATABASE=your_db
DB_USERNAME=
DB_PASSWORD=

php artisan serve
```
---
## 📦 Used Packages
jenssegers/laravel-mongodb
