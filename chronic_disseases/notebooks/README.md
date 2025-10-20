# 🩺 U.S. Chronic Disease Indicators — Level 1 Analysis
**Author:** Ronny Coulson  
**Goal:** Perform a foundational data analysis of chronic disease indicators across U.S. states and years using Pandas, NumPy, and Matplotlib.

---

## 🎯 Project Objective
The purpose of this project is to conduct a **basic exploratory data analysis (EDA)** of the CDC’s *U.S. Chronic Disease Indicators* dataset.  
The analysis aims to uncover trends in public health — how chronic conditions vary by **year**, **topic**, and **location** — and to visualize patterns that reflect changes in population health from 2015–2020.

---

## 🧱 Project Tasks

### **Phase 1 — Data Preparation**
1. Load the dataset into a DataFrame.  
2. Inspect the data’s shape, column names, and missing values.  
3. Clean the data:
   - Remove irrelevant or empty rows and columns.  
   - Convert `DataValue` and other numeric fields into proper numerical types.  
   - Rename or simplify columns for clarity.  

---

### **Phase 2 — Basic Analysis**
This phase focuses on identifying general trends and distributions.

1. **Topic Frequency**  
   - Determine which health topics appear most often (e.g., Cancer, Diabetes, Heart Disease).  
   - Visualize with a bar chart.  

2. **Yearly Average Indicators**  
   - Calculate the average `DataValue` per year to identify overall U.S. health trends.  
   - Visualize with a line chart showing changes over time.  

3. **Top States**  
   - Find states with the highest and lowest average chronic disease indicators.  
   - Visualize as a horizontal bar chart.  

4. **Data Value Distribution**  
   - Explore how `DataValue` is distributed across the dataset.  
   - Visualize as a histogram to identify skew or concentration.  

5. **By Sex (optional)**  
   - Compare indicators between males and females to identify disparities.  

---

### **Phase 3 — Visualization & Interpretation**
Create a small set of **4–5 visualizations** that summarize the findings clearly.  
Each chart should include:
- A descriptive title  
- Proper axis labels  
- A short markdown explanation of the insight  

Example Insights:
- “Cancer and Diabetes are the most reported chronic health topics.”  
- “The average indicator value decreased slightly between 2015–2020.”  
- “Southern states show higher chronic disease rates than Western states.”  

---

### **Phase 4 — Summary of Insights**
Conclude with short, data-backed insights:
- Which health topics dominate national reporting.  
- The overall direction of chronic disease indicators over time.  
- Regional variations (best and worst performing states).  
- Observations related to gender differences in certain indicators.  

---

## 📦 Project Structure
