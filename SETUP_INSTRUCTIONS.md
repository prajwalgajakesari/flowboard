# FlowBoard Support Repository - Setup Instructions

## 📦 What This Repository Contains

This is a **public support-only** repository for your **paid** FlowBoard app. It includes:

✅ GitHub issue templates (bug reports, feature requests, support questions)
✅ Support documentation with FAQs
✅ Privacy policy
✅ Professional README
❌ **No source code** (kept private for your paid app)

---

## 🚀 Quick Setup

### 1. Create GitHub Repository

1. Go to: https://github.com/new
2. **Repository name:** `flowboard`
3. **Description:** `Support repository for FlowBoard - A premium Kanban task manager for iPad`
4. **Visibility:** ✅ Public
5. **Initialize:** ❌ Don't add README, .gitignore, or license (we have them)
6. Click **Create repository**

### 2. Push This Repository

Run these commands from this directory:

```bash
cd /tmp/flowboard-support
git init
git add .
git commit -m "Initial commit - FlowBoard support infrastructure"
git branch -M main
git remote add origin https://github.com/prajwalgajakesari/flowboard.git
git push -u origin main
```

### 3. Update Before Pushing

**IMPORTANT:** Update these placeholders first:

1. **README.md** (line 119):
   - Replace `[your-email@example.com]` with your support email

2. **PRIVACY.md** (line 90):
   - Replace `[Your contact email]` with your email

3. **.github/SUPPORT.md** (line 118):
   - Replace `[Your support email]` with your email

4. **All files with `idXXXXXXXXXX`:**
   - Replace with actual App Store ID after approval (e.g., `id1234567890`)

---

## 🔗 URLs to Use in App Store Connect

After pushing to GitHub, use these URLs:

### Support URL (Required):
```
https://github.com/prajwalgajakesari/flowboard
```

### Privacy Policy URL (Required):
```
https://github.com/prajwalgajakesari/flowboard/blob/main/PRIVACY.md
```

### Marketing URL (Optional):
```
https://github.com/prajwalgajakesari/flowboard
```

---

## ✏️ After App Store Approval

Once your app is approved and you have your App Store ID:

1. Update all instances of `idXXXXXXXXXX` to your actual ID
2. Commit and push:
```bash
git add .
git commit -m "Update App Store links with actual app ID"
git push
```

---

## 🔒 Keeping Source Code Private

Your actual source code stays in:
```
/Users/prajwalp/repos/simple todo dashboard/
```

**Options for source code:**

### Option A: Keep It Local Only
- Don't push source code anywhere
- Keep it on your machine + backups

### Option B: Private GitHub Repository
- Create a **separate private** repository
- Name it something like `flowboard-private` or `flowboard-source`
- Push your full source code there
- Only you can see it

**To create private repo for source:**
```bash
cd "/Users/prajwalp/repos/simple todo dashboard"

# Initialize if not already a git repo
git init
git add .
git commit -m "FlowBoard v1.0 - Initial source code"

# Create private repo on GitHub, then:
git remote add origin https://github.com/prajwalgajakesari/flowboard-private.git
git branch -M main
git push -u origin main
```

---

## 📁 What Users Will See

When users visit `https://github.com/prajwalgajakesari/flowboard`:

✅ Professional README with app description
✅ Link to download from App Store
✅ Issue templates for bug reports and feature requests
✅ Support documentation
✅ Privacy policy
❌ **No source code** (protected for your paid app)

---

## 🎯 Benefits of This Setup

1. **Professional Support** - Users can report bugs and request features
2. **Transparent Privacy** - Privacy policy publicly accessible
3. **Protects Your Investment** - Source code stays private
4. **Free Hosting** - GitHub hosts everything for free
5. **Apple Approved** - Valid support URL for App Store

---

## ⚠️ Important Notes

- This support repo is **public** - anyone can see it
- Your **source code** stays **private** (in separate repo or local only)
- Issue templates help users report bugs properly
- You'll get email notifications when users open issues

---

## 🔄 Regular Maintenance

After launch:

1. **Monitor Issues** - Respond to bug reports and questions
2. **Update Privacy Policy** - If you add features that change data handling
3. **Update README** - Add screenshots, testimonials, new features
4. **Close Resolved Issues** - Keep issue tracker clean

---

Good luck with your App Store submission! 🚀
