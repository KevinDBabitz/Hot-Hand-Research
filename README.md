# Hot-Hand-Research

### How to Run on Your Computer
In order to open and run these files, the only required library is pacman which can be downloaded using install.packages("pacman") in R. This will load all other required libraries that may not be on your computer.

### Rmd Files
There are 3 R markdown files in this Repository:
1. Cornell Data Analysis.Rmd - Analysis of Cornell basketball player data from the Gilovich, Vallone, and Tversky (GVT) paper written in 1985 about the Hot Hand. We use permutations and binomial simulations to test for statistical significance of hotness in these players which GVT found to not be hot. 
2. Permutation and Binom Bias.Rmd - Analysis of streaks generated using binomials and permutations. We look at how changing variables like the length of the streaks, the probability of success in generating the streak, and how "bias" is calculated impacts the bias calculation discussed by Miller and Sanjurjo in their 2018 paper which responds to the 1985 GVT paper. 
3. Streak and Bias Analysis.Rmd - Analysis of how using the number of streaks in a sequence can be used to estimate the bias. This analysis is done using both permutations and binomial sequences and also with different streak lengths and probability values.

### Workspaces
There are 3 R markdown files uploaded which all are broken down into different parts of our analysis. Each file has an associated workspace in the Workspaces folder. If this workspace is loaded, the results of the simulations will be the same and the tables and figures will be the same. The code used to generate the data is also included in the files but most of the data is generated randomly and may result in different results than those in the currently generated tables.

Bias Estimation Using Streaks Workspace.RData is created and used in Streak and Bias Analysis.Rmd
Cornell Data Workspace.RData is created and used in Cornell Data Analysis.Rmd
Bias Understanding Workspace.RData is created and used in Permutation and Binom Bias.Rmd

