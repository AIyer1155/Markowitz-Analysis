# How Correlation Breaks the Optimal Portfolio

A research paper analyzing the sensitivity of Markowitz mean-variance 
portfolio optimization to estimation error in the covariance matrix.

## Summary
Derives the global minimum-variance portfolio for n assets via Lagrange 
multipliers, then demonstrates using data that weight sensitivity scales are
nearly proportionally with the condition number of the covariance matrix. 
Two case studies: a weakly-correlated (AAPL, KO, JPM, κ ≈ 2.50) and a 
highly-correlated bank portfolio (JPM, BAC, WFC, κ ≈ 13.88), showing 
roughly a five-fold increase in fragility.
