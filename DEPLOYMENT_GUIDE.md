# 🚀 Deploy Copy UTR to GitHub Pages - Complete Guide

## 📋 Prerequisites
- GitHub account (free)
- Git installed on your computer
- The `index.html` file

---

## ⚙️ Step 1: Create a GitHub Repository

1. Go to [github.com](https://github.com) and log in
2. Click the **+** icon in top-right corner → **New repository**
3. Fill in the details:
   - **Repository name**: `copy-utr` (or any name you prefer)
   - **Description**: "Copy UTR - Unique Transaction Reference Tool"
   - **Public** (required for free GitHub Pages)
   - ✅ **Initialize with README** (optional but recommended)
4. Click **Create repository**

---

## 💻 Step 2: Clone Repository to Your Computer

### On Windows (Git Bash or Command Prompt):
```bash
cd Desktop
git clone https://github.com/YOUR-USERNAME/copy-utr.git
cd copy-utr
```

### On Mac/Linux (Terminal):
```bash
cd ~/Desktop
git clone https://github.com/YOUR-USERNAME/copy-utr.git
cd copy-utr
```

⚠️ **Replace YOUR-USERNAME with your actual GitHub username**

---

## 📁 Step 3: Add Your HTML File

1. **Copy** the `index.html` file into the `copy-utr` folder
2. Make sure it's in the root of the folder (not in a subfolder)

Your folder structure should look like:
```
copy-utr/
├── index.html
├── README.md
└── .git/
```

---

## 📤 Step 4: Upload to GitHub

### Open Git Bash or Terminal in your project folder and run:

```bash
git add index.html
```

```bash
git commit -m "Add Copy UTR tool"
```

```bash
git push origin main
```

You'll see output like:
```
Enumerating objects: 3, done.
...
To https://github.com/YOUR-USERNAME/copy-utr.git
   abc1234..def5678  main -> main
```

✅ Your files are now on GitHub!

---

## 🌐 Step 5: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** (top menu)
3. On the left sidebar, click **Pages**
4. Under "Source", select:
   - Branch: **main** (or master)
   - Folder: **/ (root)**
5. Click **Save**

GitHub will show:
```
Your site is published at https://YOUR-USERNAME.github.io/copy-utr/
```

⏳ **Wait 1-2 minutes** for it to deploy

---

## ✨ Step 6: Access Your Site

Your UTR tool is now live at:
```
https://YOUR-USERNAME.github.io/copy-utr/
```

### 🎯 Use URL Parameters to Share:
```
https://YOUR-USERNAME.github.io/copy-utr/?name=John&utr=1234567891234567
```

Replace:
- `John` with the actual name
- `1234567891234567` with the actual UTR number

---

## 🔄 Step 7: Make Updates

If you need to update the tool:

```bash
# Edit index.html in your text editor, then:

git add index.html
git commit -m "Update Copy UTR tool"
git push origin main
```

Changes appear on your live site within 1-2 minutes.

---

## 📚 URL Parameter Examples

### Example 1: Simple copy
```
https://YOUR-USERNAME.github.io/copy-utr/?name=Ali&utr=9876543210987654
```

### Example 2: With spaces (use + or %20)
```
https://YOUR-USERNAME.github.io/copy-utr/?name=Muhammad+Ali&utr=5555555555555555
```

### Example 3: Share via WhatsApp
Create a short link using:
- **Bitly**: https://bitly.com
- **TinyURL**: https://tinyurl.com
- **Short.link**: https://short.link

---

## 🆘 Troubleshooting

### "404 Page Not Found"
- ✅ Check repository is **Public**
- ✅ Settings → Pages is enabled
- ✅ `index.html` is in the root folder
- ✅ Wait 2-3 minutes for GitHub to deploy
- ✅ Hard refresh browser (Ctrl+Shift+R or Cmd+Shift+R)

### "Git command not found"
- Download Git from https://git-scm.com

### "Permission denied"
- Make sure you're in the correct folder: `cd copy-utr`

### Changes not showing
- Hard refresh: **Ctrl+Shift+R** (Windows) or **Cmd+Shift+R** (Mac)

---

## 📱 Mobile Friendly

The tool works perfectly on:
- ✅ Desktop browsers
- ✅ Mobile phones (iOS/Android)
- ✅ Tablets

---

## 🔐 Security Notes

- Your page is **public** (viewable by anyone)
- The UTR numbers are **NOT stored** anywhere
- They're only copied to clipboard when user clicks

---

## 🎉 Success!

Your Copy UTR tool is now live and shareable!

**Quick Share Links:**
```
Direct: https://YOUR-USERNAME.github.io/copy-utr/?name=YourName&utr=YOUR_UTR

Share Examples:
- WhatsApp: Paste the link in message
- Email: Send as hyperlink
- Social Media: Post the link
- QR Code: Generate at https://qr-code-generator.com
```

---

## 📝 Additional Customization

To change colors, title, or design:
1. Edit `index.html` in a text editor (VS Code recommended)
2. Look for the `<style>` section
3. Modify colors, fonts, or text
4. Save and push to GitHub

---

**Questions?** Check GitHub's official guide:
https://docs.github.com/en/pages/getting-started-with-github-pages
