# Setup Guide

ChessPlay is developed as a React frontend with a private production backend. The public showcase can run locally without backend access.

## Public Showcase

```bash
npm install
npm run dev
```

## Production Source

The full production source belongs in the private `chessplay-enterprise` repository. Keep environment variables in deployment providers or local `.env` files only.

Never commit `.env`, service-account JSON files, private keys, database URLs, SMTP passwords, payment secrets, or JWT secrets.

