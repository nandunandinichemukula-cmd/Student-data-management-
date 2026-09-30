# Student Management System — Node.js + Express + MySQL + MVC

## Requirements
- Node.js 18+
- MySQL 8+
- VS Code

## 1. Database
Run `database/student_db.sql` in MySQL.

## 2. Configure MySQL
Open `backend/.env` and change:
DB_USER=root
DB_PASSWORD=YOUR_MYSQL_PASSWORD

## 3. Install packages
Open terminal inside `backend`:
```bash
npm install
```

## 4. Start
```bash
npm start
```

Open:
http://localhost:3000

## Architecture
HTML/CSS/JavaScript
→ Express REST API
→ Controller
→ Model
→ MySQL

## API
GET    /api/students
POST   /api/students
PUT    /api/students/:id
DELETE /api/students/:id


## Important
The page now displays sample student details immediately:
- Nandini — 22
- Rahul — 21
- Priya — 20

When MySQL is connected, the database records replace the sample records.
If the database is unavailable, the page keeps the sample records visible so the
frontend does not look empty.
