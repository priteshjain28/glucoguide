GlucoGuide — how to install it as an Android app
=================================================

Chrome only offers app installation for pages served from a real https://
address (not for files opened from Downloads). So host these files for free
once, then install. Total time: about 5 minutes.

OPTION A — GitHub Pages (free, permanent, recommended)
1. Go to github.com and create a free account (skip if you have one).
2. Tap "+" → "New repository". Name it e.g.  glucoguide  → Create.
3. In the repo, tap "Add file" → "Upload files" and upload ALL files in
   this folder: index.html, manifest.webmanifest, sw.js, and the 3 icons.
   Commit the upload.
4. Repo → Settings → Pages → Source: "Deploy from a branch" →
   Branch: main, folder: / (root) → Save.
5. Wait ~1 minute. Your app is live at:
   https://YOUR-USERNAME.github.io/glucoguide/
6. Open that link in Chrome on your phone →
   ⋮ menu → "Add to Home screen" → Install.
   GlucoGuide now appears in your app drawer like a normal app.

OPTION B — Netlify Drop (fastest)
1. Go to app.netlify.com/drop and sign in free.
2. Drag/upload this whole folder. You get a https://something.netlify.app link.
3. Open it in Chrome on your phone → ⋮ → Add to Home screen → Install.

After installing:
- Works fully offline (the service worker caches everything on first load).
- All health data is stored ONLY on your phone, never uploaded anywhere.
- The website itself contains no data — so the link being public is fine;
  anyone opening it just gets their own empty copy.
- Back up occasionally with Settings → Export readings (CSV).
- Don't use Chrome's "Delete browsing data" for this site, or your local
  data is erased.
