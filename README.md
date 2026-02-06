# SteeleHacks

A real-time competitive platform built at SteeleHacks. Features user authentication, leaderboards, round management, and live stats.

## Tech Stack

- **Frontend**: Next.js 14, React, TypeScript, Tailwind CSS
- **Backend**: PocketBase (embedded SQLite database + auth)
- **UI**: shadcn/ui components

## Features

- User registration and authentication (PocketBase auth)
- Round-based competition management
- Real-time leaderboards and stats dashboard
- Admin controls for managing rounds and users
- Responsive design

## Getting Started

```bash
npm install
npm run dev
```

The app runs at `http://localhost:3000`. PocketBase backend runs on port `8090`.

## Project Structure

```
src/
  app/           # Next.js pages (login, signup, stats, table, settings)
  components/    # React components (UI kit + custom)
  lib/           # Auth helpers, PocketBase client
pb_migrations/   # PocketBase schema migrations
```
