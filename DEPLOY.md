# Deploying Your Portfolio Website to GitHub Pages

## Quick Start Guide

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the **"+"** icon in the top right → **"New repository"**
3. Repository name: `portfolio-website` (or your preferred name)
4. Choose **Public** (required for free GitHub Pages)
5. **DO NOT** check "Add a README file" (you already have one)
6. Click **"Create repository"**

### Step 2: Initialize Git and Push Your Code

Run these commands in your terminal (PowerShell) from your project folder:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: Portfolio website"

# Rename branch to main (if needed)
git branch -M main

# Add your GitHub repository as remote (replace YOUR_USERNAME and REPO_NAME)
git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git

# Push to GitHub
git push -u origin main
```

**Important**: Replace `YOUR_USERNAME` with your GitHub username and `REPO_NAME` with your repository name.

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** (top menu bar)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

### Step 4: Access Your Website

Your website will be live at:
```
https://YOUR_USERNAME.github.io/REPO_NAME/
```

**Note**: It may take a few minutes (up to 10) for the site to be available after enabling Pages.

---

## Updating Your Website

After making changes to your files, use these commands to update:

```bash
git add .
git commit -m "Update: description of changes"
git push
```

Your GitHub Pages site will automatically rebuild and update within a few minutes.

---

## Troubleshooting

- **404 Error**: Wait 5-10 minutes after enabling Pages, then try again
- **Site not updating**: Check if your changes were pushed to the `main` branch
- **Build errors**: Check the **Actions** tab in your repository for build logs
- **Wrong branch**: Make sure GitHub Pages is set to the `main` branch (not `master`)

