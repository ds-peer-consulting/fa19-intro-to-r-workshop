# R Fundamentals Workshop
Division of Computing, Data Science, and Society - Data Peer Consultants (Fall 2019)

Created by Jahnavi Singh, Richa Bhattacharya

## Purpose
This workshop is an introduction to R fundamentals for an audience with no prior experience to R. It walks through Exploratory Data Analysis techniques (data cleaning, data manipulation, and data visualization) and statistical analysis/ regression modeling in R.

1. Dataset: Used the [Framingham Heart Study Dataset](https://www.kaggle.com/amanajmera1/framingham-heart-study-dataset#framingham.csv) pulled from Kaggle for analysis.
2. Packages Utilized: [dplyr](https://dplyr.tidyverse.org/), [ggplot2](https://ggplot2.tidyverse.org/), [gridExtra](https://www.rdocumentation.org/packages/gridExtra/versions/2.3), [DMwR](https://www.rdocumentation.org/packages/DMwR/versions/0.4.1), [e1071](https://www.rdocumentation.org/packages/e1071/versions/1.7-3), [DAAG](https://www.rdocumentation.org/packages/DAAG/versions/1.24).

## Section-Specific Goals

1. Data Cleaning: Removing null values, extra spaces and duplicates.
2. Data Manipulation: Adding and mutating columns based on data-specific conditions.
3. Data Visualization:
- Creating Graphs: Ex.: lineplot, boxplot, density curves, and histograms. 
- Arranging Multiple Graphs
4. Statistical Analysis: Computing the mean, median, and summary for columns.
5. Regression Analysis: Using one variable to predict another. 

## How to Use

### File Structure
|-- README.md  
|-- Fa19_R_Workshop  
|----|-- R_Workshop_Framingham.ipynb  
|----|-- R_Workshop_Framingham_With_Answers.ipynb  
|----|-- framingham.csv  
|----|-- ggplot2-cheatsheet.pdf  

### How to Launch R Jupyter Notebook
1. Create a new virtual environment
2. Install an R kernel in Jupyter similar to this [tutorial](https://medium.com/@kyleake/how-to-install-r-in-jupyter-with-irkernel-in-3-steps-917519326e41) or this [tutorial](https://kilnofthesecondflame.github.io/python/jupyter-notebook/kernel/installing-venv-R-kernel/)
3. Launch Jupyter and run `R_Workshop_Framingham.ipynb` from the R kernel. 

*Alternatively, you can directly pull the notebook into your UC Berkeley Datahub by clicking on this [link](https://datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fjanuusingh%2FR_Fundamentals_Workshop&urlpath=tree%2FR_Fundamentals_Workshop%2FFa19_R_Workshop)*

## Additional Resources
1. [R Cheatsheets](https://rstudio.com/resources/cheatsheets/)
2. [Detailed Framingham Analysis](https://rpubs.com/Shaahin/Framingham)
3. [More Regression in R](https://www.machinelearningplus.com/machine-learning/complete-introduction-linear-regression-r/)
4. [R for Beginners](https://www.statmethods.net/r-tutorial/index.html)
5. [R Programming Youtube Tutorial](https://www.youtube.com/watch?v=_V8eKsto3Ug)

