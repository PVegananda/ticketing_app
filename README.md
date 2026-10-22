<p align="center">
  <img src="public/ticketing-logo.svg" alt="Ticketing App logo" width="180">
</p>

<h1 align="center">Ticketing App</h1>

<p align="center">
  A clean and reliable foundation for managing support tickets and customer requests.
</p>

<p align="center">
  <a href="https://github.com/PVegananda/ticketing_app">
    <img src="https://img.shields.io/badge/status-in%20development-f59e0b?style=for-the-badge" alt="Project status: in development">
  </a>
  <a href="https://www.php.net/releases/8.3/en.php">
    <img src="https://img.shields.io/badge/PHP-8.3%2B-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP 8.3 or newer">
  </a>
  <a href="https://laravel.com">
    <img src="https://img.shields.io/badge/Laravel-13.x-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel 13">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/license-MIT-22C55E?style=for-the-badge" alt="MIT license">
  </a>
</p>

## About the project

Ticketing App is a Laravel-based application for organizing support requests in one place. It is being built with a focus on a simple workflow, clear communication, and a maintainable codebase.

This repository currently provides the application foundation and development setup. Features will be added as the project grows.

## Tech stack

- **Backend:** PHP 8.3+ and Laravel 13
- **Frontend tooling:** Vite, Tailwind CSS, and JavaScript
- **Database:** SQLite by default (MySQL and PostgreSQL can be configured)
- **Testing:** PHPUnit and Laravel's testing utilities

## Getting started

### Requirements

Make sure the following tools are installed:

- PHP 8.3 or newer
- Composer
- Node.js and npm

### Installation

1. Clone the repository and move into the project directory:

   ```bash
   git clone https://github.com/PVegananda/ticketing_app.git
   cd ticketing_app
   ```

2. Run the setup script:

   ```bash
   composer run setup
   ```

3. Start the local development environment:

   ```bash
   composer run dev
   ```

4. Open [http://localhost:8000](http://localhost:8000) in your browser.

### Useful commands

```bash
# Run the test suite
composer test

# Build frontend assets for production
npm run build

# Run the development asset server
npm run dev
```

## Project structure

```text
app/          Application code
database/     Migrations, factories, and seeders
public/       Public entry point and static assets
resources/    Frontend assets and Blade views
routes/       Web and console routes
tests/        Feature and unit tests
```

## Contributing

Contributions are welcome! If you have an idea, find a bug, or want to improve the project:

1. Open an issue to discuss the change.
2. Create a focused branch for your work.
3. Add or update tests where appropriate.
4. Open a pull request with a clear description of your changes.

Thanks for helping make Ticketing App better.

## License

Ticketing App is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
