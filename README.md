# 🧠 Interview IQ

**Interview IQ** is an AI-powered interview preparation platform designed to help users practice interviews, improve their answers, and build confidence before attending real interviews.

🔗 **Live Demo:** https://project-01-client.onrender.com/

---

## 🚀 Features

* 🤖 **AI-Powered Interview Practice**
  Practice interview questions with an AI-based interview system.

* 🎯 **Interview Preparation**
  Prepare for technical and general interview questions.

* 💬 **Interactive Interview Experience**
  Answer questions and receive an interview-like experience.

* 📊 **Performance Improvement**
  Review your responses and identify areas that need improvement.

* 🔐 **User Authentication**
  Secure user registration and login functionality.

* 📱 **Responsive UI**
  Designed to work across desktop, tablet, and mobile devices.

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* JavaScript
* HTML5
* CSS3
* Tailwind CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* MongoDB Atlas

### Authentication & APIs

* REST APIs
* JWT Authentication

### Deployment

* Render

---

## 🏗️ Project Architecture

```text
Interview-IQ
│
├── client/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   ├── hooks/
│   │   ├── services/
│   │   └── App.jsx
│   │
│   ├── public/
│   └── package.json
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ How It Works

### 1. User Registration/Login

Users create an account or log in to the platform.

```text
User
 ↓
Registration/Login
 ↓
Authentication
 ↓
Interview Dashboard
```

### 2. Start Interview

The user starts an interview session and receives interview questions.

```text
Start Interview
       ↓
Interview Question
       ↓
User Answer
       ↓
AI/Backend Processing
       ↓
Next Question
```

### 3. Interview Evaluation

The user's responses can be analyzed to help identify strengths and areas for improvement.

---

## 📦 Installation

Clone the repository:

```bash
git clone <your-repository-url>
```

Navigate to the project:

```bash
cd Interview-IQ
```

Install frontend dependencies:

```bash
cd client
npm install
```

Install backend dependencies:

```bash
cd ../server
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the backend directory.

Example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

If your project uses an AI API, add the required API key as well:

```env
AI_API_KEY=your_api_key
```

> Never commit your `.env` file or API keys to GitHub.

---

## ▶️ Run Locally

### Start Backend

```bash
cd server
npm run dev
```

### Start Frontend

Open another terminal:

```bash
cd client
npm run dev
```

The frontend will normally run on:

```text
http://localhost:5173
```

---

## 🌐 Live Application

The project is deployed on Render:

**https://project-01-client.onrender.com/**

---

## 🎯 Purpose of the Project

The main goal of Interview IQ is to provide an accessible platform where students and job seekers can practice interviews in a realistic environment.

Instead of only reading interview questions, users can actively practice answering them and use the experience to improve their interview preparation.

---

## 📚 What I Learned

While developing this project, I gained practical experience with:

* React component development
* React state management
* REST API integration
* Node.js and Express
* MongoDB database integration
* User authentication
* JWT-based authorization
* Frontend-backend communication
* Environment variables
* API error handling
* Responsive UI development
* Full-stack application deployment
* Debugging production applications

---

## 🔮 Future Improvements

Some features that can be added in future versions:

* 🎤 Voice-based interviews
* 🗣️ Speech-to-text interview answers
* 📈 Detailed performance analytics
* 🤖 More advanced AI feedback
* 📄 Resume-based interview questions
* 🎯 Job-role-specific interviews
* 🏆 Interview performance history
* ⏱️ Timed interview sessions
* 📊 Skill-wise performance reports

---

## 👨‍💻 Author

**Anuj Kumar**

B.Tech – Artificial Intelligence & Machine Learning

---

## ⭐ Support

If you find this project useful, consider giving the repository a ⭐ on GitHub.
