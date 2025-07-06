# 📅 Day 5 – Filter Shelf and Pages Shelf in Tableau

---

## 🔍 What I Explored Today

On Day 5 of my Tableau journey, I focused on:

1. 🧹 Filter Shelf  
2. 📖 Pages Shelf

Both are powerful tools to **slice**, **filter**, and **navigate data better**, especially in large datasets.

---

## 🧹 1. Filter Shelf

### 🧠 What is the Filter Shelf?

The **Filter Shelf** allows you to control which data is included in your visualization by applying filters. You can filter dimensions or measures to show only relevant portions of data.

---

### ❓ Why is it Needed?

In real-world datasets, you often deal with **hundreds or thousands of records**. If you display everything at once, charts become cluttered and hard to read.

✅ The Filter Shelf helps you:
- Focus only on relevant values (e.g., top-performing cities)
- Reduce noise and improve clarity
- Customize the view based on business needs

---

### ✅ Use Case:
**Visualizing Quantity by Selected Cities**

---

### 📌 Configuration:
- **Filter Shelf**: `City`
- **Columns**: `City`
- **Rows**: `Quantity`
- **Color**: `City`
- **Label/Text**: `Quantity`

---

### 📌 Steps:
1. Drag `City` to Columns  
2. Drag `Quantity` to Rows  
3. Drag `City` to Filters → select desired cities (e.g., Delhi, Mumbai, Bangalore)  
4. Drag `City` to Color  
5. Drag `Quantity` to Label  

---

### 📊 Insight:
- Visualization became cleaner with fewer cities
- Color coding improved data distinction
- Labels made the chart easy to interpret at a glance

---

## 📖 2. Pages Shelf

### 🧠 What is the Pages Shelf?

The **Pages Shelf** allows you to break a visualization into **discrete pages**, based on the values of a dimension (like Category). It’s like creating a slideshow of your data — showing one slice at a time.

---

### ❓ Why is it Needed?

In charts with multiple categories or segments, it’s often **overwhelming to view everything together**.

✅ Pages Shelf helps you:
- View one part of the data at a time
- Discover trends per category
- Create animated or interactive dashboards for storytelling

---

### ✅ Use Case:
**Sales by State, one Category at a time (using Pages Shelf)**

---

### 📌 Configuration:
- **Pages Shelf**: `Category`
- **Columns**: `State`
- **Rows**: `Sales`
- **Color**: `Sub-Category`

---

### 📌 Steps:
1. Drag `State` to Columns  
2. Drag `Sales` to Rows  
3. Drag `Sub-Category` to Color  
4. Drag `Category` to Pages  
5. Use the **Page controls** (top-right of the worksheet) to navigate

---

### 📊 Insight:
- Helped analyze each category independently
- Viewers can flip through categories like slides
- Excellent for presentations or dashboard walkthroughs

---

## 🧠 Summary of Learnings

| Feature       | Purpose                                  | Why It's Needed                                         |
|---------------|-------------------------------------------|----------------------------------------------------------|
| Filter Shelf  | Filter and control what data is shown     | To reduce clutter and focus on specific data points      |
| Pages Shelf   | Break visuals into navigable “pages”      | To isolate data segments and improve data storytelling   |

---
