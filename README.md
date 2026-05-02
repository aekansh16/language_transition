# Task 1: Language Translation Tool

## Overview
A web-based language translation tool that supports 100+ languages using Google Translate API (via `deep-translator`). Built with Flask for the backend and a clean, responsive HTML/CSS/JS frontend.

## Features
- Translate text across 100+ languages
- Auto-detect source language
- Swap source and target languages
- Copy translated text to clipboard
- Text-to-Speech (TTS) for listening to translations
- Character counter (up to 5000 chars)
- Keyboard shortcut: `Ctrl + Enter` to translate

## Tech Stack
- **Backend**: Python, Flask
- **Translation**: `deep-translator` (Google Translate API wrapper — no API key needed)
- **Frontend**: HTML, CSS, JavaScript (Web Speech API for TTS)

## Setup & Run

```bash
# 1. Install dependencies
pip install -r requirements.txt

# 2. Run the Flask app
python app.py

# 3. Open browser at
http://localhost:5001
```

## Project Structure
```
task1_language_translation/
├── app.py              # Flask backend with /translate endpoint
├── templates/
│   └── index.html      # Frontend UI
├── requirements.txt
└── README.md
```
