# Todo List API

A simple RESTful API for managing a Todo List built with Laravel. This application supports user authentication and provides CRUD operations for tasks.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Setup Instructions](#setup-instructions)
- [API Endpoints](#api-endpoints)
- [Testing the API](#testing-the-api)
- [Considerations](#considerations)

## Features

- User authentication with token-based access.
- CRUD operations for managing tasks:
  - Create a task.
  - Retrieve all tasks or a specific task.
  - Update tasks.
  - Delete tasks.

## Technologies

- **Laravel**: The PHP framework for the application.
- **PHP**: The programming language.
- **MySQL**: The database used for storing tasks and users.
- **Laravel Sanctum**: For authentication.
- **Postman**: For testing the API.

## Setup Instructions

### Prerequisites

Make sure you have the following installed on your system:

- PHP 8.x or higher
- Composer
- MySQL

### Installation Steps

1. **Clone the Repository**

   Open your terminal and run:

   ```bash
   git clone https://github.com/yourusername/todo-api.git
   cd todo-api

2. Install Composer Dependencies
   composer install
   
4. Set Up Environment Variables
   cp .env.example .env
   
6. Update the .env file with your database credentials:
   DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=test
DB_USERNAME=root

7. Run Migrations
   php artisan migrate

7.Install Laravel Sanctum
    Install Laravel Sanctum
    
8. Publish the Sanctum configuration:
    php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"
    php artisan migrate
   
10. Start the Laravel Development Server
    php artisan serve
