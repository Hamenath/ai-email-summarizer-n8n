# 📧 AI Email Summarizer using n8n

An AI-powered workflow built with n8n that automatically summarizes incoming Gmail messages using Google Gemini AI and sends the summary to Telegram.

## 🚀 Features

- 📩 Detects new Gmail messages automatically
- 🤖 Summarizes emails using Google Gemini AI
- 📱 Sends summaries directly to Telegram
- ⚡ Fully automated workflow using n8n

## 🛠️ Tech Stack

- n8n
- Gmail Trigger
- Google Gemini 2.5 Flash
- Telegram Bot API
- Google OAuth

## 📂 Workflow

```
Gmail Trigger
      │
      ▼
Basic LLM Chain
      │
      ▼
Google Gemini Chat Model
      │
      ▼
Telegram Send Message
```

## 📸 Demo

(Add screenshots here)

- Workflow Screenshot
- Telegram Output
- Gmail Trigger

## ⚙️ Setup

1. Clone the repository.
2. Import the workflow into n8n.
3. Configure Gmail OAuth credentials.
4. Configure Google Gemini API Key.
5. Create a Telegram Bot using BotFather.
6. Add your Telegram Chat ID.
7. Activate the workflow.

## 🎯 Result

Whenever a new email arrives:

1. Gmail detects it.
2. Gemini summarizes the email.
3. Telegram sends the AI-generated summary.

## 📜 License

MIT
