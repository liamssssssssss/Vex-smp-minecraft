# VEX SMP — Complete Website Starter

Production-oriented Next.js App Router site for VEX SMP.

## Included
- Responsive dark VEX design with glass panels, grid/noise background and subtle motion
- Home, Play, Rules, Wiki, Store, Ranks, Leaderboards, player profiles, News, Events, Discord, Support, Staff, Commands, Achievements, Status, Admin, Login, Register, Profile, Privacy and Terms
- Functional copy-IP button, mobile navigation, store cart counter, rank selection, support state, search interaction
- API route for server status
- Environment variable structure for PostgreSQL, Minecraft, Discord, Tebex, auth and Dynmap/BlueMap
- Dynamic `/players/[username]` and `/news/[id]` routes

## Run locally
```bash
npm install
npm run dev
```

## Production integrations
Use PostgreSQL for players/news/events/tickets/products and add server-side API adapters for Minecraft status, Discord, Tebex webhooks/checkout, authentication and BlueMap/Dynmap. Keep all private tokens in Vercel environment variables.

The current Minecraft IP is intentionally `play.example.com`, matching the supplied brief. Replace it with the real server host before launch.
