Project Management System

A modern Project Management System built with Laravel 11 and React.
This application helps teams organize projects, manage tasks, assign users, and track progress in a clean and user-friendly interface.

🚀 Features

Authentication & Authorization (Login, Registration, Roles)

Projects Management

Create, update, and delete projects

Assign users to projects

Task Management

Add tasks with priority & deadlines

Update progress (To-Do, In Progress, Done)

User Roles

Admin → manage users & projects

Manager → assign and track tasks

Member → work on assigned tasks

Dashboard with project overviews and task statistics

Responsive UI powered by React + Tailwind

🛠️ Tech Stack

Laravel 11 (Backend & App logic)

React 18 (Frontend components)

Vite (Bundler)

TailwindCSS (UI styling)

MySQL / PostgreSQL (Database)

📦 Installation
1. Clone the Repository
git clone https://github.com/your-username/project-management.git
cd project-management

2. Install Dependencies
composer install
npm install

3. Configure Environment
cp .env.example .env
php artisan key:generate


Update .env with your database credentials.

4. Run Database Migrations
php artisan migrate --seed

5. Start the Application

Run both Laravel and React together:

php artisan serve
npm run dev


Laravel available at: http://localhost:8000

React frontend compiled by Vite at: http://localhost:5173

📂 Project Structure
project-management/
├── app/            # Laravel backend logic
├── resources/js/   # React components
├── resources/views # Blade + Inertia views (if used)
├── routes/web.php  # Web routes
├── routes/api.php  # (Optional, if API routes exist)

🤝 Contributing

Fork the repo

Create your feature branch (git checkout -b feature/my-feature)

Commit your changes (git commit -m 'Add new feature')

Push to the branch (git push origin feature/my-feature)

Open a Pull Request

📜 License

This project is licensed under the MIT License.