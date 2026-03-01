# EchoSphere AI – Real-Time AI Agent Video Call Platform

SaaS for intelligent video calls: custom AI agents join live (tutor, sales assistant), auto post-call summaries, transcripts, recordings, contextual Q&A.

## Features
- Real-time video with AI agent participation (Stream SDK)
- Background jobs for summaries/transcripts (Inngest)
- Searchable transcripts + AI-powered meeting Q&A
- Subscription model & multi-tenant auth

## Tech Stack
- Frontend: Next.js 15 + React 19, Tailwind
- Video: Stream Video SDK
- AI: OpenAI Realtime API
- Backend: Neon + Drizzle ORM, tRPC, Inngest
- Auth: Better Auth / Clerk
- Deploy: Vercel

## Run Locally
1. Clone repo
2. `npm install`
3. Set env vars (API keys, DB)
4. `npm run dev`

## Screenshots
![Video Call](screenshots/call.png)  
![Post-Call Summary](screenshots/summary.png)

## License
MIT

Excited to discuss real-time AI – reach out!
