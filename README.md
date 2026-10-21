# Full Stack Interview Platform with Next JS, Supabase, Tailwind, Stream, Arcjet, Shadcn UI Tutorial 🔥🔥

# 🎯 AI Interview Hub

An AI-powered platform that helps candidates practice interviews, get instant feedback, and track their improvement over time.



[Live Demo](#) · [Report Bug](#) · [Request Feature](#)

---

## 📌 About the Project

AI Interview Hub simulates real interview experiences using AI. Users pick a role or topic, answer generated questions, and receive detailed feedback on their answers, covering correctness, clarity, and confidence, so they can prepare more effectively.

## ✨ Features

- 🤖 **AI-generated questions** tailored to role, domain, and difficulty
- 🎤 **Mock interview sessions** (text / voice)
- 📊 **Instant feedback and scoring** on every answer
- 📝 **Resume-based questions** (upload a resume to get personalized questions)
- 📈 **Progress dashboard** with performance history
- 🔐 **User authentication** and saved sessions
- 🗂️ **Question bank** for DSA, HR, System Design, and Core CS subjects

## 🛠️ Tech Stack

| Layer    | Technology                          |
|----------|-------------------------------------|
| Frontend | [React / Next.js / HTML, CSS, JS]   |
| Backend  | [Node.js, Express / Flask / Django] |
| Database | [MongoDB / PostgreSQL / Firebase]   |
| AI / API | [OpenAI / Gemini / Claude API]      |
| Auth     | [JWT / Firebase Auth]               |
| Hosting  | [Vercel / Render / AWS]             |

## 📂 Project Structure

```
ai-interview-hub/
├── client/             # Frontend code
│   ├── src/
│   └── public/
├── server/             # Backend code
│   ├── routes/
│   ├── controllers/
│   └── models/
├── .env.example
├── package.json
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or above) and npm
- [Database] installed or a cloud connection string
- An API key for [AI provider]

### Installation

1. **Clone the repository**
```bash
   git clone https://github.com/<your-username>/ai-interview-hub.git
   cd ai-interview-hub
```

2. **Install dependencies**
```bash
   # Backend
   cd server
   npm install

   # Frontend
   cd ../client
   npm install
```

3. **Set up environment variables**

   Create a `.env` file in the `server` folder:
```env
   PORT=5000
   DATABASE_URL=your_database_url
   AI_API_KEY=your_ai_api_key
   JWT_SECRET=your_jwt_secret
```

4. **Run the project**
```bash
   # Start backend
   cd server
   npm start

   # Start frontend (in a new terminal)
   cd client
   npm start
```

5. Open **http://localhost:3000** in your browser.

## 💡 Usage

1. Sign up or log in.
2. Choose an interview type (Technical, HR, or Domain-specific).
3. Answer the questions one by one.
4. Review your AI-generated feedback and score.
5. Track progress from the dashboard.

## 📸 Screenshots

| Home | Interview Session | Feedback |
|------|-------------------|----------|
| ![Home](screenshots/home.png) | ![Interview](screenshots/interview.png) | ![Feedback](screenshots/feedback.png) |

## 🗺️ Roadmap

- [x] Basic question generation
- [x] Answer evaluation
- [ ] Voice-based interviews
- [ ] Resume analyzer
- [ ] Video interview with confidence analysis
- [ ] Leaderboard and streaks

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository
2. Create a branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m "Add your feature"`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for details.

## 👤 Author

**[Your Name]**
B.Tech CSE, CGC University, Mohali

- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [your-profile](https://linkedin.com/in/your-profile)
- Email: your.email@example.com

---

⭐ If you found this project helpful, consider giving it a star!
