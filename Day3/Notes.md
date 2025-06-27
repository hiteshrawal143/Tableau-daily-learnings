# 📅 Day 3 – Packed Bubble, Word Cloud, and Stacked Bar Chart in Tableau

---

## 🔍 What I Learned Today

Today, I explored three powerful visualization types in Tableau using the **Sample Superstore** dataset:

1. 🎈 Packed Bubble Chart  
2. 🌥️ Word Cloud (Text Cloud)  
3. 📊 Stacked Bar Chart

Each chart was created with specific combinations of **Sales** and **State**, **Category**, and **Sub-Category**.

---

## 🎈 1. Packed Bubble Chart

### 🧠 What is it?
A **Packed Bubble Chart** uses circles (bubbles) sized proportionally to a measure value. It’s useful for visualizing part-to-whole relationships when comparing categories.

### ✅ Use Case:
**Sales by State**

### 📌 Steps:
1. Drag `State` → **Label**
2. Drag `Sales` → **Size**
3. Drag `Sales` → **Color** (to highlight value difference)
4. Select **Packed Bubble** from the **"Show Me"** panel

### 📊 Insight:
- Bigger bubbles = Higher Sales
- Bubble layout is space-efficient and visually intuitive
- Great for identifying top-performing states at a glance

---

## 🌥️ 2. Word Cloud (Text Cloud)

### 🧠 What is it?
A **Word Cloud** displays text labels where the **font size** corresponds to a measure (e.g., Sales). It's commonly used to highlight most frequent or highest-value items.

### ✅ Use Case:
**Sales by State**

### 📌 Steps:
1. Drag `State` → **Text**
2. Drag `Sales` → **Size**
3. Select **Text Cloud** from the **"Show Me"** panel

### 📊 Insight:
- State names appear bigger for higher sales
- Visually highlights top states without traditional charts
- More artistic and ideal for presentations

---

## 📊 3. Stacked Bar Chart

### 🧠 What is it?
A **Stacked Bar Chart** shows the breakdown of total values by categories using stacked segments of different colors.

### ✅ Use Case:
**Sales by Category**, broken down by **Sub-Category**

### 📌 Shelf Configuration:
- **Columns:** `Category`
- **Rows:** `Sales`
- **Color Shelf:** `Sub-Category`
- **Text Shelf:** `Sales`, `Category`
- **Detail Shelf:** `Sub-Category`

### 📌 Steps:
1. Drag `Category` → Columns
2. Drag `Sales` → Rows
3. Drag `Sub-Category` → Color
4. Drag `Sales` and `Category` → Label/Text
5. Drag `Sub-Category` → Detail (for segmenting)

### 📊 Insight:
- Helps compare both total sales by category and how sub-categories contribute
- Clear visual breakdown using color and stacked bars
- Easy to spot which sub-categories are dominating in each category

---
