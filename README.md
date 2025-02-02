# Project Setup Instructions

Welcome to the Coalition Technologies Product Management project! Follow the instructions below to set up the application:

## Prerequisites

- Ensure you have [PHP](https://www.php.net/downloads) installed on your machine.
- Install [Composer](https://getcomposer.org/download/) for dependency management.
- Install a database management system (e.g., MySQL, PostgreSQL, SQLite).

## Configuration
Edit the .env file and set up your database details:

    DB_CONNECTION: The type of database you are using (mysql, pgsql, sqlite, etc.).
    DB_HOST: The database host (e.g., 127.0.0.1 or localhost).
    DB_PORT: The database port (e.g., 3306 for MySQL).
    DB_DATABASE: The name of your database.
    DB_USERNAME: The username for your database.
    DB_PASSWORD: The password for your database.
        Here's an example configuration for MySQL:

        plaintext
        Copy code
        DB_CONNECTION=mysql
        DB_HOST=127.0.0.1
        DB_PORT=3306
        DB_DATABASE=your-database-name
        DB_USERNAME=your-username
        DB_PASSWORD=your-pass

-composer install
-npm run dev
-php artisan migrate
-php artisan db:seed
-php artisan serve



Once you've seeded the database, you can log in to the application using the following credentials:

Email: testuser@gmail.com
Password: password




Congratulations! Your application should now be set up and ready to use.

Thank you for using this application!



#   n e w  
 