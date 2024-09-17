# PA 4 - Data Wrangling and Data Visualization

## I. Intended Learning Outcomes: 
1. To identify the codes and functions needed in cleaning and visualizing data
2. To be able to apply and use the different codes and functions in creating a Python program that will
be used in data wrangling and data visualization

## II. Instructions:
Download the ECE Board Exam 2 dataset found on this link: **bit.ly/ECEBoardExamDataset** and write a
Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter
notebook in the dedicated submission bin.

# **ECE BOARD EXAM PROBLEM**: 
Using data wrangling and data visualization technique with
storytelling, analyze the data and present different (i) data frames; and (ii) visuals using the dataset given.

## Problem 1.A: 
**Create the following data frames based on the format provided:**
Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant as
Instrumentation and hometown Luzon

### Documentation for Problem 1.A:
1. Function **.copy()** was used to create a copy of the filtered dataframe. This ensures that the original won't be affected whenever I modify the dataframe.
2. I used **pd.read_excel** function to read data from the given Excel file.

## Problem 1.B: 
**Create the following data frames based on the format provided:**
Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is
constant as Mindanao and gender Female

### Documentation for Problem 1.B:
1. Since 'Average' was not included in the given data, I used **.mean()** to get the average scores of the students.
2. I also used **.loc** indexer to assign the result of the calculation of the average scores.

## Problem 2: 
**Create a visualization that shows how the different features contributes to average grade. Does
chosen track in college, gender, or hometown contributes to a higher average score?**

### Documentation for Problem 2:
1.  **Seaborn's boxplot** was used to create the visualizations of the graph of the data.
2.  I also used **matplotlib.pyplot** to modify the appearance of the boxplot, such as setting the **figsize** and **labels**.

# Author
John Migz D. Alveza
## Date of Submission
September 17, 2024
## Section
2ECE-C
