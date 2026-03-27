# Event6D — Project Page

Source code for the **Event6D: Event-based Novel Object 6D Pose Tracking** project page.

🔗 **Live site:** `https://<your-username>.github.io/<repo-name>/`

---

## How to deploy on GitHub Pages

1. Create a new GitHub repository (e.g. `event6d`)
2. Push this folder as the repository root:
   ```bash
   cd /home/user/my-paper-page
   git init
   git add .
   git commit -m "Initial project page"
   git remote add origin https://github.com/<your-username>/event6d.git
   git push -u origin main
   ```
3. Go to **Settings → Pages**, set Source to `main` branch, `/ (root)` folder → **Save**
4. Your page will be live at `https://<your-username>.github.io/event6d/`

---

## How to fill in placeholders

| What to replace | Where |
|---|---|
| `YOUR_YOUTUBE_ID` in the iframe src | `index.html` — Video section |
| `static/images/thumbnail.png` | Teaser image in Hero section |
| `static/images/method_overview.png` | Method section figure |
| `static/images/table1.png` | Quantitative results, Table 1 |
| `static/images/table2.png` | Quantitative results, Table 2 |
| `static/videos/comparison1.mp4` | Comparison video slot 1 |
| `static/videos/comparison2.mp4` | Comparison video slot 2 |
| `static/videos/result1~3.mp4` | Event6D result video slots |
| `static/videos/ho3d1~3.mp4` | EventHO3D result video slots |
| `static/pdfs/supplementary.pdf` | Supplementary PDF |

## Directory structure

```
my-paper-page/
├── index.html
├── .nojekyll            ← required for GitHub Pages
├── README.md
└── static/
    ├── css/
    │   └── index.css
    ├── images/          ← put thumbnail.png, method_overview.png, table1.png, table2.png here
    ├── pdfs/
    │   ├── paper.pdf
    │   └── supplementary.pdf
    └── videos/          ← put .mp4 files here
```
