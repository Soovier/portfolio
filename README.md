# Stephen Osunkunle — Capstone Portfolio

A professional single-page portfolio website built with pure HTML, CSS, and JavaScript. No dependencies, no build step required.

---

## 🚀 Quick Deploy (Pick One)

### Option 1 — GitHub Pages (Recommended, Free)

1. Create a new repo on GitHub named `portfolio` (or any name)
2. Upload `index.html` to the repo
3. Go to **Settings → Pages**
4. Set source to `main` branch, `/ (root)` folder
5. Click **Save** — your site will be live at:
   `https://yourusername.github.io/portfolio`

### Option 2 — Netlify (Drag & Drop, Free)

1. Go to [netlify.com](https://netlify.com) and sign up/log in
2. On the dashboard, drag the `index.html` file into the deploy box
3. Done — instant live URL provided automatically

### Option 3 — Vercel (Free)

1. Go to [vercel.com](https://vercel.com) and sign up/log in
2. Click **Add New → Project**
3. Upload the `index.html` file or connect your GitHub repo
4. Deploy — live URL provided automatically

### Option 4 — Local Preview

Open `index.html` directly in any browser — no server needed.

```bash
# On Mac
open index.html

# On Windows
start index.html

# With Python (optional local server)
python3 -m http.server 8000
# Then visit http://localhost:8000
```

---

## 📁 File Structure

```
portfolio/
└── index.html    ← entire portfolio (self-contained)
```

Everything is in a single file — fonts load from Google Fonts CDN, no other dependencies.

---

## ✏️ Customizing

All content is plain HTML. Search for these sections in `index.html` to edit:

| Section | What to update |
|---|---|
| `#hero` | Name, tagline, stats |
| `#about` | Bio text, skill tags |
| `#experience` | Job entries, dates, bullets |
| `#projects` | Project cards, links, tech badges |
| `#education` | Degree info, activities |
| `#contact` | Email, phone, social links |

Colors are set as CSS variables at the top of `<style>`:
```css
--accent: #e8c97a;   /* gold highlight */
--bg: #0a0a0b;       /* dark background */
```

---

## ✅ Capstone Requirements Fulfilled

- ✅ Professional Documents (resume info embedded)
- ✅ Artifact 1: SxS Scripting Frontend (GitHub)
- ✅ Artifact 2: UMCES eDNA Analysis Tool (GitHub)
- ✅ Artifact 3: SXM Leaderboard (Live deployment)
- ✅ All artifacts documented with description, tech stack, and links
- ✅ Publicly accessible (no login required)
