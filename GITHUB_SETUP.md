# 🚀 GitHub Setup Instructions

## ✅ Current Status: TRACKED & COMMITTED

Your portfolio is now being tracked in Git with 2 commits:
- ✓ Initial commit with all portfolio files
- ✓ README documentation added

**17 files tracked** including:
- `latimore-portfolio.html` (standalone artifact)
- `portfolio/` (React source files)
- `README.md` (documentation)
- `.gitignore` (git configuration)

---

## 📤 Push to GitHub (3 Steps)

### Step 1: Create a New Repository on GitHub

1. Go to https://github.com/new
2. Repository name: `latimore-digital-portfolio` (or your choice)
3. Description: "Professional digital portfolio with AI-powered legacy planning tools"
4. Choose: **Public** (to share) or **Private** (for yourself only)
5. **DO NOT** initialize with README, .gitignore, or license
6. Click "Create repository"

### Step 2: Link Your Local Repository to GitHub

Copy the commands from GitHub's "...or push an existing repository" section.
It will look like this (replace YOUR-USERNAME):

```bash
cd /home/claude
git remote add origin https://github.com/YOUR-USERNAME/latimore-digital-portfolio.git
git branch -M main
git push -u origin main
```

### Step 3: Verify Upload

Visit your repository URL:
`https://github.com/YOUR-USERNAME/latimore-digital-portfolio`

You should see all your files!

---

## 🔄 Making Updates After Initial Push

When you make changes:

```bash
# Stage your changes
git add .

# Commit with a message
git commit -m "Description of what you changed"

# Push to GitHub
git push
```

---

## 🌐 GitHub Pages Deployment (BONUS)

To make your portfolio live on the web:

1. Go to your repository on GitHub
2. Click "Settings" → "Pages"
3. Source: Deploy from branch "main"
4. Folder: / (root)
5. Click "Save"
6. Your site will be live at: `https://YOUR-USERNAME.github.io/latimore-digital-portfolio/latimore-portfolio.html`

---

## 📱 Quick Reference

**Check status:** `git status`
**See history:** `git log --oneline`
**View tracked files:** `git ls-files`

---

## 🆘 Troubleshooting

**If push fails with authentication error:**
- Use a Personal Access Token instead of password
- GitHub Settings → Developer Settings → Personal Access Tokens → Generate new token
- Use token as password when prompted

**If remote already exists:**
```bash
git remote remove origin
git remote add origin https://github.com/YOUR-USERNAME/repo-name.git
```

---

## 📧 Need Help?

Contact: jackson1989@latimorelegacy.com
Phone: (856) 895-1457
