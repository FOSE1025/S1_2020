# Week 9 SGTA
# PRAC_01

The following are group exercises. For every group, nominate one person who will explain what you have done. The group exercises will be carried out as zoom breakouts and always the same students will be in the same group. Each time, nominate a different person so that all have the opportunity to practice their presentation skills.

## 1-1. Line charts with trends (5 minutes + 5 minutes discussion)

The following CSV file has been downloaded from https://people.sc.fsu.edu/~jburkardt/data/csv/csv.html and contains records of floods of the Nile river over 570 years.

* [nile.csv](nile.csv)

In groups, conduct the following activities:

1. Plot the data as a line plot.
2. Add a linear trend line.
3. Does the trend line show an increase or a decrease of severity of floods by the Nile river?


## 1-2. Pivot tables for summaries (15 minutes + 10 minutes discussion)

The following CSV file has been downloaded from https://people.sc.fsu.edu/~jburkardt/data/csv/csv.html and contains 1034 records with various information from baseball players.

* [mlb_players.csv](mlb_players.csv)

In groups, create pivot tables that can be used to answer the following questions:

1. What is the average height of the players in each position in each team?
2. Which position of which team has the heaviest player? To make it easier to find this information, use **conditional formatting** so that cells are coloured based on their value.

For each pivot table, describe what fields were used in each of the components of the pivot table: "filter", "column", "row", "value", and what parts of the pivot table have each answer.

## 1-3. Pivot charts (5 minutes + 5 minutes discussion)

Use the same CSV file from the previous task.

* [mlb_players.csv](mlb_players.csv)

In groups, create a pivot chart that can be used to answer the following question:

1. What baseball team has the youngest players in average?

For each question, describe what fields were used in each of the components of the pivot table: "filter", "column", "row", "value". Also, justify your choice of chart (line plot? columns? scatterplot? ...) and indicate what part of the chart shows the answer.

# PRAC_02

The following are group exercises. For every group, nominate one person who will explain what you have done. The group exercises will be carried out as zoom breakouts and always the same students will be in the same group. Each time, nominate a different person so that all have the opportunity to practice their presentation skills.

## 2-1. Scatterplots (10 minutes + 10 minutes discussion)

The following CSV file has been downloaded from https://people.sc.fsu.edu/~jburkardt/data/csv/csv.html and contains 1034 records with various information from baseball players.

* [mlb_players.csv](mlb_players.csv)

We want to determine whether there is a relation between the height and the weight of the baseball players. To determine this, in groups, complete the following tasks.

1. Examine the height and weight columns. One of them contains wrong data. Identify and delete the row that contains wrong data (otherwise you can't do step 2).
2. Build a scatterplot that plots the height against the weight of all players.
3. Comment on the scatterplot. Explain whether it shows correlation between the height and the weight.

## 2-2. Correlation using CORREL (5 minutes + 5 minutes discussion)

Use the same CSV file as in the previous task, with the row with wrong data removed. In groups, complete the following tasks:

1. Use the CORREL function to calculate the correlation between the height and the weight.
2. Comment on the value of correlation and compare with what you observed in task 2-1.

## 2-3. Correlation matrix (10 minutes + 10 minutes discussion)

This task requires the use of the Excel Data Analysis pack. To be able to use this pack, the first time you use it you will need to load it. The following link contains instructions for installing the pack in various versions of Excel for Windows and Mac.

* [Load the Analysis ToolPak in Excel](https://support.office.com/en-us/article/load-the-analysis-toolpak-in-excel-6a63e598-cd6d-42e3-9317-6b40ba1a66b4)

Again, use the same Excel file as in the previous tasks. In groups, determine the correlations between height, weight, and age by completing the following tasks:

1. Build the correlation matrix between height, weight, and age.
2. What pair of columns shows the highest correlation?
3. What pair of columns shows the lowest correlation?
4. Confirm the poor correlation between age and height by building a scatterplot between these two columns.
