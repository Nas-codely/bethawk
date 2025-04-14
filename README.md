# BetHawk

An automated sports betting analysis platform with accumulator generation using FastAPI, Node.js, and React.

## Features

- Scrapes odds from 1xBet using Puppeteer
- Scores matches with AI xG-based confidence
- Builds only 95%+ guaranteed accumulators
- Frontend dashboard with filtering and sorting
- Auto-refresh every hour

## Structure

- `backend/api/`: FastAPI backend
- `backend/scraper/`: Node.js + Puppeteer scraper
- `frontend/`: React dashboard

## Deployment

- Deploy `frontend/` to Vercel or Netlify
- Deploy `backend/api/` to Render or Fly.io
- MongoDB recommended: MongoDB Atlas

## Env Variables

Create a `.env.production` in `frontend/`:
```
VITE_API_URL=https://your-backend-api-url
```

In backend/api, use:
```
MONGO_URI=your_mongodb_uri
```

---

Made by Mehdi + Dan 🤝
