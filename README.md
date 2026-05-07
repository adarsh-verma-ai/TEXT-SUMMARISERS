# 🎥 AI YouTube Video Analyzer

An AI-powered web app that analyzes any YouTube video and generates a structured report — including timestamps, topic breakdowns, and key learning points — using an intelligent agent built on OpenAI and the agno framework.

---

## 🚀 What It Does

Paste any YouTube video URL and the app will:

- Generate a **full video overview** (length, type, structure)
- Create **precise timestamps** with detailed segment summaries
- **Organize content** by themes and topic progression
- Highlight **key learning points** and practical demonstrations

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | Streamlit |
| AI Agent | agno framework |
| Language Model | OpenAI GPT |
| Transcript Extraction | youtube-transcript-api |
| Config | python-dotenv |

---

## 📁 Project Structure

```
TEXT-SUMMARISERS-main/
├── app.py                 # Streamlit frontend
├── youtube_analyzer.py    # AI agent logic
└── requirements.txt       # Dependencies
```

---

## ⚙️ Setup & Installation

### 1. Clone the repository
```bash
git clone https://github.com/your-username/youtube-video-analyzer.git
cd youtube-video-analyzer
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Set up environment variables
Create a `.env` file in the root directory:
```
OPENAI_API_KEY=your_openai_api_key_here
```

### 4. Run the app
```bash
streamlit run app.py
```

---

## 🖥️ How to Use

1. Open the app in your browser (default: `http://localhost:8501`)
2. Paste a YouTube video URL into the input field
3. Click **Analyze Video**
4. Get a full structured analysis report instantly

---

## 📊 Sample Output

The analyzer generates reports like:

```
📌 Video Overview
- Type: Technical Tutorial
- Length: 45 minutes
- Structure: Introduction → Core Concepts → Demo → Summary

⏱️ Timestamps
[00:00 - 02:30] Introduction and setup
[02:30 - 15:00] Core concept explanation
[15:00 - 35:00] Live demonstration
[35:00 - 45:00] Summary and next steps

🔑 Key Learning Points
- Point 1
- Point 2
- Point 3
```

---

## 📦 Requirements

```
streamlit
python-dotenv
agno
openai>=1.0.0
youtube-transcript-api
pytube
```

---

## 🔮 Future Improvements

- [ ] Support for multiple videos at once
- [ ] Export analysis as PDF
- [ ] Add multilingual transcript support
- [ ] Compare two videos side by side

---

## 👤 Author

**Adarsh Verma**
- LinkedIn: [linkedin.com/in/adarshverma-84499b394](https://www.linkedin.com/in/adarsh-verma-84499b394/)
- GitHub: [github.com/your-username](https://github.com/adarsh-verma-ai)

---


