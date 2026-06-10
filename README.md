# 🚀 Laravel SaaS CRM

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Laravel](https://img.shields.io/badge/Laravel-12-red)
![Status](https://img.shields.io/badge/status-active-success)
![PRs](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)

A production-ready **multi-tenant SaaS CRM platform** built with Laravel, designed for scalability, maintainability, and real-world business use cases.

---

## 🧠 Overview

This project simulates a real-world **SaaS CRM system** used by startups and companies to manage customers, support tickets, and internal tasks.

It is designed with a strong focus on:

* Clean architecture
* Modular structure
* API-first development
* Scalability

Each organization (tenant) has isolated data, users, and permissions.

---

## 🎯 Key Features

* 🏢 Multi-Tenancy (tenant-based architecture)
* 🔐 Authentication (Sanctum / JWT)
* 👥 Role & Permission Management (RBAC)
* 🎫 Ticketing System
* ✅ Task Management
* 🔗 RESTful API
* ⚙️ Modular & scalable codebase
* 🧪 Testing-ready (PHPUnit)
* 🐳 Docker support

---

## 🏗️ Architecture

The project follows a **modular and service-oriented architecture**:

```
app/
├── Actions/
├── Services/
├── Models/
├── Policies/
├── Modules/
routes/
├── api.php
├── web.php
```

### Principles:

* Separation of concerns
* SOLID principles
* API-first design
* Maintainable and extensible structure

---

## ⚙️ Tech Stack

* **Backend:** Laravel 12, PHP 8+
* **Database:** MySQL
* **Auth:** Laravel Sanctum / JWT
* **Authorization:** Spatie Laravel Permission
* **API:** RESTful
* **DevOps:** Docker, GitHub Actions (planned)
* **Testing:** PHPUnit

---

## 📦 Modules

* User Management
* Role & Permission System
* Ticket System
* Task Management
* Tenant (Organization) Management

---

## 🚧 Project Status

> ⚠️ Under active development

### Roadmap:

* Notifications system
* Activity logs
* Advanced reporting
* Billing & subscriptions (Stripe)
* API rate limiting
* Webhooks

---

## 🚀 Getting Started

### Prerequisites

* PHP 8+
* Composer
* MySQL
* Docker (optional)

---

### Installation

```bash
git clone https://github.com/ahmadjamshidi19/laravel-saas-crm.git

cd laravel-saas-crm

composer install

cp .env.example .env

php artisan key:generate

php artisan migrate

php artisan serve
```

---

### Run with Docker

```bash
docker-compose up -d --build
```

---

## 📡 API Example

```
GET    /api/tickets
POST   /api/tasks
GET    /api/users
```

---

## 🧪 Testing

```bash
php artisan test
```

---

## 💡 Use Cases

* SaaS startups
* Internal company CRM systems
* Customer support platforms
* Project & task management tools

---

## 📸 Screenshots

> Coming soon...

---

## 👨‍💻 Author

Ahmad Jamshidi
Full-Stack Developer

* LinkedIn: https://www.linkedin.com/in/ahmadjamshidi19
* Email: [ahmadjamshidi19@gmail.com](mailto:ahmadjamshidi19@gmail.com)

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.
