# NETLIFY DEPLOYMENT - EXACT STEPS

## What You'll Do (2 minutes total):
1. Download the ZIP file I created
2. Go to Netlify
3. Drag the folder onto their site
4. Done! You get a live URL

---

## Step-by-Step with Screenshots

### Step 1: Download & Extract
1. Download `scrolltastic-deployment.zip` (already provided to you)
2. Extract it - you'll get a folder called `scrolltastic-deployment`
3. Keep this folder window open

### Step 2: Go to Netlify
1. Open a new browser tab
2. Go to: **https://app.netlify.com/drop**
3. You'll see a page that says "Drag and drop your site output folder here"
4. *You don't even need to sign up first!*

### Step 3: Deploy
1. Drag the **entire `scrolltastic-deployment` folder** onto the Netlify page
2. Wait 10-30 seconds while it uploads
3. Netlify will show you a live URL like: `https://random-name-12345.netlify.app`
4. Click the URL - your hub is LIVE!

### Step 4: (Optional) Customize URL
1. After deploying, Netlify will prompt you to "Claim this site"
2. Sign up (free, just email)
3. Click "Site settings" → "Change site name"
4. Change to something like: `marshall-scrolltastic`
5. Your new URL: `https://marshall-scrolltastic.netlify.app`

### Step 5: (Optional) Custom Domain
If you want `scrolltastic.marshallritzel.com`:
1. In Netlify, go to "Domain settings"
2. Click "Add custom domain"
3. Enter: `scrolltastic.marshallritzel.com`
4. Netlify gives you DNS instructions
5. Add a CNAME record in your Wix/domain DNS settings:
   - Type: CNAME
   - Name: scrolltastic
   - Value: [the netlify URL they give you]

---

## That's It!

**Result**: Your Scrolltastic Hub will be live at a URL you can share or link from your Wix site.

**No coding, no server setup, no monthly fees.**

---

## Troubleshooting

**"It's asking me to sign up"**
- Just use the direct drop URL: https://app.netlify.com/drop
- Or sign up - it's free and takes 30 seconds

**"The modules aren't loading"**
- Make sure you dragged the FOLDER, not individual files
- The folder structure must be maintained (index.html and modules/ folder)

**"I want to update it"**
- Just drag the updated folder again
- Or use Netlify's dashboard to drag new files

---

## What You Can Do From Wix

Once deployed, add a button on your Wix site:
1. In Wix editor, add a button
2. Set link to your Netlify URL
3. Button text: "Launch Scrolltastic Hub" or "Create Scroll Story"
4. Done!
