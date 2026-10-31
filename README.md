# MealSignal

Full-stack meal planning and feedback for hostel messes, tiffin providers and small caterers.

## Source download
Download [`MealSignal-source-code.zip`](MealSignal-source-code.zip), extract it, then follow `README.md` inside the archive for Supabase configuration and local setup.

The archive includes the complete Next.js and Supabase source. Local `.env.local`, dependencies and build caches are excluded. The course report is maintained in the project folder separately. Demo analytics use simulator-labelled records; optional AI insights fall back to local keyword grouping when no provider API key is configured.

## Technology
Next.js 16 App Router, React 19, TypeScript, Supabase Auth/PostgreSQL/RLS, Next.js Route Handlers and an optional OpenAI-compatible LLM API.