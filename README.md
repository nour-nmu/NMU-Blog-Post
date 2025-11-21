# NMU Blog Post

A blog website built with **PHP (Laravel)** and connected to a **database** for storing posts and user accounts.

---

## 📌 Features

- Add, edit, and delete blog posts  
- User authentication (login system)  
- Clean and responsive UI  
- Blade templates for rendering frontend views  
- Database integration for posts and user management  

---

## 🛠️ Tech Stack

- **Backend:** Laravel (PHP)  
- **Frontend:** Blade Templates  
- **Database:** MySQL / SQLite / PostgreSQL (any Laravel-supported DB)  
- **Tools:** Composer, Node.js + npm, Vite  

---

## 🚀 Getting Started

### 1. Prerequisites

Make sure you have:

- PHP >= 8.x  
- Composer  
- Node.js & npm  
- A database (MySQL recommended)

---

### 2. Installation

Clone the repository:

```bash
git clone https://github.com/nour-nmu/NMU-Blog-Post.git
cd NMU-Blog-Post
```

2. **Install backend dependencies:**
```bash
composer install
```

**Install frontend dependencies:**
```bash
npm install
```
3. Environment Setup

**Copy the example environment file:**
```bash
cp .env.example .env
```

Configure your **.env** file:

- Database name

- Username / password

- App URL

Generate your app key:
```
php artisan key:generate
```
4. Database Migration

Run migrations:
```
php artisan migrate
```

5. Running the App

Start the Laravel development server:
```
php artisan serve
```

Run frontend build/watch:
```
npm run dev
```

Visit:
```
http://localhost:8000
```
📁 Project Structure
```
app/             # Application logic
bootstrap/       # Framework bootstrapping
config/          # Config files
database/        # Migrations and seeds
public/          # Public assets
resources/       # Blade views, CSS, JS
routes/          # Route definitions
storage/         # Logs, cache, storage
tests/           # Automated tests
```
🧩 Usage

- Users can log in to manage posts

- Create a new post

- Edit an existing post

- Delete posts

- Public visitors can read all posts

📄 License

This project is open-source. You may use, modify, and distribute it freely.
