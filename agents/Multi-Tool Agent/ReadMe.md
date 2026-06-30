<h1 align="center">🛠️ AI-Powered Multi-Tool Agent</h1>

<p align="center">
An intelligent AI assistant capable of reasoning, web search, calculations, knowledge retrieval, and productivity tasks through dynamic tool selection.
</p>

<p align="center">

![n8n](https://img.shields.io/badge/Built%20With-n8n-FF6D5A?style=for-the-badge)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?style=for-the-badge)
![Telegram](https://img.shields.io/badge/Telegram-Bot-blue?style=for-the-badge)
![AI Agent](https://img.shields.io/badge/AI-Agent-success?style=for-the-badge)
![LLM](https://img.shields.io/badge/LLM-Tool%20Calling-purple?style=for-the-badge)

</p>

---

# 📖 Overview

The **AI-Powered Multi-Tool Agent** is an intelligent assistant that goes beyond simple conversation by dynamically selecting and using the right tool for each user request.

Rather than relying solely on an LLM, the agent analyzes intent and orchestrates multiple specialized tools to deliver accurate, context-aware responses.

Whether the user needs real-time information, mathematical calculations, factual knowledge, or productivity support, the agent autonomously chooses the appropriate workflow.

---

# ✨ Features

- 🤖 Natural language conversations
- 🌍 Real-time web search
- ➗ Mathematical calculations
- 📚 Knowledge retrieval
- 📅 Calendar assistance
- ⚡ Automatic tool selection
- 💬 Telegram integration
- 🧠 Context-aware reasoning

---

# 🏗️ Architecture

<p align="center">
<img src="../../assets/architecture/multi-tool-agent.png" width="90%">
</p>

---

# 🔄 Workflow

```text
Telegram User
      │
      ▼
Telegram Trigger
      │
      ▼
Google Gemini
(Intent Understanding)
      │
      ▼
Tool Selection
      │
 ┌────┼──────────────┬───────────┬────────────┐
 ▼    ▼              ▼           ▼            ▼
Chat  SerpAPI   Calculator   Wikipedia   Calendar
 │      │            │            │            │
 └──────┴────────────┴────────────┴────────────┘
                    │
                    ▼
            AI Response Generation
                    │
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
| Search | SerpAPI |
| Knowledge Base | Wikipedia |
| Productivity | Google Calendar |
| Messaging | Telegram Bot API |
| Utilities | Calculator Tool |

---

# 💡 Core Capabilities

### 🤖 Conversational AI

Handles open-ended conversations, explanations, brainstorming, and creative tasks using Google Gemini.

---

### 🌍 Live Web Search

Retrieves up-to-date information from the internet when current data is required.

Examples:

- Latest AI news
- Stock prices
- Current events
- Weather information

---

### ➗ Intelligent Calculator

Automatically performs:

- Arithmetic
- Percentages
- Unit conversions
- Date calculations

without requiring manual formulas.

---

### 📚 Knowledge Retrieval

Searches Wikipedia for reliable background information on:

- People
- Companies
- Historical topics
- Scientific concepts

---

### 📅 Productivity Support

Integrates with Google Calendar to assist with scheduling and calendar-related operations.

---

# 🚀 How It Works

1. User sends a request through Telegram.
2. Gemini interprets the user's intent.
3. The agent determines whether a tool is needed.
4. The appropriate tool is invoked.
5. Results are processed by Gemini.
6. A natural-language response is delivered back to the user.

---

# 🎯 Example Prompts

```text
What is 18% of ₹24,500?
```

```text
Who founded NVIDIA?
```

```text
Latest AI news today.
```

```text
Explain quantum computing in simple terms.
```

```text
Create a calendar reminder for tomorrow at 10 AM.
```

---

# 💼 Use Cases

- Personal AI assistant
- Research companion
- Productivity assistant
- Educational chatbot
- Smart calculator
- Knowledge assistant
- Information retrieval
- Task automation

---

# 🔮 Future Improvements

- Memory-enabled conversations
- Gmail integration
- Google Drive support
- Weather API integration
- PDF analysis
- Image understanding
- Voice conversations
- Multi-agent collaboration

---

# 📄 License

MIT License
