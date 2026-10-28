# ln-jormungandr-api

Backend API for Jormungandr, built with [Laravel 13](https://laravel.com/docs).

## Requirements

- PHP 8.3 or newer
- [Composer](https://getcomposer.org)
- Node.js and npm

The default database is SQLite, so no database server is needed for local development.

## Installation

```bash
git clone https://github.com/Besika40k/ln-jormungandr-api.git
cd ln-jormungandr-api
composer run setup
```

`composer run setup` installs the PHP and npm dependencies, creates `.env` from `.env.example`, generates the app key, runs the database migrations and builds the frontend assets.

## Running locally

```bash
composer run dev
```

## Running tests

```bash
php artisan test
```

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE).
