# 🚀 Deployment Guide
## Project: Ram Charan — The Global Icon Tribute Page

**Document Version:** 1.0
**Date:** July 2026
**Author:** Hruthik
**Platform:** Vercel
**Status:** ✅ Successfully Deployed

---

## DEPLOYMENT OVERVIEW

```
Local Files → GitHub Repository → Vercel → Live Website
```

Every time you push code to GitHub, Vercel automatically redeploys.
Zero manual steps after first setup!

---

## 1. PRE-DEPLOYMENT CHECKLIST

Before deploying, verify everything is ready:

| Check | Status |
|---|---|
| index.html works locally | ✅ |
| rc.jpg saved in project folder | ✅ |
| rc-portrait.jpg saved in project folder | ✅ |
| No console errors in browser | ✅ |
| All sections visible and working | ✅ |
| Mobile responsive tested | ✅ |
| All links working | ✅ |
| Manual testing completed | ✅ |
| README.md written | ✅ |

---

## 2. GITHUB SETUP

### Step 1 — Create Repository on GitHub

```
1. Go to github.com
2. Click "+" top right corner
3. Click "New repository"
4. Repository name → ram-charan-tribute
5. Description → Professional tribute page for Telugu Superstar Ram Charan
6. Set to Public
7. ❌ Do NOT check "Add README" (we have our own)
8. Click "Create repository"
```

### Step 2 — Initialize Git Locally

Open Command Prompt and navigate to your project:

```bash
cd "C:\Users\hruth\Desktop\HRUTHIK\Final Draft\projects\html\I1"
```

Run these commands one by one:

```bash
# Initialize git in the folder
git init

# Add all files to staging
git add .

# First commit
git commit -m "Initial commit — Ram Charan tribute page complete"

# Rename branch to main
git branch -M main

# Connect to GitHub (replace YOUR-USERNAME)
git remote add origin https://github.com/Hruthikvardhan/Tribute_page_RC.git

# Push to GitHub
git push -u origin main
```

### Step 3 — Verify on GitHub

```
Go to github.com/YOUR-USERNAME/ram-charan-tribute
You should see:
├── index.html
├── rc.jpg
├── rc-portrait.jpg
├── README.md
└── docs/
    ├── REQUIREMENTS.md
    ├── WIREFRAMES.md
    ├── SPRINTS.md
    ├── TESTING.md
    └── DEPLOYMENT.md
```

---

## 3. VERCEL DEPLOYMENT

### Step 1 — Create Vercel Account

```
1. Go to vercel.com
2. Click "Sign Up"
3. Choose "Continue with GitHub"
4. Authorize Vercel to access GitHub
```

### Step 2 — Import Project

```
1. Click "Add New Project"
2. You will see your GitHub repos listed
3. Find "ram-charan-tribute"
4. Click "Import"
```

### Step 3 — Configure Project

```
Framework Preset  → Other (since it's plain HTML)
Root Directory    → ./ (leave as default)
Build Command     → (leave empty — no build needed)
Output Directory  → (leave empty — no build needed)
Install Command   → (leave empty — no npm)
```

### Step 4 — Deploy

```
Click "Deploy" button
Wait ~30 seconds
Vercel builds and deploys automatically
```

### Step 5 — Your Live URL

```
https://ram-charan-tribute.vercel.app
        OR
https://ram-charan-tribute-YOUR-USERNAME.vercel.app
```

---

## 4. AFTER DEPLOYMENT — VERIFY LIVE SITE

Open the live URL and check:

| Check | Expected | Pass/Fail |
|---|---|---|
| Site loads | No blank screen | ✅ |
| Fonts load | Cinzel visible in navbar | ✅ |
| Hero photo loads | RC background visible | ✅ |
| Portrait photo loads | About card photo visible | ✅ |
| All sections visible | Scroll through entire page | ✅ |
| Mobile works on phone | Open on your mobile browser | ✅ |
| Links work | Footer external links open | ✅ |

---

## 5. FUTURE UPDATES — AUTO DEPLOY WORKFLOW

Every time you make a change:

```bash
# Step 1 — Make your changes in index.html

# Step 2 — Stage changes
git add .

# Step 3 — Commit with clear message
git commit -m "Updated Peddi dialogue"

# Step 4 — Push to GitHub
git push origin main

# Vercel auto-detects the push
# Redeploys automatically in ~30 seconds
# Live site updates! ✅
```

### Good Commit Message Examples

```bash
git commit -m "Added Game Changer to timeline"
git commit -m "Fixed mobile hamburger menu"
git commit -m "Updated hero background photo"
git commit -m "Fixed timeline closing tags"
git commit -m "Added favicon"
git commit -m "Updated Peddi dialogue to transliteration"
```

### Bad Commit Messages (avoid these)

```bash
git commit -m "changes"      ❌ too vague
git commit -m "fix"          ❌ what fix?
git commit -m "update"       ❌ what update?
git commit -m "asdfgh"       ❌ meaningless
```

---

## 6. CUSTOM DOMAIN (Optional)

If you want a custom domain like `ramcharantribute.com`:

```
1. Buy domain from GoDaddy / Namecheap (~₹800/year)
2. In Vercel → Project Settings → Domains
3. Click "Add Domain"
4. Enter your domain name
5. Vercel gives you DNS records
6. Add those records in your domain provider
7. Wait 24 hours for DNS propagation
8. Your site is live on custom domain!
```

---

## 7. PROJECT FOLDER STRUCTURE

Final folder structure that is deployed:

```
ram-charan-tribute/
│
├── index.html              ← Main file (entire website)
├── rc.jpg                  ← Hero background photo
│                             (1920×1080, under 500KB)
├── rc-portrait.jpg         ← About portrait photo
│                             (338×474, under 300KB)
│
├── README.md               ← Main documentation
│
└── docs/                   ← Detailed documentation
    ├── REQUIREMENTS.md     ← Requirement gathering
    ├── WIREFRAMES.md       ← Paper wireframe docs
    ├── SPRINTS.md          ← Agile sprint plan
    ├── TESTING.md          ← Manual testing checklist
    └── DEPLOYMENT.md       ← This file
```

---

## 8. VERCEL ENVIRONMENT INFO

| Property | Value |
|---|---|
| Platform | Vercel |
| Plan | Free (Hobby) |
| Build Type | Static Site |
| CDN | Global Edge Network |
| HTTPS | Auto-enabled ✅ |
| Auto Deploy | On every git push ✅ |
| Deploy Time | ~30 seconds |
| Bandwidth | 100GB/month (free tier) |

---

## 9. SHARING YOUR PROJECT

After deployment, share these:

```
🌐 Live Site    → https://ram-charan-tribute.vercel.app
📁 GitHub Repo  → https://github.com/Hruthikvardhan/Tribute_page_RC
```

### For Portfolio / Resume

```
Projects:
→ Ram Charan Tribute Page
   Tech: HTML5, CSS3, JavaScript
   Live: https://ram-charan-tribute.vercel.app
   Code: https://github.com/Hruthikvardhan/Tribute_page_RC
```

### For LinkedIn Post

```
🚀 Just deployed my Ram Charan Tribute Page!

Built with:
✅ Pure HTML5, CSS3, Vanilla JS
✅ No frameworks — zero dependencies
✅ Fully responsive (Mobile + Desktop)
✅ CSS Grid, Flexbox, Custom Properties
✅ IntersectionObserver scroll animations
✅ Deployed on Vercel

Live: [your link]
Code: [github link]

#HTML #CSS #JavaScript #WebDevelopment #Frontend
```

---

## 10. TROUBLESHOOTING

### Problem: Photos not showing on live site

```
Cause  → Image filenames are case sensitive on Vercel
Fix    → Make sure filenames match exactly:
         rc.jpg (not RC.jpg or Rc.jpg)
         rc-portrait.jpg (not RC-Portrait.jpg)
```

### Problem: Fonts not loading

```
Cause  → Google Fonts blocked or slow internet
Fix    → Check preconnect tags in <head>
         Add font-display: swap (already done)
```

### Problem: Page shows old version after update

```
Cause  → Browser cache
Fix    → Hard refresh: Ctrl + Shift + R (Windows)
                       Cmd + Shift + R (Mac)
```

### Problem: Git push rejected

```
Cause  → Remote has changes you don't have locally
Fix    →
git pull origin main
git push origin main
```

### Problem: Vercel deploy failed

```
Fix    →
1. Go to vercel.com → your project
2. Click "Deployments" tab
3. Click the failed deployment
4. Read the error log
5. Usually a file path or typo issue
```

---

## 11. DEPLOYMENT HISTORY

| # | Date | Commit Message | Status |
|---|---|---|---|
| v1.0 | July 2026 | Initial commit — complete page | ✅ Live |
| v1.1 | July 2026 | Added hero background photo | ✅ Live |
| v1.2 | July 2026 | Added about portrait photo | ✅ Live |
| v1.3 | July 2026 | Updated dialogues to transliteration | ✅ Live |
| v1.4 | July 2026 | Added Peddi + Game Changer timeline | ✅ Live |
| v1.5 | July 2026 | Fixed timeline closing tags | ✅ Live |
| v1.6 | July 2026 | Added favicon | ✅ Live |
| v1.7 | July 2026 | Added full documentation | ✅ Live |

---

## 12. WHAT TO SAY IN INTERVIEWS

> *"I deployed this project on Vercel with GitHub CI/CD integration.
> Every git push to the main branch automatically triggers a
> redeployment on Vercel — no manual steps needed.
> The entire deployment process takes about 30 seconds.
> I used meaningful commit messages for every change
> so the deployment history is clean and readable."*

---

*Deployment guide by: Hruthik | Ram Charan Tribute Project | July 2026*
