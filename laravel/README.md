# Travel_app_Back-End

This repository contains the backend code for the Travel_app project. The backend is developed using Laravel, a PHP framework.

## Summary

The Travel_app backend provides a robust and efficient API to serve comprehensive information to travelers about their destination countries. This ensures users are well-informed and prepared for their journeys.

## Structure

The repository contains the following:

1. **Laravel Project Folder**: This folder contains all the necessary files and directories for the Laravel application.
2. **Database File**: `mark_laravel.sql` - This file contains the SQL schema and initial data for the application's database.

## Technologies Used

- **Laravel**: PHP framework for web application development.
- **PHP**: Server-side scripting language.
- **MySQL**: Relational database management system.

## Installation

### Prerequisites

- PHP: Version 7.3 or higher
- Composer: Dependency manager for PHP
- MySQL: Database system

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/Travel_app_Back-End.git
   cd Travel_app_Back-End
   ```

2. **Navigate to the Laravel project folder:**

   ```bash
   cd laravel
   ```

3. **Install PHP dependencies:**

   ```bash
   composer install
   ```

4. **Set up environment variables:**

   Copy the `.env.example` file to `.env` and update the necessary environment variables, including the database configuration.

   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

5. **Import the database:**

   Import the `mark_laravel.sql` file into your MySQL database.

   ```bash
   mysql -u yourusername -p yourpassword yourdatabase < ../mark_laravel.sql
   ```

6. **Run database migrations (if needed):**

   Ensure your database is configured correctly in the `.env` file, then run:

   ```bash
   php artisan migrate
   ```

7. **Serve the backend:**

   ```bash
   php artisan serve
   ```

## Usage

Once the backend is set up and running, it will provide API endpoints that can be consumed by the Travel_app frontend to fetch and display information about different countries.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request for any changes you'd like to make.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or suggestions, please contact:

- Your Name: [Nada El-Torgoman](mailto:nada.khalid.eltorgoman@gmail.com)
- GitHub: [Nada Eltorgoman](https://github.com/nadaeltorgoman)

---



<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the Laravel [Patreon page](https://patreon.com/taylorotwell).

### Premium Partners

- **[Vehikl](https://vehikl.com/)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Cubet Techno Labs](https://cubettech.com)**
- **[Cyber-Duck](https://cyber-duck.co.uk)**
- **[Many](https://www.many.co.uk)**
- **[Webdock, Fast VPS Hosting](https://www.webdock.io/en)**
- **[DevSquad](https://devsquad.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel/)**
- **[OP.GG](https://op.gg)**
- **[CMS Max](https://www.cmsmax.com/)**
- **[WebReinvent](https://webreinvent.com/?utm_source=laravel&utm_medium=github&utm_campaign=patreon-sponsors)**
- **[Lendio](https://lendio.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

Thank you for contributing to the Travel_app_Back-End!
