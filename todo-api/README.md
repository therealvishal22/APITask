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
  - Read tasks (list and individual).
  - Update tasks.
  - Delete tasks.

## Technologies

- Laravel
- PHP
- MySQL
- Laravel Sanctum for authentication
- Postman (for testing)

## Setup Instructions

- Install/Update a composer
- Migrate 
- Install composer require laravel/sanctum package
- publish package using 'php artisan vendor:publish --provider="Laravel\Sanctum\SanctumServiceProvider"'
- Run the Php artisan serve command

### Prerequisites

- PHP 8.x
- Composer
- MySQL
- Node.js (optional, if you plan to use frontend)

### Installation Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/todo-api.git
   cd todo-api
