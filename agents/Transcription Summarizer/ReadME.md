<h1 align="center">🎙️ Transcription Summarizer Agent</h1>

<p align="center">
An AI-powered transcription and summarization agent that converts audio into text, generates structured summaries, and automatically stores the results in Google Docs.
</p>

<p align="center">

![n8n](https://img.shields.io/badge/Built%20With-n8n-FF6D5A?style=for-the-badge)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?style=for-the-badge)
![Whisper](https://img.shields.io/badge/Groq-Whisper-orange?style=for-the-badge)
![Automation](https://img.shields.io/badge/AI-Automation-success?style=for-the-badge)

</p>

---

# 📖 Overview

The **Transcription Summarizer Agent** automates the complete process of converting spoken audio into structured knowledge.

Users simply provide an audio recording, and the workflow automatically:

- Transcribes speech into text
- Generates an AI-powered summary
- Extracts important points
- Creates a Google Document
- Stores both the transcript and summary
- Returns the document link and summary to the user

This eliminates manual note-taking and makes meetings, lectures, interviews, and podcasts easier to review.

---

# ✨ Features

- 🎙️ Audio transcription
- 📝 AI-generated summaries
- 📄 Google Docs integration
- 📌 Key point extraction
- ✅ Action item detection
- 🤖 Google Gemini reasoning
- ⚡ Fully automated workflow
- ☁️ Cloud-based processing

---

# 🏗️ Architecture

<p align="center">
<img src="../../assets/architecture/transcription-summarizer.png" width="90%">
</p>

---

# 🔄 Workflow

```text
User Uploads Audio
        │
        ▼
Audio Processing
        │
        ▼
Groq Whisper
        │
        ▼
Transcript
        │
        ▼
Google Gemini
        │
        ▼
Summary Generation
        │
        ├───────────────┐
        ▼               ▼
Google Docs       Summary Output
        │
        ▼
User Receives Results
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
| Workflow | n8n |
| Speech-to-Text | Groq Whisper |
| LLM | Google Gemini |
| Storage | Google Docs API |
| Programming | JavaScript |

---

# 📂 Repository Structure

```text
Transcription Summarizer
│
├── README.md
├── Transcription Summarizer Agent.json
│
└── images
    ├── architecture.png
    ├── workflow.png
    └── demo.gif
```

---

# 🚀 How It Works

1. User uploads an audio file.
2. Groq Whisper converts speech into text.
3. Gemini analyzes the transcript.
4. A structured summary is generated.
5. A Google Doc is created automatically.
6. Transcript and summary are stored.
7. The document link and summary are returned to the user.

---

# 🎯 Example Prompt

```text
Summarize this lecture recording and save it to Google Docs.
```

---

# 💼 Use Cases

- 🎓 Lecture Notes
- 💼 Meeting Summaries
- 🎤 Interview Analysis
- 🎙️ Podcast Notes
- 📚 Study Material
- 📰 Research Discussions

---

# 🔮 Future Improvements

- Speaker diarization
- Multi-language transcription
- Timestamped summaries
- PDF export
- Meeting action tracker
- Notion integration

---

# 📄 License

MIT License
