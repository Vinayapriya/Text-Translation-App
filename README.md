# Between ↔

**A little less lost in translation.**

A minimal text-translation app for English, Malayalam, Hindi, and Tamil, built with Streamlit and the Gemini API.

## Features

- Side-by-side original text and translation.
- Language selection and direction swapping.
- Translate using the button or Ctrl+Enter.
- Download translations as UTF-8 text files.
- Input validation and helpful API error messages.

## Tech Stack

Python 3.11 · Streamlit · Gemini API · Requests · CSS

## Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/Vinayapriya/Text-Translation-App.git
cd Text-Translation-App
```

### 2. Install dependencies

**Windows:**

```powershell
py -3.11 -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

**macOS / Linux:**

```bash
python3.11 -m venv .venv
.venv/bin/python -m pip install -r requirements.txt
```

### 3. Add your API key

Create a key in [Google AI Studio](https://aistudio.google.com/apikey).

Create `.streamlit/secrets.toml` inside the project folder:

```toml
GEMINI_API_KEY = "your-api-key"
```

Keep this file in `.gitignore`. Never commit your API key.

### 4. Start the app

**Windows:**

```powershell
.\.venv\Scripts\python.exe -m streamlit run app.py
```

**macOS / Linux:**

```bash
.venv/bin/python -m streamlit run app.py
```

Open http://localhost:8501 in your browser.

