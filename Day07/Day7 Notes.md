# 📅 Day 7 – Exploring Chart Interactions: View Data, Keep Only, and Exclude

---

## 🔍 What I Explored Today

On Day 7 of my Tableau learning journey, I explored how to **interact with chart elements** by using right-click or context menu options such as:

1. 🔎 View Data  
2. ✅ Keep Only  
3. ❌ Exclude

These are essential for data exploration and real-time filtering while analyzing visualizations.

---

## 🧠 Why This is Important

Often while analyzing charts, we notice something unusual — maybe a specific value is too high, or we want to temporarily remove something to focus on other data.

📈 That’s where these built-in options help:
- Without editing the worksheet manually
- Allowing **on-the-fly exploration**
- Making Tableau highly interactive and analytical

---

## 1. 🔎 View Data

### 🧠 What It Does:
When you click on a data point (like a bar or a bubble) and choose **View Data**, Tableau shows the **underlying raw data** behind that mark.

You can see:
- **Summary Tab**: Aggregated numbers shown on the chart  
- **Full Data Tab**: Row-level data from the source that forms this point

### ✅ Example:
Let’s say you click on the bar for **"Technology" category** in a bar chart showing **Sales by Category**.

- Click → Right-click → **View Data**  
- You’ll see all the sales transactions related to Technology

### 📌 Use Case:
Very helpful to **investigate**:
- Outliers
- Sudden spikes/drops
- Audit raw data behind charts

---

## 2. ✅ Keep Only

### 🧠 What It Does:
Selecting "Keep Only" **filters the entire view** to show **only the selected data point(s)**. Everything else is hidden.

### ✅ Example:
You’re viewing a **Bar Chart of Sales by Region**.

You click on **"East"** → Right-click → **Keep Only**  
👉 Now the chart updates to show only data for the East region.

### 📌 Use Case:
- Quickly isolate one value and remove distractions  
- Compare individual data points  
- Explore in-depth details for a specific category, product, or region

---

## 3. ❌ Exclude

### 🧠 What It Does:
The **Exclude** option removes the selected data point(s) from the view, so you can focus on the rest of the dataset.

### ✅ Example:
Same chart – **Sales by Region**.  
You right-click on **"Central"** → **Exclude**

👉 The "Central" region is removed, and chart recalculates for the remaining three.

### 📌 Use Case:
- Remove outliers or irrelevant values temporarily  
- Focus on underperforming regions by excluding top ones  
- Create "What if" scenarios visually

---
---

## 🧠 Summary of Learnings

| Feature      | Purpose                                    | Common Use Case                               |
|--------------|--------------------------------------------|-----------------------------------------------|
| View Data    | View raw data behind a chart mark          | Investigate transactions, verify data         |
| Keep Only    | Filter view to selected item(s) only       | Focus on a single category, region, or item   |
| Exclude      | Remove selected item(s) from visualization | Remove outliers or isolate remaining values   |

---
