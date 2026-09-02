# Viraj Bansod — Portfolio

This is your portfolio site, packaged as a real project so it can be deployed
to the web and given a live link. You do **not** need to install anything on
your computer — everything below happens in the browser.

## Deploy in ~5 minutes (GitHub + Vercel, both free)

### Step 1 — Create a GitHub account (skip if you have one)
Go to https://github.com/signup and create a free account.

### Step 2 — Create a new repository
1. Go to https://github.com/new
2. Repository name: `viraj-portfolio` (or anything you like)
3. Keep it **Public**
4. Click **Create repository**

### Step 3 — Upload these files
1. On your new repo's page, click **"uploading an existing file"**
   (or Add file → Upload files)
2. Drag the **entire contents** of this folder in — including the `src`
   folder — so the repo root looks like:
   ```
   index.html
   package.json
   vite.config.js
   .gitignore
   src/
     App.jsx
     main.jsx
   ```
3. Scroll down, click **Commit changes**

### Step 4 — Deploy on Vercel
1. Go to https://vercel.com and sign up using your **GitHub account**
2. Click **Add New... → Project**
3. Select your `viraj-portfolio` repo and click **Import**
4. Vercel auto-detects Vite — leave all settings as default
5. Click **Deploy**

In about a minute you'll get a live link like:
```
https://viraj-portfolio.vercel.app
```

That's your real, shareable URL — put it in your LinkedIn post, resume, and
GitHub bio.

## Custom domain (optional)
In your Vercel project → Settings → Domains, you can attach a custom domain
(e.g. `virajbansod.com`) if you buy one later. Not required to go live.

## Updating the site later
Whenever you want to change content (add a project, update a skill, etc.):
1. Edit `src/App.jsx` directly on GitHub (pencil icon on the file) — all the
   editable content (projects, skills, education, goals, etc.) is grouped
   near the top of the file in clearly labeled sections.
2. Commit the change.
3. Vercel automatically redeploys within a minute — no extra steps needed.

## Local development (optional, only if you install Node.js)
If you later want to preview changes on your own machine before committing:
```
npm install
npm run dev
```
Then open the local URL it prints (usually http://localhost:5173).
