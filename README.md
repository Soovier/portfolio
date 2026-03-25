# Capstone Portfolio — Stephen Osunkunle

This is my capstone portfolio, built as a single HTML file. I kept it simple on purpose — no frameworks, no build tools, just HTML, CSS, and a bit of vanilla JS. You can open it in a browser or host it anywhere.

---

## How to Run It

Just open `index.html` in a browser. That's it.

If you want a local server for some reason:

```bash
python3 -m http.server 8000
```

Then go to `http://localhost:8000`.

---

## How to Deploy

I used Netlify since it's the fastest option. You just drag the file onto the dashboard and it gives you a live URL. No account setup needed beyond signing up.

If you'd rather use GitHub Pages:

1. Push `index.html` to a repo
2. Go to Settings → Pages
3. Set the source to your main branch
4. It'll be live at `https://yourusername.github.io/repo-name`

---

## What's in the Portfolio

Three projects are featured:

- **SxS Scripting Frontend** — community site for a 10,000+ member Luau/Roblox dev community I founded
- **UMCES eDNA Analysis Tool** — research tool I built in Java and Rust during my internship at the UMD Appalachian Laboratory
- **SXM Trading & Journal Platform** — a live day trading journal and leaderboard app I built and deployed at sxm-leaderboard.org

Beyond the projects, the site also covers my experience at Beachify Inc. and UMCES, my education at Frostburg, and contact info.

---

## File Structure

```
portfolio/
└── index.html
```

Everything is self-contained. Fonts are pulled from Google Fonts so you need an internet connection for those to load, but the rest works offline.
