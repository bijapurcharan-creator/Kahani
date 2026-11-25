# 🎬 KAHANI (कहानी - Story)

AI-powered multilingual content creation toolkit for creators.

## What is KAHANI?

KAHANI helps content creators generate:
- ✅ Professional video scripts (5 min generation)
- ✅ SEO keywords + metadata
- ✅ Thumbnail design concepts (5 options)
- ✅ Social media captions (all platforms)

**For whom?** YouTubers, bloggers, newsletter writers, TikTok creators

**Languages:** Hindi, Spanish (LATAM), Portuguese (Brazil), Tamil, English

**Launch:** August 10, 2026

---

## Project Structure

kahani/
├── backend/              # FastAPI backend
│   ├── app/
│   │   ├── routes/
│   │   ├── models/
│   │   └── schemas/
│   ├── tests/
│   ├── main.py
│   ├── config.py
│   └── requirements.txt
├── frontend/
│   ├── public/
│   ├── src/
│   └── package.json
├── docs/
│   ├── API.md
│   └── DATABASE.md
├── .gitignore
├── LICENSE
└── README.md

---

## Tech Stack

**Backend:** FastAPI, SQLAlchemy, PostgreSQL, Pydantic, Claude API, Stripe
**Frontend:** React, TypeScript, Tailwind CSS, Axios, Vite
**DevOps:** Docker, GitHub Actions, Railway, PostgreSQL

---

## Getting Started

### Backend Setup
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload

**Server:** http://localhost:8000
**API Docs:** http://localhost:8000/docs

### Frontend Setup
cd frontend
npm install
npm run dev

**Server:** http://localhost:5173

---

## Development Workflow

git checkout -b feature/your-feature-name
# ... make changes ...
git add .
git commit -m "Add your feature description"
git push origin feature/your-feature-name

---

## License

MIT License - See LICENSE file for details.

---

**Let's build KAHANI! 🎬🚀**
