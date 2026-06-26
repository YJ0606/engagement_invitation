# 💍 Tushar & Sakshi — Engagement Website

Beautiful Indian engagement invitation website with animated ring opening, floating petals, live countdown, schedule and Google Maps.

## 🚀 Deploy on Render (Step-by-step)

### Method 1 — Via GitHub (Recommended)

1. **Push to GitHub**
   ```bash
   git init
   git add .
   git commit -m "Tushar & Sakshi engagement website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/engagement-website.git
   git push -u origin main
   ```

2. **Connect to Render**
   - Go to [https://render.com](https://render.com)
   - Click **"New +"** → **"Static Site"**
   - Click **"Connect a repository"** → Select your GitHub repo
   - Fill in settings:
     - **Name:** `tushar-sakshi-engagement`
     - **Branch:** `main`
     - **Root Directory:** *(leave blank)*
     - **Build Command:** *(leave blank)*
     - **Publish Directory:** `.`
   - Click **"Create Static Site"**
   - ✅ Live in ~30 seconds!

### Method 2 — Manual Deploy (No GitHub needed)

1. Go to [https://render.com](https://render.com) → Sign up / Log in
2. Click **"New +"** → **"Static Site"**
3. Choose **"Deploy without connecting to Git"**
4. **Drag & drop** the entire `engagement-invite/` folder
5. Click **"Deploy"**
6. ✅ Your site is live!

## 📁 Files
- `index.html` — Complete single-page website
- `render.yaml` — Render deployment config
- `_redirects` — URL redirect rules
- `_headers` — HTTP headers config

## ✨ Features
- 💍 Animated ring opening on page load
- 🌸 Floating flower petals
- ⏳ Live countdown timer
- 🎵 Background music with mute button
- ✦ Sparkle animations on click
- 📍 Google Maps location button
- 🗓️ Event schedule cards
- 📱 Fully mobile responsive
