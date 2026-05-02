# PawBoss.co — Temporary Shutdown Page

A clean, branded holding page for PawBoss.co while the site is temporarily down.

## Project Structure

```
pawboss-site/
├── index.html          # Main page
├── assets/
│   ├── logo-horizontal.png   # Full horizontal logo
│   └── logo-icon.png         # Icon/mark only
└── README.md
```

---

## 🚀 How to Deploy

### Step 1 — Push to GitHub

1. Go to [github.com](https://github.com) and sign in (or create a free account).
2. Click the **"+"** in the top right → **"New repository"**.
3. Name it `pawboss-site` (or anything you like).
4. Set it to **Public** (required for free Vercel hosting).
5. Click **"Create repository"**.

Then on your computer, open Terminal (Mac) or Command Prompt (Windows) and run:

```bash
cd path/to/pawboss-site   # navigate into the folder you downloaded
git init
git add .
git commit -m "Initial commit — shutdown page"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/pawboss-site.git
git push -u origin main
```

> Replace `YOUR_USERNAME` with your actual GitHub username.

---

### Step 2 — Deploy to Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with your GitHub account.
2. Click **"Add New… → Project"**.
3. Find `pawboss-site` in the list and click **"Import"**.
4. Leave all settings as default (Vercel auto-detects static HTML).
5. Click **"Deploy"**.

Done! Vercel will give you a live URL like `pawboss-site.vercel.app` within seconds.

---

### Step 3 — Connect Your Custom Domain (optional)

1. In your Vercel project dashboard, go to **Settings → Domains**.
2. Type `pawboss.co` and click **Add**.
3. Vercel will show you DNS records to add — log into wherever your domain is registered (GoDaddy, Namecheap, etc.) and add them.
4. It usually propagates within a few minutes to an hour.

---

## ✏️ Making Updates

To update text or content:
1. Edit `index.html` in any text editor.
2. Run `git add . && git commit -m "Update page" && git push`.
3. Vercel automatically redeploys — live in ~10 seconds.
