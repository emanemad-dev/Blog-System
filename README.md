# Laravel Blog CMS

This is a simple blog content management system (CMS) built with Laravel. The application includes core blogging features like posts, categories, comments, user profiles, themes, and contact/subscriber functionality.

## Features

- Blog post management (create, update, delete)
- Categories for organizing posts
- Comment system for user interaction
- Contact form for user messages
- Subscribe form for newsletter or updates
- Theme management (switch blog appearance)
- User profile management

## Technologies Used

- Laravel (PHP Framework)
- Blade Templating Engine
- MySQL Database
- RESTful structure using Laravel Controllers

## Folder Structure (Controllers)

```
app/Http/Controllers/V4/
├── AuthController.php
├── BlogController.php
├── CategoryController.php
├── CommentController.php
├── ContactController.php
├── Controller.php
├── ProfileController.php
├── SubscriberController.php
└── ThemeController.php
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Install PHP dependencies:

```bash
composer install
```

3. Copy the `.env` file and set your environment variables:

```bash
cp .env.example .env
php artisan key:generate
```

4. Configure your database credentials in `.env`, then run:

```bash
php artisan migrate
```

5. Run the development server:

```bash
php artisan serve
```

Visit `http://localhost:8000` in your browser.

## Usage

- Manage posts, categories, and comments from the admin panel (if implemented)
- Customize blog themes
- Handle contact messages and newsletter subscriptions

## License

This project is open-source and free to use under the MIT license.
