# [Interview.io](https://interview-io-six.vercel.app/) 🎓🧑‍💻

The project **"AI-Powered Real-Time Interview Coach"** is an innovative virtual platform designed to help users improve their interview skills through a range of interactive and AI-driven features.

This project has been made by all of our collaborators of **Team Codeblooded** & has been submitted for **HackOdisha'24**.

## 🚀 Live here - https://interview-io-six.vercel.app/

## **🏆 This project has won 1st Place in HackOdisha 2k24!!**


## 🌟 Features

- 💻 **Simulated Interview Environment** : The platform provides a **real-time** or **peer-to-peer** interview experience, allowing users to practice in a lifelike scenario using their webcam and microphone. This helps users develop time management skills and offers a flexible and convenient.
  
- 🤔 **Quiz Section:** The quiz system generates **dynamic questions** based on the user's inputs, **covering any domain**. The adaptive difficulty feature adjusts the complexity of questions in real-time, making it suitable for users at different experience levels.

- ❓ **AI-Based Q&A Section**: In this section, users receive **AI-Based real-time, context-specific interview questions** based on their skill level. The AI adjusts the difficulty based on the quality of the user’s responses, ensuring a personalized learning experience.

- 🤵 **User Profile:** Each user has a profile that tracks personal information, professional background, core skills, and the number of completed or upcoming interviews. This helps users stay organized and prepared for their interviews.

- 🚀 **Future Enhancements:** Planned future improvements include a real-time notification system, enhanced quiz security, video call functionality that supports more participants, and better integration between the overview page and upcoming interviews.

## 🛠️ Tech Stack

- **Frontend**: Vite ReactJs ⚛️, Tailwind CSS 🎨, Tailwind 🔄, SCSS 🎭
- **Backend**: Node.js 🟢, Express 🚂
- **Database**: MongoDB 🍃
- **AI Integration**: Google Gemini API 🧠
- **Testing**: Postman 📮
- **Deployment** - Vercel & Render 🚀
- **Socket.io** - For the chat and video calling functionalities 💬

## 🚀 Getting Started Locally

### Project Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/abhrajit2004/Interview.io.git
   ```

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

1. Navigate to backend(**In Another Terminal**)

   ```bash
   cd backend
   ```

2. Install dependencies:

   ```bash
   npm i
   ```

3. Set up environment variables:
   Create a `.env` file in the **backend directory** and add **your required environment variables** according to this format: 

   ```bash
   JWT_SECRET=<your-preferred-jwt-secret-key>
   MONGODB_URI=<your-mongodb-connection-string>
   MONGODB_URI1=<optional>
   GEMINI_API_KEY=<your-gemini-api-key>
   CLOUDINARY_API_KEY= 
   CLOUDINARY_API_SECRET=
   CLOUDINARY_NAME=
   NODE_ENV=development
   PORT=3000 
   ```
    Format also present in the backend folder in the file [.env.example.backend](./backend/.env.example.backend)
    <br>

4. Start the server:
   ```bash
   npm run dev
   ```

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
  
## 😎 Members of our Team Codeblooded 👥
- **Abhrajit Gupta** - [@abhrajitgupta](https://github.com/abhrajit2004)
- **Shuvadipta Das** - [@shuvadiptadas](https://github.com/5h0ov)
- **Ankita Sikdar**  - [@ankitasikdar](https://github.com/AnkitaSikdar005)
- **Megha Karmakar** - [@meghakarmakar](https://github.com/meghakarmakar)
## 🤝 Contributing

We welcome contributions to this project! Please feel free to submit issues, fork the repository and send pull requests!

## 📄 License

This project is licensed under: [MIT licensed](./LICENSE)

## 🙏 Acknowledgements

- [Gemini](https://cohere.ai/) for providing the AI API
- [MongoDB](https://www.mongodb.com/) for the database solution
- [Vercel](https://vercel.com/) for frontend deployment
- [Render](https://render.com/) for backend deployment

Have a great job cracking journey with [Interview.io](https://interview-io-six.vercel.app/)! 🎓✨
