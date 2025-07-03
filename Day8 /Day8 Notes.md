# 📅 Day 8 – Creating Groups in Tableau

---

## 🔍 What I Explored Today

On Day 8, I learned how to **create groups** in Tableau — a helpful feature that lets us combine multiple values of a dimension into a single grouped value.

This is very useful for simplifying complex datasets, performing grouped analysis, and reducing the number of marks in a view.

---

## 📘 What is a Group in Tableau?

In Tableau, a **Group** allows you to **combine multiple dimension members** into a single label or category.

It does **not affect the original data**, but creates a **new field** representing the grouped values.

---

### 🧠 Why is Grouping Needed?

Often, datasets contain **too many categories**, many of which may be small or not individually relevant. Grouping helps by:

- 🔢 **Reducing clutter** on visualizations
- 🧹 **Simplifying** your data story
- 📊 Enabling **aggregate comparisons**
- ✅ Helping you focus on broader business groupings

---


You want to group them as:

- **Technology** → Phones, Copiers  
- **Furniture** → Chairs, Tables  
- **Office Supplies** → Accessories, Binders

Instead of analyzing all 6 separately, you can analyze just 3 business groups using Tableau Group.

---

## 🛠️ How to Create a Group in Tableau

### Method 1: Manual Grouping in the View

1. In the view (e.g., bar chart), **select multiple dimension values** (e.g., Ctrl + click on "Phones" and "Copiers")
2. Right-click → Click **Group**
3. A new field like `Sub-Category (Group)` will be created in the Data pane
4. Drag this new group field into the view for analysis

### Method 2: Create Group from Data Pane

1. Right-click the dimension field (e.g., `Sub-Category`) → Select **Create → Group**
2. In the dialog box, select values and click **Group**
3. Rename the groups as needed
4. Click OK → Group field appears in Data Pane

---

## 📊 Use Case I Tried

**Grouped multiple states** into two custom groups:  

Then I compared `Sales` across these two groups.

📌 This made it easier to see regional performance, instead of analyzing each state individually.

---

## 🧠 Summary of Learnings

| Feature     | Purpose                                | Benefit                                |
|-------------|----------------------------------------|----------------------------------------|
| Group       | Combine dimension values into one unit | Simplifies analysis and reduces clutter|

---
