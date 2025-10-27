## Laravel E-Commerce App  

A modern **E-Commerce Web Application** built with the **Laravel Framework**, designed to manage products, users, and transactions efficiently. This project demonstrates a scalable and maintainable architecture following Laravel’s MVC pattern, with authentication, product management, and order handling capabilities.  

## Features  

- **User Authentication** — Register, login, and manage accounts  
- **Product Management** — Add, update, delete, and list products  
- **Category Management** — Organize products into structured categories  
- **Inventory Control** — Track product stock and availability  
- **Order Handling** — Manage customer orders and transactions  
- **Admin Dashboard** — Manage users, products, and reports via an intuitive interface  

## Tech Stack  

| Layer | Technology |
|-------|-------------|
| Backend | Laravel 10+, PHP 8+ |
| Frontend | Blade Template, Bootstrap, JavaScript |
| Database | MySQL (see `vrnancommerce.sql`) |
| Package Management | Composer, npm |
| Build Tool | Laravel Mix / Vite |
| Testing | PHPUnit |


## Installation  

Follow these steps to set up the project locally:  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/laravel-ecommerce-app.git
   cd laravel-ecommerce-app
   ```

2. **Install dependencies**  
   ```bash
   composer install
   npm install
   ```

3. **Create a copy of `.env` file**  
   ```bash
   cp .env.example .env
   ```

4. **Configure environment variables**  
   - Set your database name, username, and password inside the `.env` file.  
   - Example:  
     ```
     DB_DATABASE=vrnancommerce
     DB_USERNAME=root
     DB_PASSWORD=
     ```

5. **Generate application key**  
   ```bash
   php artisan key:generate
   ```

6. **Import the database**  
   - Import the included SQL file `vrnancommerce.sql` into your MySQL server.  

7. **Run database migrations (optional)**  
   ```bash
   php artisan migrate
   ```

8. **Start the development server**  
   ```bash
   php artisan serve
   ```

## Developer Notes  

This project is a base for Laravel-based online stores.  
You can extend it by adding:  
- Payment gateway integration (Midtrans, Stripe, PayPal, etc.)  
- Product image gallery and upload system  
- Order tracking and customer invoices  
- API support for mobile applications  



