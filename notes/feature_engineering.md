# Feature Engineering
_EDA_ - Exploratory Data Analysis
- plot data into a visual representation
- In reality its a lot more about the data cleaning, etc.
- Variance is the square of standard deviation. Why is variance necessary? Why can't we just use standard deviation? It is because it treats the negative differences as positives so they dont cancel out.
- IID
- multicolinearity - if there are columns that correlate with each other -> need to be independent because then the model will overvalue that feature.

Correlation
- use the linear coeff formula and find correlation between every feature and then plot it as a heat map.
- can check for multicolinearity

Transforming Dates
- number from the earliest date
- split into month, date, year

PCA = Principal Component Analysis
- turn high dimensions into lower ones
Figure out PCA and SVD and Kernel PCA