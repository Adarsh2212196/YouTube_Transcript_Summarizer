# 🎥 YouTube Transcript Summarizer

The *YouTube Transcript Summarizer* is a Flask-based web application that extracts the transcript of any YouTube video (if available) and summarizes the content using a powerful AI model (DistilBART). This tool helps users quickly understand the content of long videos without watching them fully.

---

## ✨ Features

- 🔗 Accepts YouTube video links
- 📜 Extracts full video transcripts
- 🤖 Summarizes the transcript using a transformer-based NLP model
- 🖥 Simple and clean web interface
- 🌐 No need for API keys — works out of the box

---

## 🚀 Demo

> 🧪 Localhost demo after running
> http://127.0.0.1:5000/

> pip install -r requirements.txt initial requirements.

## 📦 Tech Stack

- *Frontend*: HTML (Jinja2 templates via Flask)
- *Backend*: Python + Flask
- *AI Model*: sshleifer/distilbart-cnn-12-6 via Hugging Face Transformers
- *Transcript Fetching*: youtube-transcript-api

