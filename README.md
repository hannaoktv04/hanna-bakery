
# HannaBakery

HannaBakery is a web-based bakery application developed using the Laravel framework. This project aims to provide a platform for managing bakery products and supporting bakery-related activities through a web application.

## Features

- Bakery product management
- User authentication
- Product catalog
- Responsive web interface
- PDF document generation
- Interactive notifications and alerts

## Tech Stack

**Backend**
- PHP
- Laravel 8

**Frontend**
- HTML
- CSS
- JavaScript
- Laravel UI
- Livewire 2

**Database**
- MySQL

**Libraries & Packages**
- Laravel Sanctum
- Laravel DomPDF
- SweetAlert
- Laravel Livewire

## Requirements

Make sure you have installed:

- PHP >= 7.3
- Composer
- MySQL
- Node.js and NPM

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/YOUR_USERNAME/hanna-bakery.git
   ```

2. Navigate to the project directory:

   ```bash
   cd hanna-bakery
   ```

3. Install PHP dependencies:

   ```bash
   composer install
   ```

4. Copy the environment file:

   ```bash
   cp .env.example .env
   ```

5. Generate application key:

   ```bash
   php artisan key:generate
   ```

6. Configure your database connection in the `.env` file.

7. Run database migrations:

   ```bash
   php artisan migrate
   ```

8. Install frontend dependencies:

   ```bash
   npm install
   ```

9. Compile frontend assets:

   ```bash
   npm run dev
   ```

10. Start the Laravel development server:

    ```bash
    php artisan serve
    ```

11. Open the application:

    http://127.0.0.1:8000

## Project Structure

```text
hanna-bakery/
├── app/
├── bootstrap/
├── config/
├── database/
├── public/
├── resources/
├── routes/
├── storage/
├── tests/
├── .env.example
├── artisan
├── composer.json
└── README.md
```

## License

This project uses the MIT license inherited from the Laravel project configuration.
