# 🖥️ Back-End Development Projects

Welcome to the **Back-End Projects Hub**. This repository serves as a centralized workspace for various server-side applications, ranging from Python-based MVC applications built with Django to Node.js/Express APIs built with JavaScript and TypeScript.

---

## 🛠️ Technology Stack Summary

These projects showcase skills in building scalable, secure, and performant back-end systems using:
- **Python / Django:** Model-View-Template (MVT) architecture, Django Admin, ORM, authentication, and middlewares.
- **Node.js / Express:** RESTful API design, MVC design pattern, robust middlewares, and routing.
- **TypeScript:** Type-safe backend architectures and interfaces.
- **ORMs & Databases:** Prisma ORM, Mongoose/MongoDB, PostgreSQL, and SQLite.
- **Advanced Features:** Caching mechanisms, user authentication, role-based access control, file storage, and data seeding.

---

## 📂 Project Showcase

The projects are organized by their technology stack:
- **[`Django`](./Django)**: Contains Python and Django-based server-side applications.
- **[`Node.js`](./Node.js)**: Contains Node.js, Express, and TypeScript-based server-side applications.
- **[`Python`](./Python)**: Contains Python database relationship examples (One-to-One, One-to-Many, Many-to-Many) and database design using SQL.

### 1. 📝 Blog Application (Django)
*   **Path:** [`Django/Blog_Application_Django`](./Django/Blog_Application_Django)
*   **Tech Stack:** Python, Django, SQLite, Django Templates, HTML/CSS.
*   **Key Features:**
    *   Full CRUD operations on blog posts.
    *   User registration, login, logout, and profile management.
    *   Comments system on articles.
    *   Admin panel integration for easy content management.

### 2. 📚 Book Store Management API (Node.js)
*   **Path:** [`Node.js/Book-Store-Management`](./Node.js/Book-Store-Management)
*   **Tech Stack:** Node.js, Express.js, MongoDB (Mongoose), JavaScript.
*   **Key Features:**
    *   Complete RESTful API endpoints for books, authors, and users.
    *   User authentication (JWT/Cookies) and security middleware.
    *   Robust input validation and custom error-handling middleware.
    *   Database seeder script (`seeder.js`) for rapid local development.
    *   Dynamic server-side views (EJS/HTML).

### 3. 🎓 LMS (Learning Management System) Backend (TypeScript)
*   **Path:** [`Node.js/lms-backend`](./Node.js/lms-backend)
*   **Tech Stack:** Node.js, Express, TypeScript, Prisma ORM, PostgreSQL, caching.
*   **Key Features:**
    *   Type-safe backend architecture using TypeScript interfaces.
    *   Database schema modeling and migrations using Prisma.
    *   Course creation, user enrollment, instructor management, and progress tracking.
    *   Custom caching mechanisms to reduce DB queries and speed up response times.
    *   Modular architectural pattern for clean code separation.

### 4. 🗂️ Taskfy App (Django)
*   **Path:** [`Django/Taskfy-app-Django`](./Django/Taskfy-app-Django)
*   **Tech Stack:** Python, Django, SQLite, Django ORM.
*   **Key Features:**
    *   Kanban-style task board or task listing.
    *   Categorized tasks with priorities, status tracking, and deadlines.
    *   User-specific task isolation (users only see their tasks).
    *   Clean interactive UI built on Django templates.

### 5. 🗄️ Python with SQL
*   **Path:** [`Python/`](./Python)
*   **Tech Stack:** Python, SQL, SQLite / PostgreSQL.
*   **Key Features:**
    *   Implementation of fundamental database relationships: One-to-One, One-to-Many, and Many-to-Many.
    *   Social Network database structure design and modeling.
    *   Database query optimization using Python to execute complex SQL relationships.

---

## 🚀 How to Run the Projects

### Running Django Projects
1. Make sure you have Python 3 installed.
2. Navigate to the project directory:
   ```bash
   cd Django/Blog_Application_Django  # or Taskfy-app-Django
   ```
3. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
5. Apply database migrations:
   ```bash
   python manage.py migrate
   ```
6. Start the development server:
   ```bash
   python manage.py runserver
   ```

### Running Node.js/Express Projects
1. Make sure you have Node.js (v18+) installed.
2. Navigate to the project directory:
   ```bash
   cd Node.js/Book-Store-Management
   ```
3. Install packages:
   ```bash
   npm install
   ```
4. Configure environment variables (create a `.env` file based on `.env.example` if applicable).
5. Start development server:
   ```bash
   npm run dev  # or node app.js
   ```

### Running TypeScript/Prisma Projects
1. Navigate to the project directory:
   ```bash
   cd Node.js/lms-backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Generate Prisma client & apply migrations:
   ```bash
   npx prisma generate
   npx prisma migrate dev
   ```
4. Run in development mode:
   ```bash
   npm run dev
   ```

### Running Python with SQL Projects
1. Navigate to the project directory:
   ```bash
   cd Python
   ```
2. Run any database relationship script:
   ```bash
   python3 "One to One/main.py"
   ```
