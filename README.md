# Synchro-Strike Nexus

A browser-based web platform for the tactical turn-based game *Synchro-Strike*. The platform includes a matchmaking lobby, an AI Tactical Advisor, a cosmetics store, and a player profile with ML-based win probability prediction.

## Team

* Daniil Bratochkin — Team Lead + Backend / Game Logic
* Miras Nusupov — Frontend + UI/UX / Game Client
* Zhakiyan Bakhtiyaruly — ML-AI + Database

## Stack

* **Frontend:** Vue 3 + Vite
* **Backend:** Python + FastAPI
* **Database:** SQLite (development) / PostgreSQL (production)
* **AI Agent:** Google Gemini (free tier)
* **ML:** scikit-learn (win probability prediction)
* **Payment:** YooKassa Demo Store

## Project Structure

* `frontend/` — Vue 3 application (lobby, profile, store, AI chat).
* `backend/` — FastAPI server (auth, matchmaking, AI integration, payment webhooks).
* `ml/` — ML scripts (scikit-learn model) and prompt templates.
* `docs/` — project documentation.
