# CHAT-BOT

# 🤖 Mood-Based AI Chatbot

A simple Generative AI chatbot built using **LangChain**, **Google Gemini 2.5 Flash**, and **Streamlit**.

The chatbot allows users to interact with an AI that changes its personality based on the selected mood.

---

## 🚀 Features

- 🤖 Google Gemini 2.5 Flash
- 🦜 LangChain Integration
- 💬 Streamlit Chat Interface
- 😡 Angry AI Personality
- 😂 Funny AI Personality
- 😢 Sad AI Personality
- 🧠 Conversation Memory
- 🔄 Reset Chat Button
- 🔐 Environment Variables using `.env`

---

## 🛠 Tech Stack

- Python
- Streamlit
- LangChain
- Google Gemini API
- python-dotenv

---

## 📂 Project Structure

```
Mood-Based-AI-Chatbot/
│
├── uichatbot.py          # Streamlit Chat Interface
├── chatbot.py            # Console Version
├── main.py               # LangChain Version Check
├── requirements.txt
├── .env
└── README.md
```

---

## ⚙️ Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/Mood-Based-AI-Chatbot.git

cd Mood-Based-AI-Chatbot
```

---

### Create Virtual Environment

Using uv

```bash
uv venv
```

Activate

Windows

```bash
.venv\Scripts\activate
```

---

### Install Dependencies

```bash
uv pip install -r requirements.txt
```

or

```bash
uv sync
```

---

## 🔑 API Key

Create a `.env` file.

```env
GOOGLE_API_KEY=YOUR_API_KEY
```

Get your free API key from Google AI Studio.

---

## ▶️ Run the Application

```bash
streamlit run uichatbot.py
```

or

```bash
uv run streamlit run uichatbot.py
```

---

## 🎭 AI Modes

### 😡 Angry Mode

Responds aggressively and impatiently.

---

### 😂 Funny Mode

Responds with jokes and humorous answers.

---

### 😢 Sad Mode

Responds emotionally in a sad tone.

---

## 🧠 Conversation Memory

The chatbot stores conversation history during the session using LangChain message objects.

- HumanMessage
- AIMessage
- SystemMessage

This enables the AI to remember previous messages and generate context-aware responses.

---

## 📸 Screenshots

Add screenshots of your application here.

Example:

```
screenshots/
    home.png
    angry_mode.png
    funny_mode.png
```

---

## 📦 Requirements

- Python 3.11+
- Streamlit
- LangChain
- Google Gemini API
- python-dotenv

---

## 🔮 Future Improvements

- Add more AI personalities
- Voice Input
- Voice Output
- Dark/Light Theme
- Chat Export
- Chat History Database
- Multiple LLM Support (OpenAI, Groq, HuggingFace)
- RAG using FAISS
- Image Understanding
- PDF Chat

---

## 📚 What I Learned

Through this project I learned:

- Prompt Engineering
- LangChain Basics
- Google Gemini API
- Streamlit UI Development
- Session State Management
- Environment Variables
- LLM Integration
- Chat Memory

---

## 🤝 Contributing

Contributions are welcome.

Feel free to fork this repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Sagar Chavan**

Aspiring AI Engineer

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourusername
