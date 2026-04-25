# AI Circuit Blog — GitHub Pages Deployment

Your blog will be live at: https://srinu923.github.io/circuit-ai/

## Folder Structure
```
circuit-ai/
├── index.html
├── assets/
│   ├── images/
│   │   ├── hand_drawn.jpeg
│   │   ├── appnote.png
│   │   ├── waveform_hand.png
│   │   └── waveform_appnote.png
│   └── video/
│       └── demo.mp4
└── README.md
```

## Step-by-Step Deployment

### Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `circuit-ai`
3. Set to **Public**
4. Click **Create repository**

### Step 2: Upload Files
Option A — GitHub Web UI (easiest):
1. Open your new repo
2. Click **Add file** → **Upload files**
3. Upload `index.html`
4. Create folder `assets/images/` and upload all 4 images
5. Create folder `assets/video/` and upload `demo.mp4`
6. Commit changes

Option B — Git CLI:
```bash
git clone https://github.com/srinu923/circuit-ai.git
cd circuit-ai
# Copy all files here
git add .
git commit -m "Initial blog deployment"
git push origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repo → **Settings** → **Pages**
2. Under **Source**: select **Deploy from a branch**
3. Branch: **main** / folder: **/ (root)**
4. Click **Save**

### Step 4: Wait ~60 seconds
Your blog will be live at:
**https://srinu923.github.io/circuit-ai/**

## Notes
- Video file (11MB) is within GitHub's 25MB file limit ✓
- No build step needed — pure HTML/CSS/JS
- Free forever on GitHub Pages
- To update: just push changes to main branch
