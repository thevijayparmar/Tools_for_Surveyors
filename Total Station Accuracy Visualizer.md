# 🎯 Total Station Accuracy Visualizer

A modern **offline web tool** to visualize and compare the **angular accuracy vs. linear error** of different **Total Stations** and a **Theodolite**.  
Ideal for **surveyors and engineers** when deciding what instrument suits their project requirements.

---

## ✨ Features

### 📏 Supported Instruments
- **High-Precision Total Station** (0.5″ accuracy)  
- **Standard Total Station** (1″ accuracy)  
- **General-Purpose Total Station** (2″ accuracy)  
- **Basic Total Station** (5″ accuracy)  
- **Theodolite** (20″ accuracy)  

### 📐 Accuracy Visualization
- **Angular Accuracy Chart** → Wedge visualization of angular spread.  
- **Linear Error Chart** → Bar chart showing error in **mm** at selected distance.  
- Adjustable **distance slider (1–5000 m)** to see how error grows with range.  

### 🧮 Built-in Calculations
- Formula: **Linear Error (mm) = Distance(m) × tan(θ) × 1000**  
- Displays step-by-step math for each instrument (θ conversion from arcseconds).  

### 🎨 UI & Experience
- 🌗 **Dark/Light Mode** toggle.  
- 🔭 Station emoji for intuitive visualization.  
- 🎆 Animated **radar beams, pings, and sparks** for engaging interaction.  
- 📊 Instrument cards with real-time linear error values.  
- Responsive layout – works on desktop and mobile.  

---

## 🖼️ Preview
<img width="2715" height="1678" alt="Screenshot 2025-08-26 114954" src="https://github.com/user-attachments/assets/0b339aeb-5549-40e4-8e18-c23d22088446" />


---

## 🚀 How to Use
1. Open **`Total Station Accuracy Visualizer.html`** in your browser.  
2. Use the **distance slider** to adjust survey range.  
3. Compare how each instrument’s **angular accuracy** translates into **linear error**.  
4. Expand **Mathematical Calculations** for detailed formulas.  

---

## 📄 Example
- At **100 m**:  
  - 0.5″ Total Station → ~0.24 mm error  
  - 1″ Total Station → ~0.48 mm error  
  - 5″ Total Station → ~2.4 mm error  
  - 20″ Theodolite → ~9.7 mm error  

---

## ⚡ Why Use This Tool?
- 📊 Helps compare **equipment accuracy** before purchase.  
- 🧑‍💼 Useful for **field engineers** planning tolerances for different distances.  
- 💻 Runs **completely offline** — no internet required.  
- 🎯 Interactive, visual, and intuitive for quick decision-making.  
____
Total Station Accuracy Visualizer
[![Watch on YouTube](https://img.youtube.com/vi/EbrU7c0L-qY/0.jpg)](https://youtube.com/shorts/EbrU7c0L-qY?feature=share)

---

## 📦 Installation
No installation required 🎉  
Simply clone this repo and open the HTML file:

```bash
git clone https://github.com/thevijayparmar/<repo>.git
cd <repo>
open "Total Station Accuracy Visualizer.html"
```

---

## 🔗 Live Demo
[![Website](https://img.shields.io/badge/🌐_Visit_BGol.in-2E69FF?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.bgol.in)

---

## 🛡️ License
This project is released under the **MIT License** – free to use and modify.  

---

👨‍💻 Developed by Vijay Parmar
