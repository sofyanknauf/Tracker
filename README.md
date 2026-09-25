# Life log

Personal tracker: food, water, workouts, meds & blood work, check-ins, habits, trading, money and goals.
Data syncs between devices through Supabase (table `lifelog_docs`, protected per user with row-level security).
Food lookup runs through the Supabase Edge Function `lifelog-nutrition`.

## Put it online with GitHub Pages
1. Create a new repository on github.com, e.g. `lifelog`.
2. Upload everything in this folder (index.html, manifest.webmanifest, sw.js, README.md and the icons folder).
3. Settings → Pages → Deploy from a branch → branch `main`, folder `/ (root)` → Save.
4. Live after a minute at `https://<your-username>.github.io/lifelog/`.

## Install on iPhone
Open the link in Safari → Share → Add to Home Screen.

## Food lookup
Add your Anthropic API key once: Supabase dashboard → Edge Functions → Secrets → `ANTHROPIC_API_KEY`.
