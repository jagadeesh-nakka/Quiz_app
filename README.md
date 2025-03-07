# Full Stack Quiz Application with Admin Feature

## 🚀 Project Overview

This is a full-stack quiz application built using **React.js** for the frontend and **Node.js, Express.js, and MongoDB** for the backend. The application allows users to take quizzes, track their scores, and view their progress. Admin users can view a leaderboard and manage quiz results.

## 🛠️ Technology Stack

### **Frontend:**

- React.js (Hooks, Functional Components)
- React Router
- Tailwind CSS (for styling)
- Context API (for global state management)

### **Backend:**

- Node.js
- Express.js
- MongoDB (Mongoose ORM)
- JSON Web Token (JWT) for authentication

## 🌟 Features

### **User Features:**

✅ Select quizzes from a list\
✅ Answer different types of questions (Single choice, Multiple choice, True/False)\
✅ Show immediate feedback after answering\
✅ Display a progress bar\
✅ View the final score summary after completing the quiz\
✅ Light/Dark mode toggle

### **Admin Features:**

✅ Login system for admin access\
✅ View leade


 Installation & Setup



1. Clone the Repository



git clone https://github.com/yourusername/quiz-app.git

cd quiz-app



2. Backend Setup



cd backend

npm install



Create a .env file in the backend/ folder and add the following:



PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key



Start the backend server:



npm start



3. Frontend Setup



cd ../frontend

npm install

npm start



🛠 API Endpoints



Auth Routes



POST /api/auth/register → Register a new user



POST /api/auth/login → Login user & return JWT token



Quiz Routes



GET /api/quizzes → Get all quizzes



GET /api/quizzes/:id → Get quiz questions by ID



POST /api/quizzes/:id/submit → Submit quiz & get score



Admin Routes



GET /api/admin/leaderboard → Get leaderboard (Admin only)



GET /api/admin/users → Get all user scores (Admin only)



🚀 Deployment



Deploy Backend (Node.js & Express) on Render/Vercel



git push origin main



Deploy Frontend (React) on Vercel



npm run build

vercel deploy



📀 Contributors



Jagadeesh Nakka - GitHub Profile



🐝 License



This project is licensed under the MIT License.



🎯 Contact



If you have any questions, feel free to reach out at jagadeeshnakka9640@gmail.com.

