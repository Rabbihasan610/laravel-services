# Laravel Service Generator

A Laravel package to generate a full CRUD service module automatically
using a single artisan command.

## Features

-   Auto-generate Models, Migrations, Controllers, Views, Routes
-   Structured Admin module setup
-   Ready-to-use CRUD scaffolding

## Installation

### Clone the package

    mkdir packages
    cd packages
    git clone https://github.com/Rabbihasan610/laravel-services.git

### Add to composer.json

    "repositories": [
        {
            "type": "path",
            "url": "packages/laravel-services/rabbihasan/laravel-service"
        }
    ]

### Require package

    composer require rabbihasan/laravel-service:@dev

## Usage

    php artisan service:make Product

## Generated Structure

-   Models: Product, ProductList, ProductForm
-   Controllers
-   Migrations
-   Views
-   Routes

## Requirements

-   Laravel project
-   routes/admin.php file
-   php-zip extension

## Author

Rabbihasan
