# User Authentication & Management System

A full-stack web application featuring secure user authentication (Login/Register) and a protected dashboard with a user management interface. Built with the MERN stack (MongoDB, Express, React, Node.js).

## 🚀 Features

* **Secure Authentication**: User registration and login using JSON Web Tokens (JWT) and bcrypt for password hashing.
* **Protected Routes**: Dashboard access is restricted to authenticated users only.
* **Responsive UI**: Custom CSS design matching specific UI requirements (Dark "Sign In" card, Status indicators).
* **User Management Dashboard**: A static data visualization table displaying user roles and statuses.
* **Data Persistence**: User session data is persisted using local storage.

## 🛠️ Tech Stack

**Frontend:**
* React.js
* React Router DOM (Navigation & Protected Routes)
* CSS3 (Custom styling)

**Backend:**
* Node.js & Express.js
* MongoDB & Mongoose (Schema-based data modeling)
* JWT (JSON Web Tokens)
* Bcryptjs (Password Encryption)
* Cors & Dotenv

---

## ⚙️ Prerequisites

Before running this project, ensure you have the following installed:
* [Node.js](https://nodejs.org/) (v14 or higher)
* [MongoDB](https://www.mongodb.com/try/download/community) (Local instance running on port 27017)

---

## 📦 Installation & Setup

### 1. Clone the Repository
```bash
git clone [https://github.com/ashugupta1/Quantum-IT-Innovation.git](https://github.com/ashugupta1/Quantum-IT-Innovation.git)
cd Quantum-IT-Innovation


cd Server
npm install

# Start the server (Runs on port 8080 by default)
node app.js


cd ../Client
npm install

# Start the React development server (Runs on port 3000)
npm start