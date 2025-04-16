# 🤖 AI Interview Coach

Welcome to **AI Interview Coach**, a smart, modern platform designed to help job seekers and learners practice and prepare for real-world interviews using AI-powered tools and interactive mock sessions.

---

## 🔍 What This Project Does

This platform allows users to:

- 🎤 Practice interviews in real-time (using video & audio)
- 📋 Attempt smart quizzes customized to any field or domain
- 🧠 Chat with an AI assistant that asks interview-style questions
- 👤 Track skills, completed sessions, and interview readiness
- ⚡ Prepare in a hands-on, realistic environment – solo or with peers

---

## 🚀 Why This Project?

Cracking interviews takes more than theory — it needs practice, pressure handling, and clarity.  
**AI Interview Coach** brings all of that into one place. No mentors needed. No scheduling hassle.  
Just log in, practice, and grow.

---

## 🧱 Tech Stack

| Part        | Tech Used                        |
|-------------|----------------------------------|
| Frontend    | React.js (Vite) + Tailwind CSS   |
| Backend     | Node.js + Express.js             |
| Database    | MongoDB                          |
| AI Engine   | Google Gemini API                |
| Real-time   | Socket.io                        |
| Hosting     | Vercel (frontend) + Render (backend)

---

## 🛠️ How to Run Locally

## 🚀 Getting Started Locally

### 1️⃣ Clone the Project
```bash
git clone https://github.com/ayusssh01/AI-Interview-Coach.git
cd AI-Interview-Coach

### Frontend Setup

1. Navigate to frontend

   ```bash
   cd frontend
   ```

2. Install dependencies:

   ```bash
   npm i
   ```

3. Set up environment variables:
   Create a `.env` file in the **frontend directory** and add **your required environment variables** according to this format: 

   ```bash
    VITE_API_URL='<your-backend-api-url'
   ```
    Format also present in the frontend folder in the file [.env.example.frontend](./frontend/.env.example.frontend)
    <br>

4. Start the development frontend server:
   ```bash
   npm run dev
   ```

### Backend Setup

cd backend
npm install

🔐 Create .env in /backend/:

JWT_SECRET=your_secret
MONGODB_URI=your_mongo_uri
GEMINI_API_KEY=your_gemini_key
PORT=3000

## 🌐 API Endpoints

- `POST /api/v1/auth/signup`: User registration
- `POST /api/v1/auth/login`: User login
- `POST /api/v1/auth/logout`: User logout
- `POST /api/v1/auth/editUser`: Edit user information
- `GET /api/v1/auth/getAuth`: Get user authentication status
- `POST /api/v1/auth/updateAvatar`: Update user avatar
- `POST /api/v1/rooms/addroom/:roomID`: Add a new room
- `POST /api/v1/rooms/deleteroom/:roomID`: Delete a room
- `GET /api/v1/rooms/getroom/:roomID`: Get room information
- `POST /api/v1/quiz/generate-id`: Generate a quiz ID
- `POST /api/v1/quiz/generate-quiz`: Generate a quiz
- `POST /api/v1/quiz/save-answer`: Save a quiz answer
- `POST /api/v1/quiz/evaluate-answer`: Evaluate a quiz answer
- `POST /api/v1/quiz/terminate-quiz`: Terminate a quiz session
- `POST /api/v1/questions/generate-questions`: Generate questions for a quiz
- `POST /api/v1/questions/chat`: Interact with AI chatbot
  

We welcome contributions to this project! Please feel free to submit issues, fork the repository and send pull requests!

## 🙏 Acknowledgements

- [Gemini](https://cohere.ai/) for providing the AI API
- [MongoDB](https://www.mongodb.com/) for the database solution
- [Vercel](https://vercel.com/) for frontend deployment
- [Render](https://render.com/) for backend deployment


