# MealSignal

Full-stack meal planning and feedback for hostel messes, tiffin providers and small caterers.

## Source download
Download [`MealSignal-source.zip`](MealSignal-source.zip), extract it, then follow the local setup in README.md inside the archive.

The archive includes the complete Next.js and Supabase project plus the ICT3131 report. Local `.env.local`, dependencies and build caches are excluded. Demo analytics use simulator-labelled records; optional AI insights fall back to local keyword grouping when no provider API key is configured.

## Technology
Next.js 16 App Router, React 19, TypeScript, Supabase Auth/PostgreSQL/RLS, Next.js Route Handlers and an optional OpenAI-compatible LLM API.