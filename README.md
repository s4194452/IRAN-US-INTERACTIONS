# Flask App (initial scaffold)

This repository contains a minimal Flask application scaffold with four pages and empty content placeholders.

Quick start

1. Create a virtual environment and activate it:

```bash
python3 -m venv venv
source venv/bin/activate
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the app:

```bash
python run.py
```

Open http://127.0.0.1:5000/ in your browser.

Files of note

- `run.py` – entrypoint to start the app.
- `app/__init__.py` – application factory.
- `app/routes.py` – four page routes (`/`, `/about`, `/contact`, `/dashboard`).
- `templates/` – HTML templates (base + pages).
- `static/css/style.css` – minimal stylesheet.
