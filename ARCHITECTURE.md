# Public Architecture Overview

ChessPlay is organized around three repository boundaries:

## chessplay-enterprise

Private production source for frontend, backend, auth, admin, payments, referrals, database models, Socket.IO game services, automation, and deployment configuration.

## chessplay-showcase

Public frontend-only portfolio/demo repository. It contains safe UI and local gameplay surfaces only.

## chessplay-docs

Public documentation repository with roadmap, changelog, setup notes, security guidance, and high-level architecture.

## Boundary Rules

- Public repos may describe features at a high level.
- Public repos must not expose backend source, database internals, admin workflows, payment internals, production secrets, or private deployment details.
- Placeholder environment files are allowed only when they contain no real credentials.

