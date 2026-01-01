# Projectfold - Happy New Year 2026 🎉

A beautiful New Year greeting page with animated effects and floating particles.

## 🌐 Live Website

Once GitHub Pages is enabled, this website will be available at:
**https://kiran234-dot-tech.github.io/Projectfold/**

## 📋 How to Enable GitHub Pages

This repository includes a GitHub Actions workflow that will automatically deploy your site. Follow these simple steps:

### Step 1: Enable GitHub Pages
1. Go to your GitHub repository: https://github.com/Kiran234-dot-tech/Projectfold
2. Click on **Settings** (top menu)
3. In the left sidebar, click on **Pages**
4. Under **Build and deployment**, for the **Source** dropdown, select **GitHub Actions**
5. That's it! No need to save - it updates automatically

### Step 2: Deploy Your Site
Once you've selected "GitHub Actions" as the source:
1. Go to the **Actions** tab in your repository
2. You should see the "Deploy to GitHub Pages" workflow
3. Click on the workflow, then click **Run workflow** → **Run workflow** button
4. Wait 1-2 minutes for the deployment to complete
5. Your live website will be available at: https://kiran234-dot-tech.github.io/Projectfold/

### Alternative: Deploy from Branch (if GitHub Actions option is not available)
If you don't see "GitHub Actions" option:
1. In Settings → Pages, under **Source**, select **Deploy from a branch**
2. Under **Branch**, select `main` and folder `/ (root)`
3. Click **Save**
4. Wait a few minutes for deployment

## 📂 Files

- **index.html** - Main page with the New Year greeting (shown by default)
- **tag.html** - Original New Year greeting page (also accessible at `/tag.html`)
- **home.html** - Additional page

## ✨ Features

- Animated glowing text effects
- Floating particles animation
- Responsive design that works on all devices
- Personalized greeting support via URL parameter (`?to=YourName`)

## 🎨 Customization

You can personalize the greeting by adding a `?to=Name` parameter to the URL:
```
https://kiran234-dot-tech.github.io/Projectfold/?to=John
```

This will display: "For John — Wishing you a radiant 2026 ✨"

## 📝 License

Feel free to use and modify this project as needed.
