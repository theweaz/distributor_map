
# SKB Distributor Map

This is an interactive distributor map built using **Leaflet.js** and connected live to a Google Sheet via [OpenSheet](https://opensheet.elk.sh/).

📍 Click on a marker to view distributor details  
📊 Data updates dynamically from the linked Google Sheet  
🧭 Use the collapsible side panel for enhanced interactivity (if enabled)

## 📂 Project Files

- `index.html` – main interactive map page
- `SKB Cases Logo_solo.png` – optional custom marker icon (if using branded markers)

## 🔗 Live Map

Access the map here:  
**[https://theweaz.github.io/distributor_map/](https://theweaz.github.io/distributor_map/)**

## 📝 How It Works

- Distributor data is pulled from this public Google Sheet:  
  [View Sheet](https://docs.google.com/spreadsheets/d/1wVrLOTzs88gLpbnFrY0SCwPdSArXYouV4HW85jRK5fg/edit#gid=0)
- Markers are plotted based on lat/lng
- Optionally, a special icon (SKB logo) highlights HQ

## ✅ To Deploy

1. Upload `index.html` and supporting assets to your GitHub repo
2. In **Settings > Pages**, set:
   - Branch: `main`
   - Folder: `/ (root)`
3. Wait for GitHub Pages to redeploy

## 🧼 Maintenance Tips

- Always keep your `index.html` in the root directory
- If the map goes blank, check console for JavaScript or image path errors
- Publish your Google Sheet if data fails to load

---
Created by SKB Workspace • Powered by Leaflet
