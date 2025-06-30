# 📅 Day 6 – Geographic & Map Visualizations in Tableau

---

## 🔍 What I Learned Today

Today I explored how Tableau can visualize geographic data using maps. Specifically, I learned:

1. 🗺️ Symbol Map  
2. 🟩 Filled Map  
3. ✨ Highlighter  
4. ⚙️ Map Customization Options (themes, layers, labels, icons, etc.)

These visualizations are incredibly useful when data includes location-based fields like Country, State, City, etc.

---

## 🗺️ 1. Symbol Map

### 🧠 What is it?
A **Symbol Map** displays geographic locations using marks (symbols/icons) placed on a map at specific coordinates — usually defined by **Latitude** and **Longitude**.

### ✅ Use Case:
Visualizing `State`-wise data (e.g., Sales or Quantity) across the map using **icons** or **custom shapes**.

---

### 📌 Shelf Configuration:
- **Columns:** `Longitude`
- **Rows:** `Latitude`
- **Color:** `State`
- **Label:** `State`
- **Detail:** `State`
- **Size (optional):** `Sales` – to make symbols bigger for higher sales
- **Shape (optional):** custom icons (e.g., circle, star, etc.)

---

### 📌 Steps:
1. Drag `Longitude` to Columns  
2. Drag `Latitude` to Rows  
3. Drag `State` to **Color**, **Label**, and **Detail**  
4. Drag `Sales` to **Size** (optional for impact-based symbols)  
5. From the **Marks dropdown**, choose "Shape" or "Circle"  
6. Customize shape using the Shape Shelf (e.g., star, arrow)

---

### 📊 Insight:
- Higher sales = larger icons
- Colored marks distinguish states
- You can customize icon shape and size for better storytelling

---

## 🟩 2. Filled Map

### 🧠 What is it?
A **Filled Map** uses colored geographic regions (like states or countries) where **color intensity represents a value** (e.g., sales, profit).

### ✅ Use Case:
Displaying `Sales` by State with deeper color representing higher values.

---

### 📌 Steps:
1. Double-click on `State` → Tableau automatically plots the map  
2. Drag `Sales` to **Color Shelf**  
3. From the **Marks dropdown**, choose "Map" (if not selected)  
4. Tableau fills each state with color based on sales

---

### 📊 Insight:
- Darker colors = higher values
- Great for visual comparisons across regions

---

## ⚙️ 3. Map Customization Options

### 🧠 What Are These?
Tableau lets you customize the look and feel of the map background and layers using **Map Options**.

---

### 📌 To Access:
Go to **Map → Map Layers** (in the top menu bar)

---

### 🧰 Key Options Explored:

| Feature                 | Description |
|--------------------------|-------------|
| **Show/Hide State Borders** | Turn state outlines on/off |
| **Show/Hide Place Names**   | Show or hide city/state labels |
| **Map Style**               | Change theme: Normal, Dark, Light, Satellite, Streets |
| **Background Layers**       | Show/hide coastline, country borders, land cover, etc. |
| **Zoom & Pan**              | Adjust map position manually |

---

### 📊 Insight:
- Map themes help match your dashboard style  
- Hiding borders/labels creates cleaner visualizations  
- Satellite style gives real-world map feel  

---

