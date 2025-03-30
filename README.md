# Laravel 11 + React SPA Project
A simple yet functional project management application developed using Laravel 11 for the backend and React for the frontend.

## Features
1. User registration and authentication
2. Complete project management (create, read, update, delete) with sorting, filtering, and pagination
3. Comprehensive task management with the same capabilities
4. Ability to add tasks within specific projects
5. Option to view all tasks or filter by project
6. Assign users to designated tasks
7. View tasks assigned to the currently logged-in user
8. Dashboard displaying key project and task metrics

## Installation
1. Clone the repository
2. Open a terminal and navigate to the project directory
3. Copy the environment configuration file: cp .env.example .env
4. Install PHP dependencies: composer install
5. Install frontend dependencies: npm install
6. Generate the application key: php artisan key:generate --ansi
7. Run database migrations and seed initial data: php artisan migrate --seed
8. Start the Vite development server: npm run dev
9. Launch the Laravel development server: php artisan serve
