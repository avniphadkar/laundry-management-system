# laundarty Management System 


## Technologies
    - PHP: This project requires PHP version 7.3 or higher.
    - composer installed on your machine
    - laravel/framework: Version 8.75 or higher.
    - laravel/sanctum: Version 2.14 or higher.
    - laravel/tinker: Version 2.5 or higher.
    - laravel/ui: Version 3.4 or higher.
    - spatie/laravel-permission: Version 5.5 or higher.

## User Types and Permissions

1. **Admin/Owner**
   - Access: `<url>/admin/login`
   - Manages articles, comments, categories, keywords, and other users (except Owner).

2. **Reader**
   - Reads and comments on articles with email addresses.
   - Subscribes to new articles.
   - Searches and navigates articles by categories.

## Installation

1. Clone: `git clone https://github.com/avniphadkar/lavavel-blog.git`
2. Install dependencies: `composer install`
3. Setup environment: Copy `.env.example` to `.env` and run `php artisan key: generate`.
4. Database: Create, configure `.env`, and run `php artisan migrate: fresh --seed`.
5. Start: `php artisan serve`
6. Access: Visit `localhost:8000`.

