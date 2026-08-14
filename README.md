# Ricky Piggott — Portfolio

Single-page portfolio for Ricky Piggott (Computer Vision Engineer & Rancher).

## Deploy on Render (Static Site)

1. Create a new repo on GitHub (e.g. `portfolio`) and push these files:
   ```bash
   git init
   git add .
   git commit -m "Portfolio"
   git branch -M main
   git remote add origin https://github.com/rickypiggott17/portfolio.git
   git push -u origin main
   ```
2. Go to https://render.com → New → **Static Site**
3. Connect the `portfolio` repo
4. Build command: leave empty
5. Publish directory: `.` (root)
6. Deploy — Render gives you a free URL like `https://portfolio.onrender.com`

## Custom domain (optional)

Add a domain in Render dashboard → Static Site → Settings → Custom Domain (e.g. `portfolio.7gbeef.com` or `rickypiggott.com`). Point a CNAME record at Render's hostname.
