# **Employee Absence LRFM Analysis**

## Overview
This project analyzes the **Absenteeism at Work** dataset to understand employee absence patterns using an **Employee Absence LRFM (EA-LRFM)** framework. It segments employees into actionable groups (e.g., Chronic Absentees) based on **Length** (unique absence months), **Recency** (time since last absence), **Frequency** (absence count), and **Monetary** (total hours absent), with a deep dive into contextual factors like workload. The analysis aims to provide HR with insights for targeted interventions, such as health programs or workload adjustments.

## Dataset
- **Source**: [UCI](https://archive.ics.uci.edu/dataset/445/absenteeism+at+work)
- **Details**: 740 records, 36 unique employees, 21 attributes (e.g., Absenteeism time in hours, Work load Average/day)
- **Format**: CSV with semicolon (`;`) separation

## Notebook Structure
1. **Exploratory Data Analysis (EDA)**: Checks data quality, visualizes absence hours (boxplots with/without outliers), monthly trends, and correlations.
2. **LRFM Analysis**:
    - Calculates metrics, shows distributions (2x2 histograms), segments employees into four groups, and visualizes results (scatter, bar charts).
    - Explores absence reasons, demographics (Age, Education), clustering, and Work load Average/day’s impact via histograms, scatters, and bars.
3. **Strategies**: Recommends HR actions per segment (e.g., counseling for Chronic Absentees).

## Requirements
- **Python**: 3.6+
- **Libraries**: `pandas`, `matplotlib`, `seaborn`
- **Environment**: Jupyter Notebook

## Setup and Running
1. **Download Dataset**: Save `Absenteeism_at_work.csv` from Kaggle/UCI to your working directory.
2. **Install Dependencies**: Run `pip install pandas matplotlib seaborn`.
3. **Run Notebook**:
   - Open Jupyter: `jupyter notebook`
   - Load the `.ipynb` file and execute cells sequentially.
4. **Outputs**: Expect tables, plots (e.g., segment scatter, workload bars), and HR strategies printed in the notebook.

## Key Outputs
- **Visualizations**: Boxplots, histograms, scatter plots, and bar charts showing absence patterns and segment details.
- **Insights**: Identifies high-impact employees (e.g., Chronic Absentees), workload influences, and absence reasons (e.g., medical dominance).
- **HR Actions**: Tailored recommendations for each segment to reduce absenteeism.

## Additional Links
- To view presentation: [click here](https://www.canva.com/design/DAGkno1r9cQ/Jk5iC0fWWw69m58-pR8-eg/edit?utm_content=DAGkno1r9cQ&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## References
A. Martiniano and R. Ferreira. "Absenteeism at work," UCI Machine Learning Repository, 2012. [Online]. Available: https://doi.org/10.24432/C5X882.
