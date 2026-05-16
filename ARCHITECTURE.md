# Architecture Overview

## High-Level Flow

Frontend (React + Vite)
↓
REST API + Socket.IO
↓
Node.js + Express
↓
MongoDB / PostgreSQL
↓
Prisma Migration Layer

---

## Components

Frontend:
- dashboard
- gameplay
- premium
- profile
- multiplayer UI

Backend:
- auth
- game engine
- socket server
- premium logic
- referral logic

---

## Deployment

Frontend:
Vercel

Backend:
Render

CI/CD:
GitHub Actions
