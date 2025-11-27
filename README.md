# SynapMeet

SynapMeet is an AI-powered meeting assistant that converts meeting audio into:
- Transcript  
- Summary  
- Action items  
- Decisions  

It is built using **Flask**, **WhisperX**, and **Transformers NLP**.

---

## 🚀 Features
- Upload WAV/MP3 meeting audio
- Automatic speech-to-text using WhisperX
- NLP summarization using Transformers
- Action item extraction
- Simple and clean Flask UI

---

## 📁 Project Structure
synapmeet/
│ app.py
│ requirements.txt
│ README.md
│ .gitignore
│
├── samples/
│   └── uploaded_audio.wav
│
├── static/
│   └── style.css
│
└── templates/
    ├── index.html
    ├── upload.html
    ├── meeting.html
    ├── result.html
    └── history.html

