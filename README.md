
# Text to Speech App (IBM Watson)

## 🧪 Backend (Flask)

### Setup

```bash
cd backend
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
pip install -r requirements.txt
python app.py
```

This runs the Flask server at `http://localhost:5000`.

## 💻 Frontend (V0.dev-based)

```bash
cd frontend
pnpm install   # or npm install / yarn
pnpm dev       # or npm run dev
```

Visit `http://localhost:3000` in your browser.

## 📦 Features

- Enter text and click **Generate Audio**
- Backend returns `.mp3` from IBM Watson
- Preview in `<audio>` player
- Download the result

---
