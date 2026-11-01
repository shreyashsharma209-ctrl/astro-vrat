# 🌙 AstroVrat · CelestialFest

Sun, moon and festival tracker for Indian families. One file, no build step, works offline.
सूरज, चाँद और त्योहारों का ट्रैकर, पूरे परिवार के लिए।

## Features
- Sunrise / sunset / moonrise / moonset, moon phase, approximate tithi
- Live countdown to next moonrise and to festivals
- Family city tracker (about 190 Indian cities) with WhatsApp share
- Moon phase explorer, animated sky with shooting stars
- Diya, temple bell, shankh, pooja checklist
- English and Hindi

## Run locally
Open `index.html` in any browser.

## Host free on GitHub Pages
1. Create a new repository on GitHub (for example `astrovrat`).
2. Upload `index.html`, `README.md` and `.nojekyll`.
3. Go to **Settings → Pages**.
4. Under **Branch**, choose `main` and folder `/ (root)`, then **Save**.
5. After a minute your site is live at `https://<your-username>.github.io/<repo-name>/`.

## Notes
- Times are calculated in the browser with a low-precision formula and can be off by a few minutes.
- Tithi and festival dates are approximate. Check your local panchang for exact muhurat.
- To edit festivals, change the `FEST` list in `index.html`. To add cities, add entries to the `MORE` string.
- The in-page AI assistant only works inside Claude, so it is hidden automatically on GitHub Pages.
