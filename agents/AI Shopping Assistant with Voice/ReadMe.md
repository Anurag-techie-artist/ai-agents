<h1 align="center">🛍️ AI Shopping Assistant (Voice)</h1>

<p align="center">
A voice-enabled AI shopping assistant that understands natural language, recommends products, provides personalized styling advice, and searches Amazon in real time.
</p>

<p align="center">

![n8n](https://img.shields.io/badge/Built%20With-n8n-FF6D5A?style=for-the-badge)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?style=for-the-badge)
![Groq Whisper](https://img.shields.io/badge/Groq-Whisper-orange?style=for-the-badge)
![Telegram](https://img.shields.io/badge/Telegram-Bot-blue?style=for-the-badge)
![AI Agent](https://img.shields.io/badge/AI-Agent-success?style=for-the-badge)

</p>

---

# 📖 Overview

The **AI Shopping Assistant (Voice)** is an intelligent conversational shopping assistant built using **n8n**, **Google Gemini**, **Groq Whisper**, and **Telegram**.

Users can interact with the assistant using either **voice messages** or **text messages**.

Depending on the user's request, the assistant intelligently switches between multiple capabilities:

- Voice transcription
- AI-powered conversations
- Amazon product discovery
- Personalized fashion recommendations
- Styling consultation
- Shopping assistance

The workflow behaves like a real shopping assistant rather than a traditional chatbot.

---

# ✨ Features

- 🎙️ Voice input support
- 💬 Text conversations
- 🤖 AI-powered shopping assistant
- 🛒 Amazon product search
- 👕 Fashion & styling recommendations
- ⭐ Product comparison
- 🌐 Real-time web scraping
- ⚡ Fully automated workflow
- 📱 Telegram integration

---

# 🏗️ Architecture

<p align="center">
<img src="../../assets/architecture/shopping-assistant-voice.png" width="90%">
</p>

---

# 🔄 Workflow

```text
Telegram User
       │
       ▼
Voice / Text Detection
       │
       ├───────────────┐
       ▼               ▼
Voice Message      Text Message
       │               │
       ▼               │
Groq Whisper           │
       │               │
       └───────┬───────┘
               ▼
        Google Gemini AI
               │
        Intent Recognition
               │
     ┌─────────┴─────────┐
     ▼                   ▼
Shopping Search     Styling Advice
     │                   │
     ▼                   ▼
Amazon Scraper     AI Recommendations
     │                   │
     └─────────┬─────────┘
               ▼
Telegram Response
```

---

# 📸 Workflow Screenshot

<p align="center">
<img src="images/workflow.png" width="100%">
</p>

---

# 🛠 Technology Stack

| Component | Technology |
|-----------|------------|
| Workflow Automation | n8n |
| LLM | Google Gemini |
| Speech Recognition | Groq Whisper |
| Messaging Platform | Telegram Bot API |
| Product Search | ScraperAPI |
| Shopping Platform | Amazon India |
| Programming | JavaScript, Python |

---

# 💡 Core Capabilities

### 🎙️ Voice Shopping

Users can simply send a voice message describing what they want.

Example:

```text
Show me white sneakers under ₹3000
```

The assistant transcribes the request, searches Amazon, and returns relevant product recommendations.

---

### 🛒 Product Discovery

The assistant searches Amazon India in real time and provides:

- Product name
- Price
- Rating
- Product link

instead of generating fictional recommendations.

---

### 👗 Personal Styling Assistant

The agent can also act as a fashion consultant.

Example:

```text
How should I style a blue kurti?
```

Instead of immediately recommending products, the assistant asks follow-up questions about:

- Occasion
- Preferred style
- Color preferences
- Season

before generating personalized styling advice.

---

# 🚀 How It Works

1. User sends a text or voice message.
2. Voice messages are converted into text using Groq Whisper.
3. Gemini identifies the user's intent.
4. The workflow chooses the appropriate tool.
5. Shopping requests trigger Amazon search.
6. Styling requests generate personalized recommendations.
7. Results are delivered through Telegram.

---

# 🎯 Example Prompts

```text
Show me running shoes under ₹4000.
```

```text
Find me a black hoodie for winter.
```

```text
How can I style white sneakers?
```

```text
Suggest an outfit for a wedding.
```

---

# 💼 Use Cases

- Online shopping assistant
- Fashion consultation
- Product discovery
- Voice commerce
- Personal shopping assistant
- AI retail chatbot

---

# 🔮 Future Improvements

- Price comparison across multiple stores
- Wishlist support
- Order tracking
- Image-based shopping
- Personalized recommendations
- Multilingual conversations
- Voice response generation

---

# 📄 License

MIT License
