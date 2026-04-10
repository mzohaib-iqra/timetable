# 📋 IPS School — Timetable Manager

A complete school timetable management system for IPS School.  
Built with React + Vite. Hosted free on GitHub Pages.

---

## ✅ Features

- 👤 **Teacher management** — add, edit, remove teachers
- 📚 **Per-class subject setup** — each class has its own subjects; multi-select to apply to several classes at once
- 📋 **Full timetable view** — editable cells, section filter, print all
- 🏫 **Class view** — see any class's full period schedule
- 🖨 **Print** — individual teacher sheets or all teachers at once
- 💾 **Auto-save** — all data saved in browser (localStorage), survives page refresh
- ⬇⬆ **Export / Import** — backup and restore data as a JSON file
- ♂♀ **Male + Female sections** — female section Cl.4–12, classes 8 & 9 combined
- ✦ **Cross-section** — male science teachers teaching female section

---

## 🚀 How to put this on GitHub Pages (step by step)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up (free).

### Step 2 — Create a new repository
1. Click the **+** button → **New repository**
2. Name it: `ips-timetable`
3. Set it to **Public**
4. Do NOT tick "Add README" (the folder already has one)
5. Click **Create repository**

### Step 3 — Upload the project files
**Option A — Using GitHub website (easiest, no software needed):**
1. Open the repository you just created
2. Click **"uploading an existing file"** link (or drag and drop)
3. Select ALL files and folders from this `ips-timetable` folder
   - ⚠️ You must also upload the hidden `.github` folder — make sure it's included
4. Click **Commit changes**

**Option B — Using Git (if you have Git installed):**
```bash
cd ips-timetable
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ips-timetable.git
git push -u origin main
```

### Step 4 — Enable GitHub Pages
1. In your repository, go to **Settings** (top menu)
2. Click **Pages** (left sidebar, under "Code and automation")
3. Under **Source**, select **GitHub Actions**
4. Click **Save**

### Step 5 — Wait for deployment (~2 minutes)
1. Go to the **Actions** tab in your repository
2. You'll see a workflow running called "Deploy to GitHub Pages"
3. Wait for the green ✓ checkmark

### Step 6 — Open your app!
Your app will be live at:
```
https://YOUR_USERNAME.github.io/ips-timetable/
```
Bookmark this link. You can open it on any device (PC, phone, tablet).

---

## 💾 Your data is saved automatically

- Every change (adding a teacher, editing a period, etc.) is saved instantly in your browser
- Data stays there even if you close the tab or restart the PC
- Use **⬇ Export** to download a backup JSON file anytime
- Use **⬆ Import** to restore from a backup (useful if you clear browser data)

---

## 🔄 Making changes / updates

Whenever you edit any file and push to GitHub, the site **automatically rebuilds and deploys** within ~2 minutes.

---

## 💻 Running locally (optional, requires Node.js)

```bash
npm install
npm run dev
```
Then open `http://localhost:5173` in your browser.
