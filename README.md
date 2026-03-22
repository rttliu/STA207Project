# STA207 Project

This repository contains the group project for **STA 207 - Statistical Research Methods II**. The project focuses on statistical modeling, analysis, and reproducible reporting. All code, data processing steps, and final results are maintained here to ensure transparency and collaborative development. The group project is finished by Ruitian Liu, Zhiye (Jerry) Jiang, Tommy Yu, Yuyu Zhang.

The project received a raw score of **19.2/20 (96%)**. A 2-point deduction was applied due to the use of AI-assisted tools that did not fully comply with course policies. As a result, the final recorded score is 17.2/20 (86%).

# Longitudinal Effects of Small Class Sizes on Academic Achievement

## Overview
This repository contains the final report analyzing the impact of class size on students' academic success. Specifically, the project explores the longitudinal effects of small class sizes on academic achievement from kindergarten through third grade. The analysis addresses challenges like non-random attrition and clustered data to provide robust, causal insights.

## Data Source
The analysis uses data from the **Tennessee Student/Teacher Achievement Ratio (STAR) project**, a large-scale, randomized controlled trial designed to study the effects of class size in early education.

## Methodology
To ensure accurate causal inference and handle data limitations, this project employs advanced statistical techniques:
* **Handling Attrition:** We utilized Multiple Imputation by Chained Equations (MICE) combined with doubly robust estimation to address severe non-random attrition in the later stages of the experiment.
* **Modeling:** We built a **mixed-effects model** featuring both school- and student-level random intercepts. This accounts for the naturally clustered nature of educational data.
* **Validation:** Model diagnostics and sensitivity analyses were conducted to ensure the robustness of the results.

## Key Findings
After correcting for attrition bias and controlling for relevant background variables, our analysis revealed the following:
* **Significant Math Gains:** Initial assignment to a small class in kindergarten results in a significant causal gain of approximately **7.5 points** on overall mathematics achievement.
* **Persistent Advantage:** The academic advantage gained from small class assignments remains constant across all grades (Kindergarten through 3rd grade).

## How to View the Report
The full analysis, including visualizations and detailed statistical outputs, is available in the `Final_Report.html` file. 

To view it:
1. Download the `Final_Report.html` file to your local machine.
2. Double-click the file, or right-click and open it with any modern web browser (e.g., Chrome, Firefox, Safari, Edge).

---
*Note: This report was generated as an HTML document for easy viewing and interactive data exploration.*

## Reproducibility

All analyses are written in R and organized to allow full reproducibility.  Please pull the latest version of the repository before making changes.
