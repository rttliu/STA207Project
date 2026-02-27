# STA207 Project

This repository contains the group project for STA207. The project focuses on statistical modeling, analysis, and reproducible reporting. All code, data processing steps, and final results are maintained here to ensure transparency and collaborative development.

## How to Run the Project (For Collaborators)

To ensure reproducibility, all collaborators should clone the repository and run the analysis from the project root directory.

1. In RStudio, go to: File → New Project → Version Control → Git  

2. Use the following repository URL: https://github.com/rttliu/STA207Project.git

3. Choose a local directory and click **Create Project**.

After cloning, confirm that the project root contains: README.md, STAR.tab, code/, report/, and output/.

To load the dataset, run the following in R from the project root:

```r
df <- read.table("STAR.tab", header = TRUE, sep = "\t")
```


## Structure

- `STAR.tab` – raw datasets  
- `code/` – scripts for data cleaning, modeling, and analysis  
- `report/` – R Markdown files for the final report  
- `output/` – generated figures and results  

## Reproducibility

All analyses are written in R and organized to allow full reproducibility.  Please pull the latest version of the repository before making changes.
