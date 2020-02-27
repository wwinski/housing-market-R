# Housing Market Analysis in R

Inspired by a class assignment, this project focuses on the analysis of housing market data using R.  
  
Data taken from [Kaggle](https://www.kaggle.com/anthonypino/melbourne-housing-market).

---

**Phase 1**  
The first phase of this project is to do simple analysis of the data. The purpose of this analysis is to identify when the market turned and to determine what features can be used to predict price. Following the analysis comes the creation of linear regression models for before and after the market downturn.

- [R Notebook (HTML)](https://github.com/wwinski/housing-market-R/blob/master/Housing%20Linear%20Regression%20Notebook.html)
- [R Notebook (Code)](https://github.com/wwinski/housing-market-R/blob/master/Housing%20Linear%20Regression.Rmd)

---

**Phase 2**  
*In Progress*  
The goal of the second phase is to iterate on the analysis from Phase 1 to generate a more accurate model using Keras Neural Networks. The output of this model has yet to be decided, either predictions for price of individual properties or predictions of mean/median price for a given time period. Ideally, with the more complex model, I will be able to achieve accuracy greater than 85%.

---

**Phase 3**  
*Still in conceptual stage, until Phase 2 is complete.*  
The goal for Phase 3 will be to build a model on top of the one trained in Phase 2 such that it can predict when the market is turning. The Phase 2 model will output a prediction and based on the accuracy of these predictions over time the Phase 3 model should be able to identify when the market turns.