# 📅 Day 4 – Tooltip Shelf and Shape Shelf in Tableau

---

## 🔍 What I Explored Today

On Day 4 of my Tableau learning journey, I explored two shelves that improve how users **interact with data visually**:

1. 💬 Tooltip Shelf  
2. 🔺 Shape Shelf

Both are not used to change chart axes or structure, but they enhance user experience and chart storytelling.

---

## 💬 1. Tooltip Shelf in Tableau

### 🧠 What is the Tooltip Shelf?

The **Tooltip Shelf** allows you to customize what data appears when a user hovers their mouse over a mark (bar, point, shape, etc.). It makes charts interactive and insightful without cluttering the view.

### ✅ Why It’s Useful:
- Shows extra info without displaying it directly on the chart
- Keeps the visual clean while enhancing interactivity
- Helps non-technical users understand what's behind each data point

### 📌 Use Case:
I added fields like `Profit`, `Region`, and `Sub-Category` to the Tooltip to enhance a bar chart showing **Sales by Category**.

### 📌 Steps:
1. Create a simple bar chart (e.g., `Category` → Columns, `Sales` → Rows)
2. Drag fields like `Profit`, `Sub-Category` to the **Tooltip** Shelf
3. Click the Tooltip Shelf to **customize the hover text**

📊 **Example Tooltip**:
> **Category**: Furniture  
> **Sales**: ₹1,20,000  
> **Profit**: ₹8,500  
> **Top Sub-Category**: Chairs

🔍 This helps viewers explore insights without overwhelming the visual.

---

## 🔺 2. Shape Shelf in Tableau

### 🧠 What is the Shape Shelf?

The **Shape Shelf** lets you use different **icons or symbols** (called shapes) to represent data points. You can assign a unique shape for each category or dimension.

### ✅ Why It’s Useful:
- Great for **symbolic storytelling** (e.g., using a truck for “Shipping”, phone for “Technology”)
- Helps non-numeric users grasp data meaning
- Makes dashboards visually appealing

---

### 📌 Visualization Built:
**Quantity by Category using Custom Shapes**

### 📌 Shelf Configuration:
- **Columns** → `Category`
- **Rows** → `Quantity`
- **Shape Shelf** → `Category` (assign each category a different shape)

### 📌 Steps:
1. Drag `Category` → Columns
2. Drag `Quantity` → Rows
3. Drag `Category` → Shape
4. From the **Marks dropdown**, select "Shape"
5. Click **Shape Shelf** to choose built-in or custom shapes

📌 **Tip:** You can import your own `.png` and `.jpg` images into Tableau’s Shapes folder for advanced customization.

---

## 🧠 Key Differences:

| Shelf         | Purpose                                 | Affects Chart Layout? | Interactive? |
|---------------|------------------------------------------|------------------------|---------------|
| Tooltip       | Shows hover info (on hover)              | ❌ No                  | ✅ Yes        |
| Shape         | Changes mark icon (e.g., circle → star)  | ✅ Yes (appearance)    | ✅ Visually   |

---

