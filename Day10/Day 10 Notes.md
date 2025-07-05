# 📅 Day 10 – Exploring the Filter Shelf in Tableau

---

## 🔍 What I Explored Today

On Day 10 of my Tableau journey, I explored the **Filter Shelf** — one of the most powerful features that controls what data appears in a view.

I also learned about the **four filter types** available under the filter dialog box:

1. General  
2. Wildcard  
3. Condition  
4. Top  

Each plays a unique role in helping us narrow down data dynamically and meaningfully.

---

## 📘 What is the Filter Shelf?

The **Filter Shelf** is where we place dimensions or measures to restrict what data is shown in the visualization.

📊 For example, if we want to show only "Furniture" category sales — we drag `Category` to Filter Shelf and select "Furniture".

Filters help to:
- Reduce clutter  
- Focus on relevant data  
- Improve dashboard performance  
- Make visualizations cleaner and more insightful

---

## 🧠 Why Filters Are Important

| Reason                    | Benefit                                           |
|---------------------------|---------------------------------------------------|
| Focused Analysis          | See only relevant data for specific questions    |
| Improved Performance      | Filtered data loads faster and runs smoother     |
| Better User Experience    | Cleaner visuals lead to better storytelling      |
| Enhanced Interactivity    | Filters can be added as dashboard controls       |

---

## 🔎 Types of Filters in Tableau (via Filter Dialog)

When we apply a filter (especially on dimensions like Category, State, etc.), Tableau gives us multiple filter tabs. Here's what each one does:

---

### 1. 🔘 General Tab

**Purpose**: Manual selection of values from the field

✅ Use Case:  
Choose specific members to include or exclude

🧪 Example:  
Filter `Category` to show only “Furniture” and “Technology”

---

### 2. 🔤 Wildcard Tab

**Purpose**: Filter data based on **text-matching patterns** (like search)

✅ Use Case:  
Filter values that **start with**, **contain**, or **end with** a certain keyword or character

🧪 Example:  
- Want only states that contain the word "New"  
→ Use wildcard: `*New*` → matches "New York", "New Mexico"

📌 Pattern Guide:
- `*word` → ends with  
- `word*` → starts with  
- `*word*` → contains word  
- `word` → exact match

---

### 3. ⚙️ Condition Tab

**Purpose**: Filter dimension members **based on logic or condition using measures**

✅ Use Case:  
Only keep Sub-Categories where `Sales > 10,000`

🧪 Example:
- Field: `Sales`  
- Aggregation: SUM  
- Operator: `>`  
- Value: `10000`

📌 This is a **dynamic filter** that updates as the data changes.

---

### 4. 🔝 Top Tab

**Purpose**: Keep **Top N** or **Bottom N** items based on a measure

✅ Use Case:  
Show only the **Top 5 States by Sales**

🧪 Example:
- Choose: "By Field"
- Top: 5
- By: `Sales`
- Aggregation: SUM

📌 Very useful for leaderboard-style charts.

---

## 📊 Visualization Created

- **Chart 1:** Top 5 Sub-Categories by Sales  
  → Used `Top` Tab of Filter

- **Chart 2:** Filtered to only Furniture Category  
  → Used `General` Tab

- **Chart 3:** Filter states that contain "New"  
  → Used `Wildcard` Tab

- **Chart 4:** Only show Sub-Categories with `Sales > 10,000`  
  → Used `Condition` Tab

---
---

## 🧠 Summary of Learnings

| Filter Type  | Purpose                                      | Example Use Case                                 |
|--------------|----------------------------------------------|--------------------------------------------------|
| General      | Select specific field values manually         | Show only Furniture category                     |
| Wildcard     | Filter values using pattern/text match        | Filter states containing "New"                   |
| Condition    | Filter based on logic using a measure         | Keep Sub-Categories with Sales > 10,000          |
| Top          | Show top/bottom N values based on a measure   | Show Top 5 Sub-Categories by Sales               |

---
