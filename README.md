# NumPy Mini Projects Portfolio

This repository contains a collection of three mini-projects demonstrating the power of **NumPy** for data manipulation, mathematical optimization, and image processing. Each project focuses on solving a real-world scenario using vectorized operations and efficient array handling.

---

## 🚀 Projects Overview

### 1. Health Data Sanitizer & Scorer
**Goal:** Cleanse medical dataset "noise" and calculate patient health risk scores.
* **Data Cleaning:** Identifies missing values (represented as `-1`) and replaces them with the mean value of the respective column.
* **Normalization:** Implements **Min-Max Scaling** to bring all health metrics into a comparable range of 0 to 1.
* **Risk Assessment:** Applies custom weights to different health parameters and calculates a final weighted score for each patient to identify the individual at highest risk.

### 2. Satellite Coverage Optimizer
**Goal:** Optimize satellite-to-user communication using spatial geometry.
* **Coordinate Simulation:** Generates random 2D coordinates for 50 satellites within a defined space.
* **Distance Calculation:** Uses the **Euclidean Distance Formula** to find the proximity of each satellite to a specific user position.
* **Range Filtering:** Utilizes **Boolean Masking** to identify which satellites are currently within a specific signal range (e.g., less than 15 units).

### 3. NumPy Image Filter & Analyzer
**Goal:** Manipulate image data at the pixel level using matrix operations.
* **Image Simulation:** Creates a 5x5 grayscale image matrix using NumPy arrays.
* **Brightness Adjustment:** Demonstrates broadcasting by adding a scalar value to the entire matrix to "brighten" the image.
* **Structural Analysis:** Flattens image data for processing and calculates vertical brightness totals by summing pixels across specific axes.

---

## 🛠️ Tools Used
* **Language:** Python
* **Library:** NumPy
* **Environment:** Jupyter Notebook / Google Colab

## 📖 Key Concepts Demonstrated
* **Vectorization:** Performing operations on entire arrays without explicit loops.
* **Broadcasting:** Arithmetic between arrays of different shapes.
* **Slicing & Indexing:** Accessing and modifying specific data segments.
* **Aggregation:** Using `sum()`, `mean()`, `argmax()`, and `argmin()` for data insights.
* **Randomization:** Simulating real-world data distributions using `np.random`.
