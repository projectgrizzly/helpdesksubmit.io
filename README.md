# HelpDesk — Public Submission Form

Standalone public-facing ticket submission form for the HelpDesk system.

## Setup

No build step required. Open `index.html` directly or deploy to any static host.

## Deploy to Netlify

1. Push this repo to GitHub
2. Go to app.netlify.com → **Add new site → Import from GitHub**
3. Select this repo — no build settings needed
4. Site goes live instantly at `yoursite.netlify.app`

## Supabase

The form writes directly to your Supabase `tickets` table using the anon key baked into `index.html`. To update the key, edit the `SUPABASE_KEY` variable at the bottom of `index.html`.

## Admin Dashboard

The admin dashboard lives in a separate repo: `helpdesk-admin`
