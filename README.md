# Photographer Portfolio (Laravel)

A four-page photographer portfolio built with Laravel to practice routes,
controllers, Blade layouts, and looping over data for a photo gallery.

## Pages

- Home
- About (bio, skills, services)
- Gallery
- Contact

## Built With

- PHP
- Laravel
- Blade
- CSS

## Requirements

- PHP 8.2 or higher
- Composer
- Node.js and npm (only if using Vite)

## Installation

1. Clone the repository
   git clone https://github.com/Samiullah-Popalzai/photographer-portfolio.git
   cd photographer-portfolio

2. Install dependencies
   composer install
   npm install

3. Set up the environment
   copy .env.example .env
   php artisan key:generate

4. Run the app
   php artisan serve
   npm run dev

5. Open http://127.0.0.1:8000

## What I Learned

- Named routes and a single PageController
- Shared Blade layout with navigation
- Storing content in PHP arrays and looping with @foreach / @forelse
- Serving images from the public folder

## Author

Samiullah Popalzai