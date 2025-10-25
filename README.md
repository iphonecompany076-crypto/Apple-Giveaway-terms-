# Apple Giveaway and Promotion — Terms & Conditions Site (GitHub Pages Setup)

This guide explains how to publish your Terms & Conditions website for **Apple Giveaway and Promotion** using **GitHub Pages** (free hosting with a public link).

## 🚀 What You Need
- A [GitHub](https://github.com) account (free)
- Git installed on your computer
- The HTML file: `index.html` (the Terms & Conditions site provided)

## 🧩 Step 1: Create a New Repository
1. Log into GitHub and click **New Repository**.
2. Name it something like `apple-giveaway-terms`.
3. Choose **Public**.
4. Do **not** initialize with a README.
5. Click **Create Repository**.

## 💻 Step 2: Upload Your Site via Terminal (Git Commands)
```bash
cd ~/Desktop
mkdir apple-giveaway-terms && cd apple-giveaway-terms
# Move your index.html file here
git init
git add index.html
git commit -m "Initial commit - Apple Giveaway Terms"
git branch -M main
git remote add origin https://github.com/<your-username>/apple-giveaway-terms.git
git push -u origin main
```

## 🌐 Step 3: Enable GitHub Pages
1. Go to **Settings → Pages**.
2. Select **Deploy from a branch**.
3. Choose branch **main**, folder **/ (root)**, then click **Save**.
4. Your site will appear at:
   https://<your-username>.github.io/apple-giveaway-terms

## ✉️ Support
Email: iphonecompany076@gmail.com

© 2025 Apple Giveaway and Promotion — Munich, Germany
