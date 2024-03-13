# Statistical Models: Theory and Application @ UCB

- My assignments and projects of Statistical Models: Theory and Application (STAT215B) in Department of Statistics @ University of California, Berkeley.
- Instructor: @ Jon McAuliffe
- Language: R



> Some of the assignments were modified after submitted because I realized something wrong as I learnt more and more about the statistical topics. 
>
> Please find the new version of the report in "assignmentx-report-new.pdf".



## Quick Review of Assignments

- [1. Assignment 1](#1)
- [2. Assignment 2](#2)
- [3. Assignment 3](#3)
- [4. Assignment 4](#4)
- [5. Assignment 5](#5)



<h3 id="1">Assignment 1. EDA and Hypothesis Tests</h3>

- The main job in this assignment is to investigate the connection between maternal smoking and infant health <a href="https://link.springer.com/book/10.1007/b98875">[Deborah Nolan, 2000]</a> and is conducted mainly following the guideline in the instruction document. 
- Dataset: Child Health and Development Studies (CHDS).
- Deadline: 17:00 January 22nd, 2024.
- Updates in the new version: 
  - Section 3.1: I give more details in the step-by-step construction of univariate comparision.
  - Section 3.2: I add a multi-panel boxplot to make the univariate comparison more explicit.
  - Section 3.4: I add a new disadvantage for multiple regression regarding the variance assumption.
- Remarks: For two-sample tests where we want to compare the means based on a large-sample dataset, it's better to use the t-test than the Wilcoxon rank sum test because the null hypothesis $H_0$​ for Wilcoxon rank sum test is that the whole distribution of the two samples are the same (including mean, median, variance, etc.). Besides, though the t-test requires normal assumption, the large sample size can ensure the validity and power of t-test.



<h3 id="2">Assignment 2. Survival Analysis</h3>

- The main job in this assignment is to develop deep insights of survival analysis using mathematical calculations and simulation studies.
- Deadline: 17:00 January 30th, 2024.
- Updates in the new version: 
  - Section 1.2: I correct a typo regarding the explanation of Weibull model, where $\beta < 1$ should imply a monotone decreasing hazard function.
  - Section 2.3: I add some remarks on the case of administrative censoring and explain why the time span of the survival curves is not exactly $[0,5]$.
  - Section 2.4: I add one sentence to introduce the new censoring pattern (a combination of administrative censoring and random censoring).



<h3 id="3">Assignment 3. Randomness in Randomization Studies</h3>

- The main job in this assignment is to carry out an analysis of the Dade County experimental data that is justified by the randomization <a href="https://www.jstor.org/stable/2095922">[Pate and Hamilton, 1992]</a>.
- Dataset: <a href="https://www.icpsr.umich.edu/web/NACJD/studies/6008/versions/V1">Randomized Treatments Data for Spouse Abuse Replication Project in Metro-Dade County, Florida, 1987-1989.</a>
- Deadline: 17:00 February 6th, 2024.
- No updates so far.



<h3 id="4">Assignment 4. OLS v.s. IVLS</h3>

- The main job in this assignment is to study the performance of OLS and IVLS coefficient estimators, as well as two different estimators of the error variance using simulation.
- Deadline: 17:00 February 19th, 2024.
- Updates in the new version: 
  - Section 2.1: I correct a typo, where I forget to put a "hat" on $\beta_{OLS}$ and $\beta_{IVLS}$.
  - Section 2.2: I correct a typo, where the GLS should be the Generalized Least Squares instead of Generalized Method of Moments (GMM).
  - Section 2.3: I modify the properties I previously stated for $\hat\beta_{IVLS}$ — it should be biased but consistent rather than unbiased. Then I give the proofs for the biasness and inconsistency of $\hat \beta_{OLS}$ and the proofs for the biasness and consistency of $\hat \beta_{IVLS}$.



<h3 id="5">Assignment 5. Empirical Bayes and Shrinkage</h3>

- The main job in this assignment is to gain deep insights of James-Stein estimation and empirical Bayes.
- Deadline: 17:00 February 28th, 2024.
- Updates in the new version: 
  - Section 1.3 (Exercise 1.4): I correct the proof. My previous proof is not correct because I forgot that $S$ refers to the sum of squares $||\boldsymbol z||^2=\sum_iz_i^2$, containing $z_i$ as well, and thus I failed to compute the derivative $\partial \hat \mu_i^\text{(JS)}/\partial z_i$ correctly.

