# SirinNabat

A pharmacy management system built with Laravel for managing medicines, sales, employees, and storage operations.

## Features

- **Medicine Management**: Add, edit, and manage medicine inventory
- **Sales Management**: Track retail and wholesale sales with customer information
- **Employee Management**: Manage pharmacy staff and roles
- **Storage Management**: Track medicine storage locations and transfers
- **Wholesale Operations**: Manage wholesale sales and storage
- **Multi-language Support**: Available in English, Russian, and Turkmen

## Requirements

- PHP >= 8.1
- Composer
- MySQL/MariaDB
- Node.js & NPM

## Installation

1. Clone the repository:
```bash
git clone https://github.com/kurban-4/SirinNabat.git
cd SirinNabat
```

2. Install dependencies:
```bash
composer install
npm install
```

3. Copy environment file:
```bash
cp .env.example .env
```

4. Generate application key:
```bash
php artisan key:generate
```

5. Configure your database in `.env` file

6. Run migrations:
```bash
php artisan migrate
```

7. Seed the database (optional):
```bash
php artisan db:seed
```

8. Build assets:
```bash
npm run build
```

9. Start the development server:
```bash
php artisan serve
```

## Usage

Access the application at `http://localhost:8000`

## License

This project is open-sourced software licensed under the MIT license.
