# 📅 Day 2 – Dimensions, Measures, Shelves & Basic Visualizations in Tableau

---

## 🔍 What I Explored Today

Today, I explored the foundational elements of Tableau that are essential for building meaningful and interactive visualizations:

- **Dimensions vs Measures**
- **Tableau Shelves** (Color, Size, Label, Text)
- **Bar Chart and Tree Map**

---

## 🧠 Understanding Dimensions and Measures

In Tableau, every field in your dataset is either a **Dimension** or a **Measure**.

| Aspect      | Dimensions                              | Measures                           |
|-------------|------------------------------------------|------------------------------------|
| Definition  | Qualitative fields (categories)          | Quantitative fields (numeric)      |
| Examples    | Region, Category, Customer Name          | Sales, Profit, Quantity            |
| Usage       | Used to slice data                       | Used to aggregate data             |
| Aggregation | Not aggregated                           | Aggregated by default (SUM, AVG)   |
| Role        | Answer “What?”                           | Answer “How much?”                 |

🔸 **In Tableau interface:**
- Dimensions appear in **blue** (categorical)
- Measures appear in **green** (numerical)

---

## 📦 Tableau Shelves – What Are They?

**Shelves** in Tableau are the areas where you drag fields to control how your chart looks.

### ✅ Key Shelves I Explored:

| Shelf  | Purpose |
|--------|---------|
| **Columns** | Defines the X-axis (Horizontal) |
| **Rows**    | Defines the Y-axis (Vertical) |
| **Color**   | Changes color based on a field (category/value) |
| **Size**    | Controls size of marks (e.g., size of bars or circles) |
| **Label**   | Adds text values directly to marks (like sales values) |
| **Text**    | Similar to label – used mostly in text tables |
| **Tooltip** | Shows extra info when hovering on a mark |

✅ **Example**: Dragging `Sales` to Size increases the size of bars based on sales value.

---

## 📊 Bar Chart – Hands-On

**Goal**: Visualize **Sales by Category**

### Steps:
1. Drag `Category` → Columns
2. Drag `Sales` → Rows
3. Drag `Profit` → Color (to show profit level by color)
4. Drag `Sales` → Label (to show values on bars)

📌 Insight:
- Bar charts are excellent for comparing categories side by side.
- You can use **Sort** to rank the bars in descending order.

---

## 🌲 Tree Map – Hands-On

**Goal**: Visualize **Sales by Sub-Category**

### Steps:
1. Drag `Sub-Category` → Label
2. Drag `Sales` → Size
3. Drag `Profit` → Color

🔸 **Tree Map** uses size and color to represent multiple dimensions at once.

📌 Insight:
- Bigger box = higher sales
- Darker/green = higher profit; Red = low/negative profit
- Useful when space is limited, but categories are many

---

## 🧠 Learnings & Observations

- **Dimensions and Measures** form the base of every visualization.
- **Shelves** like Color and Size add more context without extra visuals.
- **Bar Charts** are best for simple comparisons.
- **Tree Maps** offer compact, multi-variable insights.
- Using **Label** makes visuals more informative without clutter.

---

## 🧪 Dataset Used:
Sample Superstore (built-in Tableau dataset)

---

📂 **Files in this Folder:**
- 

