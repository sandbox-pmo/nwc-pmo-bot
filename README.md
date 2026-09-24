NWC PMO Bot — Free Webpage Deployment
======================================

This folder contains one file: index.html. It is a complete, self-contained
webpage (all data and logic is embedded — no server, database, or API key
needed). Publishing it makes the bot available at a URL you control, not a
claude.ai link.

Data snapshot: 17 Sep 2026, Northwestern Cluster (Madinah & Tabuk), 82 projects.
To refresh later, just re-send Claude your latest PMO Live extract, ask for
an updated index.html, and re-upload it using the same steps below (it will
overwrite the old one — the URL stays the same).


OPTION A — Netlify Drop (fastest, ~2 minutes, free forever)
-------------------------------------------------------------
1. Go to https://app.netlify.com/drop in a browser (on your laptop, not
   your phone, for this one-time step).
2. Sign up for a free account if prompted (email, or continue with GitHub/
   Google — no credit card needed).
3. Drag this whole folder (the one containing index.html) onto the page.
4. Netlify gives you a live URL immediately, e.g.
   https://random-name-1234.netlify.app
5. Optional: in Site settings > Change site name, pick something memorable,
   e.g. https://nwc-pmo-bot.netlify.app
6. Open that URL on your phone, then "Add to Home Screen" (see below).

To update later: go to your site's Netlify dashboard > Deploys > drag the
new folder in again. Takes 10 seconds, same URL.


OPTION B — GitHub Pages (if you already use GitHub)
-------------------------------------------------------------
1. Create a new PUBLIC repository on github.com, e.g. "nwc-pmo-bot".
2. Upload index.html to it (GitHub's web UI: Add file > Upload files).
3. Go to Settings > Pages > Source > Deploy from branch > main > / (root) >
   Save.
4. After ~1 minute your site is live at:
   https://<your-username>.github.io/nwc-pmo-bot/
5. To update later: upload the new index.html to the same repo, overwriting
   the old one (GitHub Pages redeploys automatically in ~1 minute).


ADD IT TO YOUR PHONE'S HOME SCREEN (either option above)
-------------------------------------------------------------
- iPhone (Safari): open the URL > Share icon > "Add to Home Screen"
- Android (Chrome): open the URL > ⋮ menu > "Add to Home screen" / "Install app"

You'll get a "PMO Bot" icon that opens full-screen, no browser bar. From
there: tap the icon, type a project number or a few keywords, get the card.


NOTES
-------------------------------------------------------------
- Both options are genuinely free with no time limit for a static site
  like this one (no ongoing cost, no credit card).
- Nothing here needs a database, backend, or ongoing hosting bill — it's
  the same kind of "one HTML file" you could also just email to a colleague
  and they could open it locally, though a hosted URL is easier to bookmark
  and share.
- If you'd like a proper custom domain (e.g. pmo.irolys.com) instead of a
  *.netlify.app / *.github.io address, both Netlify and GitHub Pages support
  connecting one you already own, free of charge (you'd only pay your
  existing domain registrar, not Netlify/GitHub).
