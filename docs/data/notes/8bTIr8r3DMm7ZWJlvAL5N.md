
## Exponential Regression

* 90 Day Linear Regression is medium term
* Slope is the dollar amount per day
* R2 measures the fitness of the regression line
* Exponential Slope measures percent per day
* Annualized Slope measures percent per year

### Ranking

* Ranking = R2 * Adjusted Annualized Percent Slope

### Adjusted Slope Formula

* take natural log of quote closing prices
* calc slope of numPeriods log price - this is the ‘exponential slope’ * It represents the percent per day that the stock moves
* annualize the daily percent ```(1 + daily percent)^250``` - this is compounded
* calc R2 - this ranges from 0 to 1
Adjusted slope = annualized percent * R2 - this is the rank values