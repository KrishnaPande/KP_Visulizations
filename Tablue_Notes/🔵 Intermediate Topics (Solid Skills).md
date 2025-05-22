Sure! Here's a detailed **theory-based overview** of the 🔵 **Intermediate Tableau Topics (Solid Skills)**. These concepts build on foundational knowledge and are essential for creating dynamic, analytical dashboards.

---

## 🔵 **1. Calculated Fields**

### 🧠 Theory:

Calculated fields allow you to create new data fields derived from your existing dataset. These can include numerical calculations, conditional logic, or text manipulations.

### ✅ Example Use Cases:

* Profit Margin = `SUM(Profit) / SUM(Sales)`
* IF statements: `IF [Sales] > 1000 THEN "High" ELSE "Low" END`

---

## 🔵 **2. Table Calculations**

### 🧠 Theory:

Table calculations are performed *on top of* aggregated data in your view. They compute values using data that’s already been visualized.

### 🛠 Common Functions:

* `RUNNING_SUM()`
* `RANK()`
* `WINDOW_AVG()`

### ✅ Example Use Case:

* Calculate year-over-year sales growth.
* Rank products by sales within each region.

---

## 🔵 **3. Parameters**

### 🧠 Theory:

A **parameter** is a dynamic input that allows user interaction. It’s like a variable that can be used in calculations, filters, or to control the view.

### ✅ Example Use Cases:

* Switch between "Sales" and "Profit" on a chart.
* Adjust a discount percentage and see real-time impact.
* Use a dropdown to filter by a selected region.

---

## 🔵 **4. Sets & Combined Sets**

### 🧠 Theory:

Sets are custom fields that define a **subset** of your data. They can be fixed (manually selected) or dynamic (based on conditions).

### ✅ Example Use Cases:

* Top 10 customers by sales (Dynamic Set).
* Compare sales inside vs. outside a selected category.

### ➕ Combined Sets:

* Combine two sets to see overlaps or differences.
* Example: Customers who bought in Region A **and not** in Region B.

---

## 🔵 **5. Data Blending vs Joins**

### 🧠 Joins:

* Combine data tables **within the same data source** using keys (e.g., Customer ID).
* Types: Inner, Left, Right, Full Outer.

### 🧠 Blending:

* Combine data from **different data sources** (e.g., SQL + Excel).
* Uses a **primary** (blue) and **secondary** (orange) data source.
* Often necessary when the data sources cannot be joined directly.

---

## 🔵 **6. Date Functions & Calculations**

### 🧠 Theory:

Dates are critical in time-series analysis. Tableau provides powerful date functions to manipulate and analyze time-based data.

### ⏱ Useful Functions:

* `DATEPART()`: Returns a part of a date (e.g., month)
* `DATEDIFF()`: Measures the difference between two dates
* `DATETRUNC()`: Rounds dates to the nearest unit (e.g., month, year)

### ✅ Example Use Cases:

* Calculate customer tenure.
* Compare current quarter sales to the previous quarter.

---

Would you like short **examples with visuals or formulas** for each of these intermediate topics next?
