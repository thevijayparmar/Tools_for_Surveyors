# 🧭 Traverse Adjustment Tool
A powerful **browser-based traverse computation and adjustment tool** built for **surveyors and civil engineers**.  
Supports both **bearing-distance** and **coordinate entry**, performs **Bowditch adjustment**, and provides rich **visual + tabular outputs**.  
Runs fully **offline in your browser** – no internet or installation required.

---

## ✨ Features

### 📂 Input Modes
- **Bearing + Distance** → Enter traverse legs using lengths and bearings.  
- **Coordinate Entry** → Options for:  
  - Manual entry of points.  
  - **CSV Upload** (auto-detect & map columns).  
  - **Sample Test Data** for quick demos.  

### ⚙️ Settings
- ✅ Assume Closed Traverse toggle.  
- ✅ Choose angle system: **Azimuth (0–360°)** or bearings.  
- 🌍 Choose coordinate system:  
  - **UTM / Projected** → Standard XY easting/northing.  
  - **GCS (Longitude/Latitude)** → Uses **haversine formula** for distances & geodetic bearings.  

### 🖼️ Visualization
- Interactive **sketch panel**:  
  - Red polyline → Original traverse with misclosure vector.  
  - Green polyline → Adjusted traverse (Bowditch).  
  - Click a **point** → Get ID, X, Y, and computed bearing.  
  - Click a **segment** → View segment length.  
  - Red dashed vector → **Misclosure line** with error magnitude.  
- Responsive redraw on resize.  

### 📊 Computation & Adjustment
- Calculates:  
  - Misclosure vector (ΔX, ΔY).  
  - Resultant error magnitude.  
  - Misclosure ratio (1 in N).  
  - Perimeter and area of traverse.  
- Applies **Bowditch Adjustment** to redistribute closure error.  
- Shows **original vs adjusted** coordinates and leg details.  

### 📑 Tabular Reports
- **Legs Table** → Original vs Adjusted lengths, bearings, ΔX, ΔY, corrections, and Δθ.  
- **Points Table** → Original vs Adjusted coordinates with δX, δY corrections.  
- **Summary Stats** → Misclosure, perimeter, area, and quality commentary.  

### 📤 Export Options
- Export **Legs CSV** (original vs adjusted).  
- Export **Points CSV** (original vs adjusted).  
- Retains **precision** based on input decimals.  

### 🎨 Usability
- Clean **Neumorphism UI** with modern cards.  
- Drag‑and‑drop row reordering.  
- History log with status/error messages.  
- **Reset** button to start fresh.  

---

## 🖼️ Preview
<img width="1241" height="1898" alt="Screenshot 2025-08-26 115046" src="https://github.com/user-attachments/assets/89a99816-7aa3-4f9c-8095-c697cc032b5d" />
<img width="1862" height="1905" alt="Screenshot 2025-08-26 115056" src="https://github.com/user-attachments/assets/46a094e8-9b48-42bf-a651-344bfd9daeb9" />


---

## 🚀 How to Use
1. Open **`Traverse adjustment tool V6.0.html`** in your browser.  
2. Select input type:  
   - **Bearing + Distance** → Enter start coordinates, add legs.  
   - **Coordinates** → Enter manually, upload CSV, or load a sample.  
3. Adjust settings (Closed Traverse, Azimuth/GCS).  
4. Click **Compute & Adjust**.  
5. Review outputs in:  
   - Sketch window.  
   - Legs & Points tables.  
   - Stats bar with misclosure and area.  

---

## 📄 Example CSV Input
```csv
Point,X,Y
P1,5000,8000
P2,5200,8000
P3,5200,8200
P4,5000,8200
```

---

## ⚡ Why Use This Tool?
- 🧑‍💼 Tailored for **surveyors in the field** without access to CAD/GIS.  
- 📊 Provides **instant adjustment results** with visualization.  
- 🌐 Runs **offline** – great for remote sites.  
- 🎯 Supports both **UTM and geographic (lat/long)** traverses.  
- 📦 Export results for reports & drawings.  

_______
Traverse Adjustment Tool
[![Watch on YouTube](https://img.youtube.com/vi/oSk2cCvP2OI/0.jpg)](https://youtube.com/shorts/oSk2cCvP2OI?feature=share)



---

## 📦 Installation
No installation required 🎉  
Simply clone this repo and open the HTML file:

```bash
git clone https://github.com/thevijayparmar/<repo>.git
cd <repo>
open "Traverse adjustment tool V6.0.html"
```

---

## 🔗 Live Demo
[![Website](https://img.shields.io/badge/🌐_Visit_BGol.in-2E69FF?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.bgol.in)

---

## 🛡️ License
This project is released under the **MIT License** – free to use and modify.  

---

👨‍💻 Developed by Vijay Parmar
