# SkillPath AI 🚀

SkillPath AI is an AI-powered career guidance platform designed to help students and professionals explore career opportunities, understand required skills, and plan their career growth journey.

The platform provides career information, authentication, role-based access, and a structured interface for students, mentors, and administrators.

## ✨ Features

### 👨‍🎓 Student Features

* User registration and login
* Browse career paths
* View career details and required skills
* Access personalized career guidance
* Secure authentication using JWT

### 🧑‍🏫 Mentor Features

* Provide career guidance
* Help students understand career pathways
* Support skill development planning

### 🛠️ Admin Features

* Admin authentication
* Add new career paths
* Edit existing career information
* Manage career resources

## 🏗️ Tech Stack

### Frontend

* React.js
* Vite
* React Router
* Context API
* CSS
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* bcrypt Password Hashing

## 📂 Project Structure

```
SkillPath-AI
│
├── Backend
│   ├── config
│   ├── controllers
│   ├── middleware
│   ├── models
│   ├── routes
│   ├── utils
│   ├── server.js
│   └── package.json
│
├── Frontend
│   ├── src
│   │   ├── components
│   │   ├── pages
│   │   ├── context
│   │   └── api
│   ├── public
│   └── package.json
│
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/KhyatiPrakash/SkillPath-AI.git
```

Move into the project folder:

```bash
cd SkillPath-AI
```

---

## 🔧 Backend Setup

Navigate to the backend folder:

```bash
cd Backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
NODE_ENV=development
CLIENT_URL=http://localhost:5173
```

Start the backend server:

```bash
npm start
```

Backend will run on:

```
http://localhost:5000
```

---

## 💻 Frontend Setup

Open another terminal:

```bash
cd Frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

Frontend will run on:

```
http://localhost:5173
```

---

## 🔐 Authentication

SkillPath AI uses JWT-based authentication.

Security features:

* Password encryption using bcrypt
* Protected routes
* Role-based authorization
* Secure API access

## 🌐 API Overview

### Authentication Routes

| Method | Endpoint             | Description   |
| ------ | -------------------- | ------------- |
| POST   | `/api/auth/register` | Register user |
| POST   | `/api/auth/login`    | Login user    |

### Career Routes

| Method | Endpoint           | Description           |
| ------ | ------------------ | --------------------- |
| GET    | `/api/careers`     | Get careers           |
| POST   | `/api/careers`     | Add career (Admin)    |
| PUT    | `/api/careers/:id` | Update career (Admin) |
| DELETE | `/api/careers/:id` | Delete career (Admin) |

## 🚀 Deployment

Recommended deployment:

Frontend:

* Vercel

Backend:

* Render

Database:

* MongoDB Atlas

## 📌 Future Improvements

* AI-based personalized career recommendations
* Skill gap analysis
* Resume analysis
* Learning roadmap generation
* Mentor-student communication system
* Career chatbot assistant

## 👨‍💻 Author

**Khyati Prakash**

GitHub:
https://github.com/KhyatiPrakash

## 📄 License

This project is developed for educational and internship purposes.

