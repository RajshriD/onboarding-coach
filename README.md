# Onboarding Coach — Vercel Edition

Standalone Next.js version of the Claude Onboarding Coach artifact.

## Deploy
1. Import this folder/repository into Vercel.
2. Add `AI_GATEWAY_API_KEY` as a Vercel Secret in Project Settings → Environment Variables.
3. Redeploy.
4. The app uses Vercel AI Gateway with `anthropic/claude-sonnet-4.5`.

## Important
This first standalone version uses browser localStorage for policies and HR reports, so data is local to the browser. For a production multi-user HR product, replace localStorage with a shared database and add authentication/authorization.
