# 🚀 GitHub Pages Deployment Guide

This guide will help you deploy your portfolio to GitHub Pages using GitHub Actions for automatic deployment.

## 📋 Prerequisites

- GitHub account
- Git installed on your computer
- Your portfolio files ready

## 🔧 Step-by-Step Deployment

### Step 1: Create GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** button → **"New repository"**
3. Repository name: `your-username.github.io` (recommended) or `portfolio`
4. Make it **Public**
5. **Don't** initialize with README (we have files already)
6. Click **"Create repository"**

### Step 2: Upload Your Files

**Option A: Using Git Command Line**
```bash
# Navigate to your portfolio folder
cd path/to/your/portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio commit"

# Add GitHub repository as remote
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

**Option B: Using GitHub Web Interface**
1. In your new repository, click **"uploading an existing file"**
2. Drag and drop all your portfolio files
3. Commit the files

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** tab
3. Scroll down to **"Pages"** in the left sidebar
4. Under **"Source"**, select **"GitHub Actions"**
5. The workflow will automatically trigger

### Step 4: Wait for Deployment

1. Go to **"Actions"** tab in your repository
2. You'll see the deployment workflow running
3. Wait for it to complete (usually 2-3 minutes)
4. Once complete, your site will be live!

## 🌐 Accessing Your Live Site

Your portfolio will be available at:
- If repo name is `your-username.github.io`: `https://your-username.github.io`
- If repo name is `portfolio`: `https://your-username.github.io/portfolio`

## 🔄 Automatic Updates

Every time you push changes to the main branch:
1. GitHub Actions automatically rebuilds your site
2. Changes go live within 2-3 minutes
3. No manual deployment needed!

## 📁 Required Files Structure

Make sure your repository has this structure:
```
your-repo/
├── .github/
│   └── workflows/
│       └── deploy.yml          ← Auto-deployment workflow
├── index.html                  ← Main portfolio page
├── styles.css                  ← Styling
├── script.js                   ← JavaScript functionality
├── profile.jpg                 ← Your profile image
├── README.md                   ← Project documentation
└── DEPLOYMENT.md              ← This guide
```

## 🛠 Troubleshooting

### Common Issues:

**1. 404 Error**
- Check that `index.html` is in the root directory
- Ensure GitHub Pages is enabled in repository settings

**2. Images Not Loading**
- Make sure `profile.jpg` is uploaded to the repository
- Check that the filename matches exactly in your HTML

**3. Workflow Fails**
- Check the Actions tab for error details
- Ensure the workflow file is in `.github/workflows/deploy.yml`

**4. Changes Not Reflecting**
- Wait 2-3 minutes after pushing changes
- Clear browser cache (Ctrl+F5)
- Check Actions tab to see if deployment completed

### Force Redeploy:
1. Go to Actions tab
2. Click "Deploy Portfolio to GitHub Pages"
3. Click "Run workflow" → "Run workflow"

## 🎯 Custom Domain (Optional)

To use your own domain:
1. Add a `CNAME` file to your repository root
2. Put your domain name in the file (e.g., `suryaprakash.dev`)
3. Configure DNS settings with your domain provider
4. Point to `your-username.github.io`

## 📊 Analytics (Optional)

Add Google Analytics to track visitors:
1. Get Google Analytics tracking code
2. Add it to the `<head>` section of `index.html`
3. Push changes to update live site

## 🔒 Security Notes

- Repository must be public for free GitHub Pages
- Don't commit sensitive information
- Profile image and content are publicly accessible

---

**🎉 Congratulations!** Your portfolio is now live and automatically deploys with every update!