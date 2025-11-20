Project Plan: Activity 15 

Goal:

The goal is to create a reproducible portfolio analysis from activity 14, and practice using GitHub to manage workflows like branching, issues, and pull requests.



Needs:

Software: R, RStudio, Quarto, Git.
Packages: tidyverse (for data wrangling), ggplot2 (for visualization), dcData (for baby names dataset), knitr.
Data Source: Armed Forces demographic data (Google Sheets) and the BabyNames dataset from the dcData package.
Version Control: A GitHub account and a public repository.



Steps
1. The Analysis
Setup: Initialize a new Quarto document (.qmd) with a YAML header specifying PDF output.

Data Wrangling (Armed Forces):
Load data from the provided Google Sheet.
Define column names and rank titles manually.
Clean data by removing 'Total' columns and separating 'Branch' and 'Sex'.
Pivot data to create summary tables for Male and Female enlisted personnel.

Data Visualization (Baby Names):
Filter BabyNames data for specific names (James, Michael, Jennifer, Jessica).
Create a multi-line plot showing trends over time using ggplot2.
Add professional labels, titles, and accessible alt text.

Mathematical Function Plot:
Define a function to calculate box volume based on cutout length.
Plot the function curve to identify the maximum volume.
Final Output: Compile the document to PDF to ensure all tables and figures render correctly.


2. The Workflow
Initialization: Create a new public GitHub repository named Activity15.

Issue Tracking:
Create Issue #1: "Add Activity 14 Analysis Files".
Create Issue #2: "Update README and Plan".

Branching:
Create a dev branch to isolate changes from the main branch.

Commits & Merging:
Switch to the dev branch.
Commit the .qmd, .pdf, and Plan.md files with a descriptive message closing Issue #1.
Commit the README.md updates with a message closing Issue #2.
Push the dev branch to GitHub.

Review:
Open a Pull Request (PR) from dev to main.
Merge the PR to finalize the project on the main branch.

