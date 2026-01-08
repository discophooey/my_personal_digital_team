# GITHUB PAGES DEPLOYMENT - EXACT STEPS

## What You'll Get:
A live URL like: `https://marshallritzel.github.io/scrolltastic-hub/`

**Total Time: 5 minutes**

---

## STEP 1: Create a GitHub Account (if you don't have one)

1. Go to: **https://github.com**
2. Click **"Sign up"** (top right)
3. Enter your email, create password, choose username
4. Verify your email
5. Done!

---

## STEP 2: Create a New Repository

1. Once logged in, click the **"+"** icon (top right)
2. Select **"New repository"**
3. Fill in:
   - **Repository name**: `scrolltastic-hub` (or whatever you want)
   - **Description**: "Scrolltastic Hub - modular scroll builder"
   - **Public** (must be public for free GitHub Pages)
   - ✅ Check **"Add a README file"**
4. Click **"Create repository"**

---

## STEP 3: Upload Your Files

### Option A: Drag & Drop (EASIEST)

1. You're now on your repository page
2. Click **"Add file"** → **"Upload files"**
3. **Extract the ZIP file** I gave you on your computer
4. **Drag ALL files and folders** from `scrolltastic-deployment` folder onto GitHub:
   - index.html
   - The entire `modules` folder (with all 5 HTML files inside)
   - README.md
   - netlify.toml (optional, not needed for GitHub)
5. At the bottom, click **"Commit changes"**
6. Wait 10 seconds for upload to complete

**IMPORTANT**: Make sure the folder structure looks like this on GitHub:
```
scrolltastic-hub/
├── index.html
├── modules/
│   ├── gallery.html
│   ├── sequence.html
│   ├── zoom.html
│   ├── layers.html
│   └── hotspots.html
└── README.md
```

### Option B: Upload Folder by Folder

If drag & drop doesn't work for folders:

1. First upload `index.html` and `README.md` directly
2. Click **"Add file"** → **"Create new file"**
3. In the name field, type: `modules/gallery.html`
4. Copy/paste the content from gallery.html
5. Click **"Commit new file"**
6. Repeat for each module file:
   - modules/sequence.html
   - modules/zoom.html
   - modules/layers.html
   - modules/hotspots.html

---

## STEP 4: Enable GitHub Pages

1. In your repository, click **"Settings"** (top menu, far right)
2. In the left sidebar, scroll down and click **"Pages"**
3. Under "Build and deployment":
   - **Source**: Select **"Deploy from a branch"**
   - **Branch**: Select **"main"** (or "master")
   - **Folder**: Select **"/ (root)"**
4. Click **"Save"**
5. Wait 1-2 minutes

---

## STEP 5: Get Your Live URL

1. Refresh the GitHub Pages settings page
2. You'll see a message at the top:
   - **"Your site is live at https://YOUR-USERNAME.github.io/scrolltastic-hub/"**
3. Click the URL to visit your live Scrolltastic Hub!

**Your URL will be:**
```
https://marshallritzel.github.io/scrolltastic-hub/
```
(Replace with your actual GitHub username)

---

## STEP 6: Link from Your Wix Site

Now that it's live, add it to marshallritzel.com:

1. Log into Wix
2. Go to your site editor
3. Add a button or text link
4. Set the link to your GitHub Pages URL
5. Publish!

---

## HOW TO UPDATE IT LATER

When you want to change something:

1. Go to your repository on GitHub
2. Navigate to the file you want to edit
3. Click the **pencil icon** (Edit this file)
4. Make your changes
5. Click **"Commit changes"**
6. Changes go live in 1-2 minutes automatically

---

## TROUBLESHOOTING

### "I see a 404 error"
- Wait 2-3 minutes after enabling Pages (it takes time to build)
- Make sure `index.html` is in the root (not in a subfolder)
- Check that your repository is **Public**

### "The modules don't load / 404 errors"
- Make sure the `modules` folder structure is correct
- Files should be at: `modules/gallery.html`, `modules/sequence.html`, etc.
- Folder and file names are case-sensitive

### "I can't drag folders"
- Use Option B (create files one by one)
- Or use GitHub Desktop (more advanced)

### "It says my repository name is taken"
- Choose a different name like `scrolltastic-builder` or `scroll-hub`

---

## CUSTOM DOMAIN (OPTIONAL)

If you want `scrolltastic.marshallritzel.com`:

1. In GitHub Pages settings, click **"Add a custom domain"**
2. Enter: `scrolltastic.marshallritzel.com`
3. GitHub will give you DNS instructions
4. In your domain provider (where marshallritzel.com is registered):
   - Add a CNAME record:
     - Name: `scrolltastic`
     - Value: `marshallritzel.github.io`
5. Wait 10-60 minutes for DNS to propagate
6. GitHub will automatically handle the SSL certificate

---

## SUMMARY

**What you need:**
- GitHub account (free)
- The ZIP file I provided (extracted)
- 5 minutes

**What you get:**
- Live URL: `https://YOUR-USERNAME.github.io/scrolltastic-hub/`
- Free hosting forever
- Easy updates anytime
- Can add custom domain

**Next step:** Just start at STEP 1 above!
