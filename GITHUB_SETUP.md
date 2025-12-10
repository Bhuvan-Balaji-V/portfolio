# GitHub Pages Setup Guide

## Quick Summary of What's Done

✅ **Fixed all HTML files** — Added proper `<head>`, `<meta>` tags, and accessibility improvements  
✅ **Enhanced CSS** — Responsive design, mobile support, print stylesheet  
✅ **Created README.md** — Project documentation and deployment instructions  
✅ **Git initialized** — Repository ready to push to GitHub  

---

## Next Steps: Push to GitHub (5 minutes)

### Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and log in
2. Click the **+** icon (top-right) → **New repository**
3. Fill in:
   - **Repository name:** `portfolio` (or your preferred name)
   - **Description:** "Full Stack Developer & AI/ML Engineer Portfolio"
   - **Visibility:** Public
4. Click **Create repository**

### Step 2: Connect Local Git to GitHub

Copy and run these commands in PowerShell (inside your project folder):

```powershell
cd "c:\Users\Bhuvan Balaji V\OneDrive\Desktop\weblab1"

# Replace YOUR_GITHUB_USERNAME and portfolio with your values
git branch -M main
git remote add origin https://github.com/YOUR_GITHUB_USERNAME/portfolio.git
git push -u origin main
```

**Example:**
```powershell
git remote add origin https://github.com/bhuvanbalajiv/portfolio.git
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub (https://github.com/YOUR_USERNAME/portfolio)
2. Click **Settings** (top-right)
3. Scroll down to **"Pages"** section (on left sidebar)
4. Under **"Build and deployment"**:
   - Branch: Select **main**
   - Folder: Select **/ (root)**
5. Click **Save**

**Your site will be live in 2-3 minutes at:**
```
https://YOUR_GITHUB_USERNAME.github.io/portfolio/
```

---

## Alternative: Deploy with Netlify (Even Easier)

1. Go to [netlify.com](https://netlify.com)
2. Click **Add new site** → **Deploy manually**
3. Drag and drop your entire project folder into the drop zone
4. Your site is live instantly with a random URL (or connect GitHub for custom domain)

---

## Verification Checklist

Once deployed, check:

- [ ] Home page loads and navigation works
- [ ] Resume page displays correctly
- [ ] Bio-data table looks good
- [ ] Mobile view (toggle DevTools phone icon)
- [ ] Print resume (Ctrl+P or Cmd+P)
- [ ] All links work correctly
- [ ] No console errors (F12 → Console tab)

---

## Files Ready to Deploy

```
weblab1/
├── index.html          ✅ Fixed
├── resume.html         ✅ Fixed
├── biodata.html        ✅ Fixed (already complete)
├── style.css           ✅ Enhanced (responsive + print)
├── README.md           ✅ Created
└── .git/               ✅ Initialized
```

---

## Git Commands Reference

```powershell
# Check current status
git status

# View commit history
git log --oneline

# Make changes locally, then push
git add .
git commit -m "Your message"
git push origin main

# View remote URL
git remote -v
```

---

## Contact & Links

- **Email:** bhuvanbalajiv@outlook.com
- **GitHub:** https://github.com/YOUR_GITHUB_USERNAME
- **Portfolio:** https://YOUR_GITHUB_USERNAME.github.io/portfolio/

---

**Ready? Run the commands in Step 2 above!** 🚀
