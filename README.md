# STA207 Project

This repository contains the group project for STA207. The project focuses on statistical modeling, analysis, and reproducible reporting. All code, data processing steps, and final results are maintained here to ensure transparency and collaborative development.

## How to Run the Project

To ensure reproducibility, all collaborators should clone the repository and run the analysis from the project root directory.

1. In RStudio, go to: File → New Project → Version Control → Git  
2. Use the following repository URL: https://github.com/rttliu/STA207Project.git
3. Choose a local directory and click **Create Project**.

After cloning, confirm that the project root contains: README.md, STAR.tab, code/, report/, and output/.
To load the dataset, run the following in R from the project root:

```r
df <- read.table("STAR.tab", header = TRUE, sep = "\t")
```

## How to Update the Repository

To keep the project synchronized, all collaborators should commit and push their local changes after completing updates.

1. In RStudio, open the **Git** tab (top-right panel).
2. Check the modified files. If it displays an 'M' at the capital, then it is modified.
3. Click **Commit**.
4. Enter a clear commit message describing your changes (e.g., "Update data cleaning script").
5. Click **Commit**, then click **Push** to upload changes to GitHub. (You do not have to select the file and click Push)


## Reproducibility

All analyses are written in R and organized to allow full reproducibility.  Please pull the latest version of the repository before making changes.
