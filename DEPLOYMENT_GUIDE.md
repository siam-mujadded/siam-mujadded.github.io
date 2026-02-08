# Quick Deployment Guide

## 🚀 Step-by-Step Instructions

### Prerequisites
- GitHub account (you already have: https://github.com/siam-mujadded)
- Git installed on your computer
- Terminal/Command Prompt access

---

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: **`siam-mujadded.github.io`** (must be exactly this)
3. Set to **Public**
4. **DO NOT** check "Add a README file"
5. Click **"Create repository"**

---

## Step 2: Upload Files to GitHub

### Option A: Using Command Line (Recommended)

Open terminal in your project folder (`siam-mujadded`) and run:

```bash
git init
git add .
git commit -m "Initial commit: Portfolio website"
git branch -M main
git remote add origin https://github.com/siam-mujadded/siam-mujadded.github.io.git
git push -u origin main
```

**If you get authentication errors:**
- Use GitHub Personal Access Token instead of password
- Or use GitHub Desktop application (Option B)

### Option B: Using GitHub Desktop

1. Download GitHub Desktop: https://desktop.github.com/
2. Sign in with your GitHub account
3. File → Add Local Repository → Select your `siam-mujadded` folder
4. Click "Publish repository"
5. Name it: `siam-mujadded.github.io`
6. Make it Public
7. Click "Publish repository"

---

## Step 3: Enable GitHub Pages

1. Go to: https://github.com/siam-mujadded/siam-mujadded.github.io/settings/pages
2. Under "Source", select: **"Deploy from a branch"**
3. Branch: **"main"**
4. Folder: **"/ (root)"**
5. Click **"Save"**

---

## Step 4: Wait & Access

- Wait 2-5 minutes for GitHub to build your site
- Visit: **https://siam-mujadded.github.io**
- Your portfolio is now live! 🎉

---

## 🔄 Updating Your Portfolio

After making changes to files:

```bash
git add .
git commit -m "Update portfolio"
git push origin main
```

Site updates automatically in 1-2 minutes.

---

## ✅ Checklist

- [ ] Created repository named `siam-mujadded.github.io`
- [ ] Pushed all files to GitHub
- [ ] Enabled GitHub Pages in settings
- [ ] Verified site is accessible at https://siam-mujadded.github.io
- [ ] Updated project links to actual GitHub repositories
- [ ] Tested all navigation links
- [ ] Checked mobile responsiveness

---

## 🆘 Troubleshooting

**Site not loading?**
- Wait 10-15 minutes (first deployment takes longer)
- Check repository name matches exactly: `siam-mujadded.github.io`
- Verify GitHub Pages is enabled in Settings → Pages

**404 Error?**
- Make sure `index.html` is in the root folder
- Check branch is set to `main` in Pages settings

**Changes not showing?**
- Clear browser cache (Ctrl+F5)
- Wait a few more minutes for GitHub to rebuild

---

## 📝 Next Steps

1. **Update Project Links**: Edit `index.html` and replace placeholder GitHub links with your actual repository URLs
2. **Add LinkedIn**: Update the LinkedIn link in the hero section if you have one
3. **Customize Colors**: Modify CSS variables in `styles.css` if desired
4. **Add More Projects**: Copy project card template and add your other work

---

**Need Help?** Check the detailed README.md file for more information.

