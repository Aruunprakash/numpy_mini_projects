# 🚀 Data Science & Analytics Portfolio: NumPy & Pandas

This repository features a collection of five specialized projects demonstrating advanced data manipulation, financial analysis, and numerical optimization. These projects showcase the transition from raw, messy data to actionable insights using the core pillars of the Python data stack: **NumPy** and **Pandas**.

---

## 📂 Pandas Projects (Business & Strategic Analytics)

### 1. Movie Production & Marketing Optimizer
**Goal:** Analyze 1,000+ films to identify high-ROI production opportunities for a film studio.
* **Regex String Surgery:** Used `.str.extract()` to clean non-standard date formats (e.g., "II 2018").
* **Data Transformation:** Converted currency and runtime strings (e.g., "$10M", "120 min") into numeric types.
* **Data Integrity:** Implemented **Median Imputation** to handle missing revenue data without skewing results.
* **Vectorized ROI Calculation:** Created a Profitability Index to compare indie hits against blockbusters.

### 2. Global E-Commerce Performance Analyzer
**Goal:** Merge fragmented sales, product, and customer data into a unified business dashboard.
* **Multi-Source Integration:** Merged CSV and Excel files using complex **Inner and Left Join** logic.
* **Missing Value Handling:** Utilized `ffill` for time-series gaps and `interpolate()` for numeric trends.
* **Categorical Normalization:** Standardized global region names using mapping dictionaries.
* **Segmentation:** Utilized `groupby()` to identify high-value customer segments and regional profit drivers.

---

## 🔢 NumPy Projects (Numerical & Image Processing)

### 3. Health Data Sanitizer & Scorer
**Goal:** Cleanse medical dataset noise and calculate patient health risk scores.
* **Noise Reduction:** Identifies and replaces missing value markers with column-wise means.
* **Min-Max Normalization:** Scales varied health metrics into a standard 0 to 1 range.
* **Weighted Risk Assessment:** Applies linear algebra principles to calculate final patient risk scores.

### 4. Satellite Coverage Optimizer
**Goal:** Optimize satellite-to-user communication using spatial geometry.
* **Spatial Distance Calculation:** Implements the **Euclidean Distance Formula** to find proximity between 50+ satellites and a user.
* **Boolean Masking:** Efficiently filters satellites within a specific signal radius using bitwise logic.

### 5. Pixel-Level Image Filter
**Goal:** Manipulate image data as matrix structures.
* **Broadcasting:** Used scalar addition to adjust image brightness across an entire matrix.
* **Structural Analysis:** Used axis-based aggregation (`sum()`) to analyze vertical brightness distributions.

---

## 🛠️ Tech Stack
* **Languages:** Python
* **Libraries:** Pandas, NumPy
* **Techniques:** Vectorization, Regex, Data Imputation, Matrix Manipulation, Relational Merging

## 📖 Key Concepts Demonstrated
* **Data Integration:** Combining disparate sources into "Single Source of Truth" DataFrames.
* **Advanced Cleaning:** Using both pattern matching (Regex) and statistical filling (Mean/Median).
* **Efficiency:** Leveraging **Vectorization** to avoid slow Python loops on large datasets.
* **Business Intelligence:** Moving beyond "clean data" to calculate ROI, LTV, and Risk Metrics.

---
