<h1 align="center">☕ Coffee Quality Analysis (Power BI)</h1>

A fully interactive **Power BI analytics project** built to understand global coffee quality patterns using advanced visual analytics, decision trees, key influencers, smart narratives, and interactive bookmarks.  
This report blends **business insights + data analytics** to evaluate what drives high coffee quality across origins, processing methods, and sensory attributes.

---

## 📑 Table of Contents
- [🔎 Project Overview](#overview)  
- [🎯 Business Problem](#business-problem)  
- [📂 Dataset](#dataset)  
- [🛠 Tools & Techniques](#tools-techniques)  
- [🧹 Data Preparation](#data-preparation)  
- [📊 Analysis Performed](#analysis-performed)  
- [📌 Key Insights](#key-insights)  
- [📸 Report Screenshots](#screenshots)  
- [👤 Author & 📧 Contact](#author-contact)  

---

## <a id="overview"></a>🔎 Project Overview
This project analyzes global specialty coffee quality using Power BI.  
The objective is to identify **what factors drive Total Cup Points**—the global scoring standard for coffee used by SCA (Specialty Coffee Association).

Using interactive visualizations, smart narratives, and machine learning–based insights, this dashboard provides a deep dive into:

- What makes a coffee “high-quality”
- Which countries consistently produce top-tier coffee
- Which sensory attributes contribute most to better cup scores

The entire report is built using **bookmarks** and **page-level navigation**, enabling a single-page interactive experience.

---

## <a id="business-problem"></a>🎯 Business Problem
Coffee quality evaluation is complex and depends on multiple sensory and non-sensory factors.  
The goal of this analysis is to answer:

- Which **countries of origin** consistently produce the highest-quality coffee?  
- Which **sensory attributes** (aroma, aftertaste, flavor, acidity, body, etc.) most strongly influence cup scores?  
- What **processing methods** and **bean types** lead to premium-quality coffees?  
- Can we build a **decision tree** that predicts what combinations produce the highest quality?  
- How do max/avg/median cup scores vary across origins?

These insights can help exporters, specialty roasters, and researchers understand **quality drivers** and **market potential**.

---

## <a id="dataset"></a>📂 Dataset
- **Source:** Coffee Quality Institute dataset (CQI) 
- **Rows:** ~211  
- **Columns:** Sensory attributes, farm details, processing method, country, altitude, etc.  
- **Years Covered:** Mostly 2023

---

## <a id="tools-techniques"></a>🛠 Tools & Techniques
- **Power BI Desktop**
- Power Query (Cleaning & Transformation)  
- DAX (only for calculated fields like Average Cup Scores if needed)  
- Key Influencer Visual  
- Decision Tree (through decomposition tree)  
- Smart Narrative  
- Bookmarks & Selection Pane  
- Slicers and Filters  
- Top-N Filtering  
- Interactive Tooltip Pages  

---

## <a id="data-preparation"></a>🧹 Data Preparation
Major steps performed in Power Query:

- Removed duplicates and null rows  
- Standardized column names  
- Ensured numeric fields (aroma, flavor, acidity, etc.) were stored as decimals  
- Cleaned inconsistent origin spellings  
- Converted text fields to proper case  
- Ensured Total Cup Points → numeric type  
- Created calculated columns for aggregated views (Avg, Median, Max Cup Points)

The dataset was then modeled for performance and loaded into Power BI for large-scale visual analysis.

---

## <a id="analysis-performed"></a>📊 Analysis Performed
### **1. Overall Quality Distribution**
- Average Total Cup Points across dataset  
- Max–Min spread  
- Median distribution by country  

### **2. Country-Level Quality Comparison**
- Compared **Max**, **Average**, and **Median** Cup Points  
- Top 5 highest-quality producing countries (based on Max Cup Points)  
- Variability analysis  

### **3. Key Influencers (Machine Learning Visual)**
Identified which factors most strongly push Cup Points upward:
- Aftertaste  
- Aroma  
- Flavor  
- Acidity  
- Body  

*A strong positive correlation was detected across these attributes.*

### **4. Decision Tree (Decomposition Tree)**
Breakdown of highest cup score contributors using:
- Country  
- Processing Method  
- Sensory attributes  
- Altitude  

### **5. Smart Narrative (AI Insights)**
Power BI auto-generated key summaries, such as:

- *Colombia had the highest Max Cup Points at 89.33, 2.68% higher than Guatemala.*  
- *Max vs Avg divergence was largest in Colombia (≈ 5.55).*  
- *Median Cup Points highest in Ethiopia (≈ 85.25), followed by Taiwan and Tanzania.*  

### **6. Top-N Analysis**
- Top 5 scoring countries  
- Top 5 aromatic profiles  
- Top 5 flavor profiles  

### **7. Interactive Dashboard with Bookmarks**
- Filters for country, processing method, roasted level  
- Bookmark toggles (switch insights pages in one click)  
- Hover tooltips for extra detail  

---

## <a id="key-insights"></a>📌 Key Insights
- **Ethiopia, Colombia, Taiwan, Tanzania, and Guatemala** consistently produce top-tier high-quality coffee.  
- **Aroma, Flavor, Aftertaste, Body, and Acidity** are the strongest influencers of cup scores.  
- **Colombia leads in maximum cup score** (89.33), but **Ethiopia leads median consistency**.  
- Processing method shows significant impact—washed and honey-processed coffees produce higher premium-grade scores.  
- Sensory attributes show strong correlations, meaning higher flavor often implies higher aroma, acidity, etc.  
- The interactive design (bookmarks + slicers) makes the report intuitive and extremely user-friendly.

---

## <a id="screenshots"></a>📸 Report Screenshots  


- **Key Influencers View**






<img width="1338" height="792" alt="Image" src="https://github.com/user-attachments/assets/8d770a2e-526b-4d1c-8e3f-ce7184207aac" />





  
- **Country of Origin Quality Comparison**






  <img width="1346" height="791" alt="Image" src="https://github.com/user-attachments/assets/f8794203-4b77-4b3a-80c0-216ac9e3fba7" />






- **Quality Parameter Visual**  






<img width="1342" height="802" alt="Image" src="https://github.com/user-attachments/assets/31da4fbf-a567-4c3d-a555-e4010088ec38" />


---

## <a id="author-contact"></a>👤 Author & 📧 Contact 

👤 Author: Vaibhav Goyal<br>
📧 Email: vg.goyal611@gmail.com<br>
💼 [LinkedIn](https://www.linkedin.com/in/vaibhav-goyal-29b70a30/)<br>
🧑‍💻 [Portfolio](https://github.com/vggoyal611)<br>
🌐 [Website](https://vaibhav-goyal-7nkea52.gamma.site)

---
