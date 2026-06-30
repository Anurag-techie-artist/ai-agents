<h1 align="center">🧠 Learning Path Generator</h1>

<p align="center">
An AI-powered agent that generates personalized learning roadmaps, researches resources, creates Google Docs, and schedules study plans automatically.
</p>

<p align="center">

![n8n](https://img.shields.io/badge/Built%20With-n8n-FF6D5A?style=for-the-badge)
![Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?style=for-the-badge)
![LLM](https://img.shields.io/badge/LLM-Agent-blueviolet?style=for-the-badge)
![Automation](https://img.shields.io/badge/Automation-AI-success?style=for-the-badge)

</p>

---

# 📖 Overview

The **Learning Path Generator** is an autonomous AI agent designed to create structured learning plans from a simple user goal.

Instead of manually planning courses, collecting resources, writing notes, and creating reminders, this agent performs the complete workflow automatically.

The agent researches learning resources, organizes a day-wise curriculum, creates documentation in Google Docs, and schedules study sessions directly in Google Calendar.

---

# ✨ Features

- 🧠 AI-generated learning roadmap
- 📚 Automatic resource discovery
- 🎥 Finds relevant YouTube videos
- 🌐 Finds articles & documentation
- 📄 Creates Google Docs
- 📅 Schedules Google Calendar events
- ⚡ Fully automated workflow
- 🤖 Powered by Google Gemini

---

# 🏗️ Architecture

<p align="center">
<img src="../../assets/architecture/learning-path-generator.png" width="90%">
</p>

---

# 🔄 Workflow

```text
User Goal
     │
     ▼
Chat Trigger
     │
     ▼
Google Gemini
     │
     ▼
Curriculum Planning
     │
     ├──────────────┐
     ▼              ▼
Resource Search   Google Docs
     │              │
     ▼              ▼
Calendar Events
     │
     ▼
Learning Plan Delivered
```

---

# 📸 Workflow Screenshot

<p align="center">
<img src="images/workflow.png" width="100%">
</p>

---

# 🛠️ Technology Stack

| Component | Technology |
|-----------|------------|
| Workflow | n8n |
| LLM | Google Gemini |
| Search | SerpAPI |
| Documentation | Google Docs API |
| Scheduling | Google Calendar API |

---

# 📂 Repository Structure

```text
Learning Path Generator
│
├── README.md
├── Learning Path Generator.json
│
└── images
    ├── architecture.png
    ├── workflow.png
    └── demo.gif
```

---

# 🚀 How It Works

1. User specifies a learning goal.
2. Gemini generates a structured curriculum.
3. The agent researches high-quality learning resources.
4. A Google Doc is created automatically.
5. Calendar events are scheduled.
6. The completed learning roadmap is delivered to the user.

---

# 🎯 Example Prompt

```text
Create a 30-day roadmap to learn Cloud Computing starting next Monday.
```

---

# 🔮 Future Improvements

- Adaptive difficulty levels
- Progress tracking
- Quiz generation
- Notion integration
- PDF export
- Multi-language support

---

# 📄 License

MIT License
