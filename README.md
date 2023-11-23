# Replication and Review of CoVaR Paper 📊

## Original Paper Summary

* **Title**: CoVaR 
* **Authors**: Tobias Adrian and Markus K. Brunnermeier  
* **Published**: 2016 in American Economic Review
* **Key Points**:
    * Introduced CoVaR as a novel measure of systemic risk contribution.
    * Highlight tail dependence and spillovers between financial institutions.
    * Identified institutions contributing significantly to systemic risk.

## Project Overview 🎯

This project undertakes a comprehensive review and replication of the methodologies proposed in the CoVaR paper. The main objectives are:

* Implement and test methods for computing ΔCoVaR.
* Examine and compare different estimation techniques.
* Analyze model dynamics using empirical data.
* Assess the CoVaR model's ability to measure systemic risk effectively.

## Methodology and Implementation 🛠️

* Focus on a Linear Factor Model for estimation.
* Employ Maximum Likelihood Estimation (MLE) and Quantile Regression methods.
* Analyze weekly returns of S&P 500 stocks.
* Evaluate model performance, convergence, and risk estimation reliability.

## Key Findings and Results 📈

* Quantile Regression emerged as the most reliable method.
* Generated plausible systemic risk estimates.
* Observed notable differences in risk estimates across different sectors.
* Identified limitations in the model's explanatory power.

## Data Sources 📊

The replication project utilized various macroeconomic data, sourced from the following:

1. **S&P 500 Companies List**: Data on S&P 500 companies and sectors, updated as of April 21, 2022, available at [Wikipedia](https://en.wikipedia.org/wiki/List_of_S%26P_500_companies).

2. **DTB3**: Used as the first and second state variables, updated as of April 21, 2022, accessible at [FRED](https://fred.stlouisfed.org/series/DTB3).

3. **DLTBOARD**: Contributing to the second state variable (first period), with the latest update on June 30, 2000, from [FRED](https://fred.stlouisfed.org/series/DLTBOARD).

4. **USTREASURY-LONGTERMRATES**: Part of the second state variable (second period), updated as of January 31, 2022, found at [Nasdaq Data Link](https://data.nasdaq.com/data/USTREASURY/LONGTERMRATES-treasury-long-term-rates).

5. **TEDRATE**: The third state variable, updated as of January 21, 2022, available at [FRED](https://fred.stlouisfed.org/series/TEDRATE).

6. **DBAA**: Serving as the fourth state variable, updated as of April 21, 2022, obtained from [FRED](https://fred.stlouisfed.org/series/DBAA).

7. **DGS10**: Also part of the fourth state variable, with the latest update on April 21, 2022, sourced from [FRED](https://fred.stlouisfed.org/series/DGS10).

## Limitations and Prospects for Future Research 🔍

* Necessity for model refinement to enhance fit and accuracy.
* Exploration of dynamic beta factor models.
* Integration of additional systemic risk measures.
* Extension of the analysis to international financial data sets.

## Conclusion 🌐

This replication and review effort provided valuable insights into the CoVaR model's robustness and applicability in systemic risk measurement. Future research directions have been identified to further enhance the model's effectiveness and applicability in diverse financial contexts.


