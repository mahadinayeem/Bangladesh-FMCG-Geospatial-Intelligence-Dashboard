# 🇧🇩 Bangladesh FMCG Retail & Geospatial Intelligence Dashboard

Interactive National Geospatial Dashboard with multi-tier drilldown:
- **Level 1**: National Overview (8 Divisions, 64 Districts, 545 Thanas)
- **Level 2**: Isolated Division View (Image 2 style)
- **Level 3**: Isolated District Thana View (Image 3 style)
- **Features**: Fine Zoom (0.25 snap), Fullscreen Map View, Dynamic FMCG Category Filters, Responsive Light/Dark Theme.

---

## 🚀 How to Push to GitHub & Deploy to Vercel

### Step 1: Open Terminal in this folder
Open PowerShell or Git Bash inside this folder:
```bash
cd "E:\FMCG  NEW\bangladesh_map_dashboard"
```

### Step 2: Initialize Git & Commit
```bash
git init
git add .
git commit -m "feat: Bangladesh retail FMCG geospatial dashboard"
```

### Step 3: Connect GitHub Repository & Push
```bash
git branch -M main
git remote add origin https://github.com/mahadinayeem/Bangladesh-FMCG-Geospatial-Intelligence-Dashboard.git
git push -u origin main
```

### Step 4: Deploy on Vercel
1. Go to [Vercel Dashboard](https://vercel.com/dashboard).
2. Click **"Add New..."** -> **"Project"**.
3. Import your GitHub repository (`bangladesh-fmcg-map`).
4. Framework Preset: **Other** (Static HTML).
5. Root Directory: `./` (Leave as default).
6. Click **"Deploy"**.
7. Your dashboard is live in seconds with a fast global CDN URL (e.g., `https://bangladesh-fmcg-map.vercel.app`)!
