# 👩‍💻 Interview Prep AI – An AI-Powered Web Application 👩‍💻

---

## 💡 About the Project

**Interview Prep AI** simplifies and enhances the interview preparation journey by offering an all-in-one platform that allows users to:

- 🧠 Generate **AI-curated questions** tailored to their **target job role**, **experience level**, and **technology focus**
- 📘 Receive **detailed answers**, **explanations**, and **code snippets** for concept reinforcement
- 📌 Manage questions with features like **pinning**, **organizing**, and **multi-session handling**
- 🔁 Perform **CRUD operations** on sessions and questions
- 📱 Enjoy a **responsive** and modern UI for a seamless experience

---

## ✨ Key Features

- 🎯 Intelligent Q&A tailored to individual goals
- 🧩 Contextual learning with detailed insights and code blocks
- 📂 Multi-session creation and management
- 🔒 Secure user authentication (login/signup)
- 🖥️ User profile creation with role, experience, tech focus, and notes
- 📱 Smooth, responsive, and modern UI design
- 🔃 Full CRUD functionality for enhanced control

---

## 🛠 Tech Stack

### 🧩 Frontend
- **React.js** – Component-based UI
- **Tailwind CSS** – Modern and responsive styling
- **JavaScript & HTML** – Dynamic behavior and markup

### 🔧 Backend
- **Node.js & Express.js** – Scalable REST API backend
- **MongoDB** – NoSQL database for flexible data storage
- **Postman** – API development and testing

### 🤖 AI Integration
- **Gemini 2.0 Flash Lite (Google)** – API-powered dynamic question and explanation generation

---

## 📂 Setup & Usage
```bash
# 1. Clone the repository: 
git clone https://github.com/your-username/interview-prep-ai.git

# 2. Create a `.env` file in the `backend` directory with the following content:
MONGO_URI = enter_your_mongo_db_uri
JWT_SECRET = enter_your_jwt_secret
GEMINI_API_KEY = enter_your_gemini_api_key
PORT=8000

# 3. Install dependencies and run the project:
# For backend
cd backend
npm install
npm start

# For frontend
cd frontend
npm install
npm run dev
