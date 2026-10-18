# 🇧🇩 Bangladesh FMCG Retail & Geospatial Intelligence Dashboard

Interactive National FMCG Geospatial Intelligence Dashboard with multi-tier territorial drilldown:
- **Level 1**: National Overview (8 Divisions, 64 Districts, 545 Thanas)
- **Level 2**: Isolated Division View with district metrics & market distribution
- **Level 3**: Isolated District Thana View with deep-dive FMCG category sales, outlet density & performance
- **Features**: Sub-pixel Fine Zoom (0.25 snap), Fullscreen Map Mode, Dynamic Multi-Category Filters, Responsive Light/Dark Mode.

---

## 📁 Repository Structure

```text
├── index.html                           # Main entry point for Dashboard (Vercel / GitHub Pages)
├── bangladesh_category_map_dashboard.html # Standalone mirror file
├── bd_geo.js                            # Bangladesh Division boundaries (GeoJSON)
├── bd_districts_geo.js                  # 64 District boundaries (GeoJSON)
├── bd_thanas_geo.js                     # 545 Thana / Upazila boundaries (GeoJSON)
├── district_thana_category_data.js      # Hierarchical FMCG Category Retail Dataset
├── leaflet.js / leaflet.css             # Local Leaflet geospatial library
├── vercel.json                          # Vercel deployment configuration
└── README.md                            # Documentation & guide
```

---

## 🚀 Running Locally

No build tools or Node.js environment required! Simply open `index.html` in any modern web browser or serve via a local HTTP server:

```bash
# Python
python -m http.server 8000

# or Node / npx
npx serve .
```

Then navigate to `http://localhost:8000`.

---

## 🌐 Deploy to Vercel

1. Go to your [Vercel Dashboard](https://vercel.com/dashboard).
2. Click **"Add New..."** -> **"Project"**.
3. Import your GitHub repository: `mahadinayeem/Bangladesh-FMCG-Geospatial-Intelligence-Dashboard`.
4. Framework Preset: **Other** (Static HTML).
5. Root Directory: `./` (Leave as default).
6. Click **"Deploy"**.
7. Your geospatial dashboard is instantly live with global CDN performance!

---

## 🌐 Deploy to GitHub Pages

1. Go to repository **Settings** -> **Pages**.
2. Under **Build and deployment** > **Source**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/ (root)`.
4. Click **Save**. Your site will be published at:
   `https://mahadinayeem.github.io/Bangladesh-FMCG-Geospatial-Intelligence-Dashboard/`
