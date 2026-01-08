# Scrolltastic Hub - Deployment Package

This folder contains everything you need to deploy the Scrolltastic Hub.

## Folder Structure

```
scrolltastic-deployment/
├── index.html              (Main hub interface)
└── modules/
    ├── gallery.html        (Scrolltastic Image Gallery)
    ├── sequence.html       (Fantastic Scrolltastic)
    ├── zoom.html           (Scrolltastic Zoomies)
    ├── layers.html         (Scrolltastic Layers)
    └── hotspots.html       (Scrolltastic Hotspots)
```

## How to Deploy

### Option 1: GitHub Pages (Recommended - Free & Easy)

1. Create a new GitHub repository
2. Upload all files maintaining the folder structure
3. Go to Settings → Pages
4. Select "main" branch and "/" root
5. Your hub will be live at `https://yourusername.github.io/repo-name/`

### Option 2: Netlify (Free, Drag & Drop)

1. Go to [netlify.com](https://netlify.com)
2. Drag the entire `scrolltastic-deployment` folder onto Netlify
3. Your site is live instantly with a custom URL

### Option 3: Vercel (Free)

1. Go to [vercel.com](https://vercel.com)
2. Import your project
3. Deploy - takes seconds

### Option 4: Local Testing

For local testing before deployment:

```bash
cd scrolltastic-deployment
python -m http.server 8000
```

Then visit: `http://localhost:8000`

## How It Works

1. **Click a module button** → Opens that module in an iframe with full functionality
2. **Configure the module** → Use all original controls, upload images, customize
3. **Click "Add to Stack"** → Hub extracts the generated HTML from the module
4. **Repeat** → Add as many modules as you want
5. **Preview** → See all modules combined in a full-screen preview
6. **Export** → Download a single HTML file with everything combined

## Features

- ✅ Full functionality of each original module
- ✅ Drag to reorder stack items
- ✅ Live preview of combined result
- ✅ Single-file HTML export
- ✅ No code integration needed
- ✅ Easy to update individual modules

## Notes

- Each module file is completely independent
- The hub simply loads them in iframes and extracts their output
- You can update any module file without touching the hub
- Works on any static file host (no server-side code needed)

## Support

If you have issues, the most common cause is CORS (Cross-Origin) restrictions. 
This is why hosting is recommended over file:// URLs.
