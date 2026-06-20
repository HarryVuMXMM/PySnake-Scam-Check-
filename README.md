# ScamCheck

A simple Flask hackathon app for checking suspicious Vietnamese messages, links, screenshots, and voice text with Gemini.

## Run locally

```powershell
pip install -r requirements.txt
python app.py
```

Open http://localhost:5000/

Put your Gemini key in `.env` as `GEMINI_API_KEY=...`. Do not commit `.env`.
