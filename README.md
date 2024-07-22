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
   git clone https://github.com/nadaeltorgoman/Travel_app_Back-End.git
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

Thank you for contributing to the Travel_app_Back-End!
