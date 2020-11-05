# Getting Rid of Dichotomous Sex Estimations: Why Logistic Regression Should be Preferred Over Discriminant Function Analysis
A repository for [Bartholdy et al. 2020](https://onlinelibrary.wiley.com/doi/epdf/10.1111/1556-4029.14482)

## Here you will find:

- The data used for the publication
- The publication itself (open-access)
- The RScript used for the statistics
- How to cite
- Abstract
<!-- - Non-specialist summary -->
<!-- - A reproducible .Rmd file of the publication and a rendered .pdf file -->
<!-- - Binder environment mybinder.org -->

## How to cite

>Bartholdy, B.P., Sandoval, E., Hoogland, M.L.P. and Schrader, S.A. (2020), Getting Rid of Dichotomous Sex Estimations: Why Logistic Regression Should be Preferred Over Discriminant Function Analysis. J Forensic Sci, 65: 1685-1691. doi:10.1111/1556-4029.14482

## Abstract

Sex estimation is an important part of creating a biological profile for skeletal remains in forensics. The commonly used methods for developing sex estimation equations are discriminant function analysis (DFA) and logistic regression (LogR). LogR equations provide a probability of the predicted sex, while DFA relies on cutoff points to segregate males and females, resulting in a rigid dichotomization of the sexes. This is problematic because sexual dimorphism exists along a continuum and there can be considerable overlap in trait expression between the sexes. In this study, we used humeral measurements to compare the performance of DFA and LogR and found them to be very similar under multiple conditions. The overall cross-validated (leave-one-out) accuracy of DFA (75.76--95.14%) was slightly higher than LogR (75.76–-93.82%) for simple and multiple variable equations, and also performed better under varying sample sizes (94.03% vs. 93.78%). Three of five DFA equations outperformed LogR under the B index, while all five LogR equations outperformed the DFA equations under the Q index. Both methods saw an improvement in overall accuracy (DFA 86.74--95.79%; LogR 86.74--95.76%) when individuals with a classification probability lower than 0.80 were excluded. Additionally, we propose a method for calculating additional cutoff points (PMarks) based on posterior probability values. In conclusion, we recommend using LogR over DFA due to the increased flexibility, robusticity, and benefits for future users of the statistical models; however, if DFA is preferred, use of the proposed PMarks facilitates future analysis while avoiding unnecessary dichotomization.
