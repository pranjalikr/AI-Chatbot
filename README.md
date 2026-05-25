# 🤖 Lumina AI – Intelligent Chatbot Assistant

A modern AI-powered chatbot built using **FastAPI**, **Groq API**, and a custom **HTML/CSS/JavaScript frontend**. Lumina AI enables real-time conversations, generates intelligent responses, and provides a clean, responsive user experience inspired by modern conversational AI platforms.



<h2>📌 About</h2>

<b>Lumina AI</b> is designed to simulate human-like conversations by processing user queries and generating context-aware responses using Large Language Models (LLMs). The project combines a responsive frontend interface with a FastAPI backend and Groq's high-speed inference engine to deliver a seamless chatbot experience.



<h2>✨ Features</h2>

✅ <b>Real-Time AI Conversations</b> 💬 – Engage in interactive conversations powered by Groq LLMs.<br>
✅ <b>Modern Responsive UI</b> 🎨 – Clean and user-friendly interface with sidebar navigation and chat history layout.<br>
✅ <b>Fast Response Generation</b> ⚡ – Delivers low-latency responses using Groq API.<br>
✅ <b>Markdown Response Rendering</b> 📝 – Supports formatted text, lists, headings, and code blocks.<br>
✅ <b>Dark & Light Theme Support</b> 🌙 – Enhanced user experience with theme switching.<br>
✅ <b>REST API Integration</b> 🔗 – Frontend and backend connected using FastAPI endpoints.<br>
✅ <b>Scalable Architecture</b> 🛠 – Easy to extend with memory, authentication, and additional AI models.<br>



<h2>🚀 How It Works</h2>

1️⃣ <b>Enter your message</b> – Type a query in the chatbot interface.<br>
2️⃣ <b>Request is sent to backend</b> – JavaScript sends the message to the FastAPI server.<br>
3️⃣ <b>Groq API processes the prompt</b> – The selected LLM generates an intelligent response.<br>
4️⃣ <b>Response is displayed</b> – The AI-generated reply is rendered in the chat interface with formatting support.<br>



<h2>🛠️ Tech Stack</h2>

| Technology | Purpose |
|------------|---------|
| Python 🐍 | Backend development |
| FastAPI ⚡ | REST API framework |
| Groq API 🤖 | AI response generation |
| HTML5 🌐 | Frontend structure |
| CSS3 🎨 | Styling and responsiveness |
| JavaScript ⚙️ | Frontend logic and API integration |
| VS Code 💻 | Development environment |



<h2>📂 Project Structure</h2>

```text
chatbot/
├── chatbottt.py        # FastAPI backend
├── index.html          # Frontend UI
├── .env                # API credentials
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation
```



<h2>⚙️ Installation & Setup</h2>

**1. Clone the repository:**
```bash
git clone https://github.com/pranjalikr/Chatbot.git
```

**2. Navigate to the project folder:**
```bash
cd Chatbot
```

**3. Install dependencies:**
```bash
pip install fastapi uvicorn groq python-dotenv
```

**4. Configure Environment Variables**

Create a `.env` file and add your API credentials:

```env
GROQ_API_KEY=YOUR_API_KEY
```

**5. Run the backend server:**
```bash
uvicorn chatbottt:app --reload
```

**6. Launch the frontend:**

Open `index.html` using VS Code Live Server or any local web server.



<h2>📊 Output</h2>

- Real-time AI-generated responses
- Modern web-based chatbot interface
- Fast conversational experience powered by Groq
- Markdown-rendered responses with clean formatting
- Responsive design for desktop and mobile devices



<h2>📈 Key Learnings</h2>

- Building full-stack AI applications
- Integrating FastAPI with frontend interfaces
- Working with Large Language Models through APIs
- Frontend-backend communication using JavaScript Fetch API
- Environment variable management and API security
- UI/UX design principles for conversational applications



<h2>🔮 Future Improvements</h2>

- 🧠 Conversation memory and chat persistence
- 🎙️ Voice-enabled interaction (Speech-to-Text)
- 📎 File upload and document analysis
- 🌍 Multi-language conversation support
- 👤 User authentication and profiles
- ☁️ Cloud deployment and database integration
- 📥 Chat export and conversation management



<h2>👩‍💻 Author</h2>

<b>Pranjali Kargaonkar</b><br>
Aspiring AI & Full Stack Developer passionate about building intelligent and user-friendly applications.

- GitHub: [github.com/pranjalikr](https://github.com/pranjalikr)
- LinkedIn: [linkedin.com/in/pranjali-kargaonkar](https://www.linkedin.com/in/pranjali-kargaonkar)



<h2>⭐ Support</h2>

If you found this project helpful, give it a star ⭐ and feel free to contribute or share feedback!
