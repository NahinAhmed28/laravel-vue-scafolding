# Laravel Vue Scafolding

Laravel Vue Scafolding is a starter project combining a Laravel backend with a Vue front end.

## Features

- Full-stack Laravel + Vue scaffold
- Backend routing, controllers, and models
- Vue component/UI foundation
- Vite/npm asset build workflow

## Modules

- Backend module: Laravel routes, controllers, services, and models
- Frontend module: Vue components, pages, and assets
- Auth module: authentication flow when enabled
- Data module: migrations, seeders, and database persistence
- Build module: Composer, npm, Vite, and development scripts

## System Architecture

The project follows a full-stack Laravel architecture. Laravel handles backend routing, business logic, and persistence. Vue handles client-side UI components. Vite builds front-end assets and Laravel serves the application shell or API responses.

## Getting Started

```bash
git clone https://github.com/NahinAhmed28/laravel-vue-scafolding.git
cd laravel-vue-scafolding
composer install
cp .env.example .env
php artisan key:generate
npm install
npm run dev
php artisan serve
```
