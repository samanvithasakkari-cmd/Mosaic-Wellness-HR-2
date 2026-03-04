# Mosaic Talent — AI Recruitment Platform

Single-file Flask app. No build step. Deploy anywhere in 2 minutes.

## Run Locally
```bash
pip install flask openpyxl gunicorn
python app.py
# → http://localhost:5000
```

## Deploy to Railway
1. Push this folder to GitHub
2. railway.app → New Project → Deploy from GitHub
3. Done. Live in ~2 minutes.

## Deploy to Render / Heroku / Fly.io
- Build: `pip install -r requirements.txt`  
- Start: `gunicorn app:app --bind 0.0.0.0:$PORT`

## Files
- `app.py` — entire application (backend + frontend embedded)
- `requirements.txt` — 3 dependencies
- `Procfile` — production start command
