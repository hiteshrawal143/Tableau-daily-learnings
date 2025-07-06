# 📅 Day 3 – Packed Bubble, Word Cloud, Stacked Bar Chart & Detail Shelf in Tableau

---

## 🔍 What I Learned Today

Today, I explored three different types of visualizations and a very useful feature called the **Detail Shelf** in Tableau. These include:

1. 🎈 Packed Bubble Chart  
2. 🌥️ Word Cloud (Text Cloud)  
3. 📊 Stacked Bar Chart  
4. 🧩 Detail Shelf

Each chart was created using the **Sample Superstore** dataset and helped me understand how to present data in more dynamic and insightful ways.

---

## 🎈 1. Packed Bubble Chart

### 🧠 What is it?
A Packed Bubble Chart visualizes values as circles where **size indicates value**, and bubbles are packed into the space.

### ✅ Use Case:
**Visualizing Sales by State**

### 📌 Steps:
- Drag `State` → **Label**
- Drag `Sales` → **Size**
- Drag `Sales` → **Color**
- Select **Packed Bubbles** from the **Show Me** panel

### 📊 Insight:
- States with higher sales have bigger bubbles
- Color highlights performance difference
- Great for comparing a single measure across many categories in a compact view

---

## 🌥️ 2. Word Cloud (Text Cloud)

### 🧠 What is it?
A Word Cloud shows data where the **text size** reflects the value of a measure. Useful for identifying high-frequency or high-value items quickly.

### ✅ Use Case:
**Visualizing Sales by State**

### 📌 Steps:
- Drag `State` → **Text**
- Drag `Sales` → **Size**
- Select **Text Cloud** from the **Show Me** panel

### 📊 Insight:
- State names with higher sales appear larger
- Visually attractive and useful for quick overviews or storytelling

---

## 📊 3. Stacked Bar Chart

### 🧠 What is it?
A Stacked Bar Chart breaks down **total values into segments**, grouped and color-coded for better comparison.

### ✅ Use Case:
**Sales by Category, broken down by Sub-Category**

### 📌 Shelf Configuration:
- **Columns** → `Category`
- **Rows** → `Sales`
- **Color Shelf** → `Sub-Category`
- **Text Shelf** → `Sales`, `Category`
- **Detail Shelf** → `Sub-Category`

### 📌 Steps:
1. Drag `Category` → Columns
2. Drag `Sales` → Rows
3. Drag `Sub-Category` → Color
4. Drag `Sales` and `Category` → Label
5. Drag `Sub-Category` → Detail

### 📊 Insight:
- Allows you to compare total sales **and** see which sub-categories contribute most
- Useful for analyzing composition within each major group

---

## 🧩 Detail Shelf in Tableau

### 🧠 What is the Detail Shelf?

The **Detail Shelf** adds additional data to your visualization **without displaying it directly** on the chart. It allows Tableau to split marks in a more granular way.

### ✅ Why It’s Useful:

| Feature       | Purpose                                                                 |
|----------------|------------------------------------------------------------------------|
| Detail Shelf  | Adds more detail to the marks without showing the field in the view     |
| Chart Impact  | Doesn't change axes but increases granularity                           |


---
