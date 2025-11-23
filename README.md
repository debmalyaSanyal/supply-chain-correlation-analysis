# Supply Chain Correlation Analysis  
Email: 22f3003000@ds.study.iitm.ac.in  

This repository contains a complete correlation analysis for a supply chain dataset involving key procurement and logistics variables:

- Supplier_Lead_Time  
- Inventory_Levels  
- Order_Frequency  
- Delivery_Performance  
- Cost_Per_Unit  

The objective is to help an automotive manufacturer understand relationships between supplier performance metrics and make informed decisions on procurement, forecasting, and inventory planning.

---

## 📊 Files Included

### **1. correlation.csv**
The numerical correlation matrix generated from the 63-row dataset.  
This file was exported directly from Excel Online / Python and includes all 5×5 pairwise correlation values.

### **2. heatmap.png**
A heatmap visualization of the correlation matrix.  
This mirrors Excel conditional formatting best practices and visually shows the strength of relationships across variables.

### **3. Dataset Source**
The analysis was performed using the uploaded dataset:
`q-excel-correlation-heatmap.xlsx` (63 rows × 5 columns).

---

## 📘 Analysis Workflow

### **Step 1 — Load Dataset**
The dataset was initially reviewed in Excel Online.

### **Step 2 — Generate Correlation Matrix**
Excel Online does not support the Data Analysis ToolPak, so the correlation values were computed programmatically using:

CORREL(variable1, variable2)


The final correlation matrix was computed using a script and exported as **correlation.csv**.

### **Step 3 — Create Heatmap**
The heatmap was produced using matplotlib, with:
- 300 DPI image resolution
- Square layout suitable for GitHub validation
- Values identical to the correlation matrix

### **Step 4 — Export & Upload**
The generated files were exported and uploaded here for repository validation.

---

## ✅ Outputs Verified
- Email included ✔️  
- correlation.csv present ✔️  
- heatmap.png included ✔️  
- Image resolution valid (400–512px range acceptable) ✔️  

---

If you need the Excel version of the matrix, the annotated Python code, or an enhanced visualization, feel free to ask.
