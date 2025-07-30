# Impurity Analysis Case Study

This repository presents a comprehensive data analysis case study investigating the **impact of catalyst concentration, temperature, and reaction time** on **impurity levels** across three different chemical reactors and work shifts.

📊 Can process impurities be reduced by optimizing reactor conditions?

This case study explores that question by analyzing the effects of catalyst concentration, temperature, and reaction time across multiple reactors and work shifts using Python, Power BI, and JMP.

🔬 The study aims to identify significant factors affecting impurity levels using statistical modeling and data visualization techniques.

---

## 📁 Project Structure

- `Impurity_Analysis_Case_Study.ipynb` — Main Python notebook using `pandas`, `statsmodels`, and `matplotlib`
- `Impurity_Analysis_Case_Study.html` — **Interactive HTML preview** of the notebook (viewable [here](https://cchiayik.github.io/Impurity-Analysis-Case-Study/))
- `Impurity.csv` — Cleaned dataset containing reactor operation parameters and impurity values (viewable [here](https://github.com/cchiayik/Impurity-Analysis-Case-Study/blob/impurity-analysis-case-study/data/Impurity.csv))
- `Impurity_Analysis_Case_Study.pbix` — Dashboard visualizing trends and interactions across variables (download [here](https://github.com/cchiayik/Impurity-Analysis-Case-Study/raw/refs/heads/impurity-analysis-case-study/power_bi/Impurity%20Analysis%20Case%20Study.pbix))
- `Impurity_JMP.jmp` — DOE model and profiling using JMP (download [here](https://github.com/cchiayik/Impurity-Analysis-Case-Study/raw/refs/heads/impurity-analysis-case-study/jmp_analysis/Impurity%20JMP.jmp)) (required JMP software, viewer can choose to access HTML for JMP below as well)
- `Impurity_JMP_Least_Squares.htm` — **Interactive HTML preview** of the JMP (viewable [here](https://cchiayik.github.io/Impurity-Analysis-Case-Study/Impurity%20JMP%20-%20Fit%20Least%20Squares.htm ))
- `Impurity_Analysis_Case_Study_JMP_Report.pdf` - **PDF Report** of the JMP  (viewable [here](https://github.com/cchiayik/Impurity-Analysis-Case-Study/blob/impurity-analysis-case-study/jmp_analysis/Impurity%20Analysis%20Case%20Study.pdf)) ***IF the PDF cannot render (download [here](https://github.com/cchiayik/Impurity-Analysis-Case-Study/raw/impurity-analysis-case-study/jmp_analysis/Impurity%20Analysis%20Case%20Study.pdf))
---

## 🚀 Tools & Technologies

| Tool         | Purpose                               |
|--------------|----------------------------------------|
| Python       | Data cleaning, regression modelling     |
| Power BI     | Visual analytics dashboard             |
| JMP          | Advanced DOE and model profiling       |

3D Contour Plot in JMP
---
<img width="857" height="417" alt="image" src="https://github.com/user-attachments/assets/d7e87979-b2df-472e-a1ec-2e25b08c6172" />

Actual vs Predicted Plot with matplotlib in Jupyter
---
<img width="1044" height="823" alt="image" src="https://github.com/user-attachments/assets/d48ea2f8-b3ab-41ef-afaa-20ca494b77f2" />

Table with Conditional Formatting, Bar Chart of Impurity for Each Reactors
---

<img width="1316" height="738" alt="Screenshot 2025-07-27 225241" src="https://github.com/user-attachments/assets/536a690e-82d5-4b9e-8551-2b3590f2f6a8" />



## 🔎 Highlights

- Multiple linear regression with interaction terms  
- Full factorial insights on reactor and shift variation  
- Visualizations via both **Power BI** and **Jupyter Notebook**
- DOE profiling and validation using **JMP**

📈 Outcome Summary
---
- Identified catalyst concentration and temperature as significant factor affecting impurity level via regression
- Found Reactor 3 under out-of-control conditions using SPC analysis
- Designed optimal setpoints using JMP prediction profiler and 3D contour plots
- Built a Power BI dashboard for real-time impurity monitoring

---

## 🌐 Live Notebook Preview

➡️ View the rendered notebook in your browser:  
🔗 [https://cchiayik.github.io/Impurity-Analysis-Case-Study/](https://cchiayik.github.io/Impurity-Analysis-Case-Study/)

---

💡 **What I Learned**
---
- How to integrate Python, Power BI, and JMP for end-to-end manufacturing data analysis
- The limits of assuming linearity without checking interaction effects
- How SPC tools can reveal hidden process instabilities
- How to communicate insights through visual dashboards for non-technical stakeholders

## 📌 Usage

You can clone the repository and explore the analysis:

```bash
git clone https://github.com/cchiayik/Impurity-Analysis-Case-Study.git
