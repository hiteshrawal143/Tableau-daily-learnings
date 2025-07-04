# 📅 Day 9 – Understanding Sets in Tableau

---

## 🔍 What I Explored Today

On Day 9 of my Tableau journey, I learned how to create and use **Sets**, which are **custom fields that define a subset of data** based on certain conditions or manual selection.

Sets are more **flexible and powerful** than Groups, especially when you want to analyze data based on dynamic conditions or logic.

---

## 📘 What is a Set in Tableau?

A **Set** is a **subset of your data** created by either:
- Manually selecting members (Static Set)
- Defining rules or conditions (Dynamic Set)

It results in a **boolean field** with values:
- `IN` → the item is part of the set  
- `OUT` → the item is not in the set

You can use Sets in:
- Filters  
- Color  
- Rows/Columns  
- Calculations  
- Combined logic and dashboards

---

## 🧠 Why Sets Are Important

Unlike Groups, which are **fixed labels**, Sets allow for:
- Condition-based grouping (e.g., Sales > 5000)
- Real-time filtering and interactivity
- More complex comparative analysis
- Useful logic inside calculated fields and dashboards

---

## 🔸 Types of Sets

### 1. 🧱 Static Set

A Static Set is **created manually** by selecting values from a dimension.

### ✅ Example:
- Select 5 specific `Sub-Categories` (e.g., Phones, Chairs, Binders)
- Right-click → Create Set  
- This set always includes these 5 items unless manually changed

📌 Useful when your data doesn’t change frequently.

---

### 2. ⚙️ Dynamic Set

A Dynamic Set is created by defining **rules or conditions** (based on measures or logic).

### ✅ Example:
Create a set of **Sub-Categories where Sales > 10,000**

**Steps**:
1. Right-click `Sub-Category` → Create Set  
2. Choose **Use all members**  
3. Go to **Condition tab**  
4. Set condition: `SUM(Sales) > 10000`  
5. Click OK → Set1 created

📌 This set will auto-update if sales data changes.

---

## 📊 Visualization Example: Highlighting Sub-Categories Based on Sales

I created a bar chart to **visually differentiate Sub-Categories** that are part of the Set (Sales > 10,000):

### 📌 Configuration:

- **Columns**: `Sub-Category`  
- **Rows**: `Sales`  
- **Color**: `Set1` (the dynamic set based on Sales)  
- **Sort**: Descending by Sales (optional for clarity)

### 💡 Output Insight:
- Sub-Categories `IN` the set are highlighted (e.g., darker color)
- Sub-Categories `OUT` of the set are dimmed
- Helps to quickly spot top-selling segments

---
---

## 🧠 Summary of Learnings

| Concept       | Description                                             | Use Case                                     |
|---------------|---------------------------------------------------------|----------------------------------------------|
| Set           | A defined subset of dimension values                    | Segment data for analysis/filtering          |
| Static Set    | Manually selected members                               | Fixed comparisons (e.g., top 5 products)      |
| Dynamic Set   | Condition-based members that auto-update                | Performance-based segmentation (e.g., high sales items) |

--
