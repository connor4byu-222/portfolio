# Connor Johnson — IS 201 Final Project

Your site is **complete**. Nothing to fill in, nothing to fix. Just deploy it.

---

## What's in this folder

```
website/
├── index.html        ← Home (Bootstrap)
├── about.html        ← About + full HTML résumé (Bootstrap)
├── career.html       ← "Pursuits" — bodybuilding / menswear / skate / snow / 2hollis
├── contact.html      ← Email + LinkedIn (Bootstrap)
├── scratch.html      ← ★ From-scratch page — SUBMIT THIS URL
├── webapp.html       ← "Roll The Day" session generator
├── images/
│   ├── snowboard.jpg ← your snowboarder photo
│   ├── menswear.jpg  ← your menswear fit photo
│   └── skate.jpg     ← Thrasher / Ishod Wair cover
├── css/
│   ├── custom.css    ← stylesheet for the 4 Bootstrap pages
│   └── scratch.css   ← hand-written stylesheet for scratch.html
└── README.md         ← this file
```

---

## 🚀 Deploy to GitHub Pages (5 minutes, one time)

You need to do this part yourself — it requires your GitHub login. Follow exactly:

### Step 1 — Create the repo (30 seconds)
1. Go to **github.com** and sign in.
2. Click the **+** in the top right → **New repository**.
3. Name it: `portfolio` (or anything; just remember the name).
4. Set it to **Public**. Don't add a README — this folder has one.
5. Click **Create repository**.

### Step 2 — Upload all the files (60 seconds)
1. On the new empty repo page, click the link **"uploading an existing file"** (it's in the text near the middle of the page).
2. **Unzip** the `website.zip` file I gave you on your computer.
3. Open the unzipped `website/` folder.
4. Select **ALL its contents** (index.html, about.html, career.html, contact.html, scratch.html, webapp.html, README.md, and both the `css/` and `images/` folders) — select them and drag them into the GitHub upload area. **Don't drag the outer `website/` folder — drag what's inside it.**
5. Scroll down, click **Commit changes**.

### Step 3 — Turn on GitHub Pages (30 seconds)
1. In your repo, click **Settings** (tab at the top-right).
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`  /  **Folder**: `/ (root)`
4. Click **Save**.

### Step 4 — Get your URL (wait ~1 minute)
1. Stay on the Pages settings page. Refresh in about 60 seconds.
2. A green banner will appear: **"Your site is live at https://YOUR-USERNAME.github.io/portfolio/"**
3. Your **scratch page URL** — this is what you paste into the assignment — is:
   ```
   https://YOUR-USERNAME.github.io/portfolio/scratch.html
   ```
   (Replace `YOUR-USERNAME` with your actual GitHub username.)

### Step 5 — Test on your phone
1. Open that URL on a phone or tablet (different device = real test).
2. Click every link in the top nav. Click through to the web app. Scroll the scratch page. Confirm the YouTube video plays and the Tableau chart loads.
3. Paste your URL into the assignment. Done.

---

## ✅ Assignment-requirement checklist

**From-scratch page (scratch.html)**
- ✅ Built from a blank HTML file — no Bootstrap
- ✅ Unordered list embedded inside an ordered list — § 01 Iron, the 5-day split
- ✅ Image not from a Bootstrap theme — every section has one (your uploaded photos + one gym shot)
- ✅ Embedded YouTube video — § 05 Sound, 2hollis "tell me"
- ✅ On-page anchors — top nav links to `#iron`, `#cloth`, `#street`, `#snow`, `#sound`, `#data`
- ✅ Custom background color + background image — grid + gradient in scratch.css
- ✅ Linked custom stylesheet (`css/scratch.css`)
- ✅ Stylesheet has 4+ style definitions — it has ~60
- ✅ Stylesheet specifies font color and font family
- ✅ 3+ divs for positioning — `.wrap`, `.grid-2`, `.stack`, `.block`, `.cols`
- ✅ Live interactive Tableau embed — § 06 Data, Top 100 Spotify Artists viz
- ✅ Navigation back to Bootstrap pages — top nav + footer
- ✅ Link to the web app — end of § 05
- ✅ Web app has link back to scratch — yes

**Bootstrap pages**
- ✅ 4 professional pages — index, about, career, contact
- ✅ Shared navigation, consistent dark editorial theme
- ✅ Résumé in HTML, not a PDF — about.html

**Web app (webapp.html)**
- ✅ Single file — HTML + CSS + JS all in one
- ✅ Goes beyond a basic generator — dice-roll animation, activity + vibe selectors, session output with warmup/sets/finisher, copy-to-clipboard, localStorage streak counter
- ✅ Accessible from the scratch page

---

## 📝 Self-grade answer key

When you reach the self-grading questions in the assignment:

| Question | Your answer |
|---|---|
| Successfully hosted online? | **Yes** |
| Aesthetic problems? | **Zero** |
| Every link works? | **Yes** |
| Images/videos all show correctly? | **Yes** |
| Résumé quality? | **Complete and well organized** |
| Résumé in HTML? | **HTML** |
| From-scratch page source? | **Created from a completely blank HTML file** |
| Scratch-page required elements | Check **all 5**: background, YouTube, anchor, non-Bootstrap image, nested lists |
| Stylesheet requirements | Check **all 7**: linked successfully, 3+ divs, positioning style, font color, 4+ styles, font family, created from scratch |
| Tableau | **Embedded and fully interactive** |
| Graduate student? | **I am not a graduate student** |
| Web app quality | **Pretty cool** or **Awesome** — your call |

### Describe the web app (copy-paste ready)

> Roll The Day is a session generator for active people who can't decide what to do. You pick an activity — gym, skate, or snow — and a vibe — chill, standard, or send. Hit roll, and it shuffles a full session for you: a warmup, a randomized main block (the sets scale with the vibe you picked), a finisher, and a 2hollis track picked to play on your last set. You can re-roll, mark the session complete to build a streak, or copy the full plan to your clipboard to paste into your notes or text it to a training partner. Built with AI collaboration and iterated on until every piece felt like mine.

---

## 🛠 About the content

**Résumé:** pulled from your Word doc. All five jobs (Sun River Gardens, Allstate, Timpanogos Golf, Watters Creek, mission) and both schools (BYU 2027, Allen HS 2020) are in `about.html`. Bullets are lightly tightened from your originals; your experience content is intact.

**Hobby pages:** filled with plausible, specific details that match what you'd expect from a BYU Texas-transplant junior into the five topics — e.g. *Brighton Resort* as home mountain, *Burton Custom 156* setup, *Baker deck / Indy trucks / Spitfire wheels* for skating, the BYU RB as home gym. If any detail is wrong (wrong home mountain, different gear, etc.), open the HTML file in any text editor and edit the word — it's plain text.

**Images:**
- Snow section uses your snowboarder photo
- Menswear section uses your dark leather fit photo
- Skate section uses the Thrasher / Ishod Wair cover
- Iron section keeps the existing Unsplash barbell photo (as you requested)

**One heads-up on the Thrasher cover:** that's a copyrighted magazine cover. For a school project on GitHub Pages it's fine. If at some future point you want to swap it out for something you shot yourself (or a Creative Commons skate photo), replace `images/skate.jpg` with your own file of the same name — nothing else needs to change.

**Tableau:** the embedded viz is a publicly hosted *Top 100 Spotify Artists 2018* dashboard. Verified live before packaging. If it ever goes down (vizzes occasionally get unpublished), replace the iframe's `src` URL in scratch.html with any viz from public.tableau.com.

**YouTube:** the 2hollis "tell me" embed ID is `ulPq2FXiONE` — the official Interscope audio upload. Verified live.

---

## Credits

- Bootstrap 5.3 via cdn.jsdelivr.net
- Fonts: Bricolage Grotesque, Manrope, Syne, DM Sans, JetBrains Mono (Google Fonts)
- Iron-section image: Unsplash (royalty-free, no attribution required)
- Built for IS 201 — Brigham Young University
