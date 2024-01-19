# Holdings-of-Federal-Government-s-Domestic-Debt-Outstanding-Billion



### Project Overview 
Data Analysis Project Overview - Time series Analysis of Central Bank of nigeria(CBN) Holdings of Federal Government's Domestic Debt Outstanding in Billions


### Introduction:
The Data Analysis Project focuses on delivering valuable insights into the Holdings of Federal Government's Domestic Debt Outstanding in Billion. By leveraging advanced forecasting techniques, the project aims to uncover future trends, enabling data-driven decision-making, and fostering a comprehensive understanding of the dynamics surrounding the Federal Government's Domestic Debt.

![CBN BANK](https://github.com/OlamilekanKolawole/OlamilekanKolawole-Holdings-of-Federal-Government-s-Domestic-Debt-Outstanding-Billion/blob/main/Central-Bank-of-Nigeria.png)


### Data Source 
Central Bank of nigeria(CBN): The primary Dataset used for this analysis was extracted from "2021 statistics bulletin_public finance" .xlsx File, found in the Excel sheet (B1.5) Table B1.5: containing detailed information about Holdings of Federal Governments Domestic Debt Outstanding Billion.

### Tools

- Excel - Data Cleaning [Download Here](https://microsoft.com)
- Gretl - Time Series Analysis [Download Here](https://sourceforge.net/projects/gretl/)


### Data Cleaning and Preparation 
In the initial data preparation phase, we performed the following Tasks 
1. Data Loading and inspection.
2. Data cleaning and formatting.

### Exploratory Data Analysis (EDA)

Initially, I obtained the time series plot depicted in the graph below.

![CBN BANK](https://github.com/OlamilekanKolawole/OlamilekanKolawole-Holdings-of-Federal-Government-s-Domestic-Debt-Outstanding-Billion/blob/main/FIRSGT%20CBN%20GRAPH%20CHECK.JPG)

Step 2: I discovered the Augmented Dickey-Fuller (ADF) test.

![CBN BANK](https://github.com/OlamilekanKolawole/OlamilekanKolawole-Holdings-of-Federal-Government-s-Domestic-Debt-Outstanding-Billion/blob/main/ADF%20Test%20for%20CBN.JPG)

Observation: After scrutinizing the results of the Augmented Dickey-Fuller (ADF) test, it is evident that the p-value suggests non-stationarity. Consequently, the next step involves obtaining the natural logarithm and the first difference of the logarithm.

![CBN BANK](https://github.com/OlamilekanKolawole/OlamilekanKolawole-Holdings-of-Federal-Government-s-Domestic-Debt-Outstanding-Billion/blob/main/PVALUE%20STATIONARY.JPG)

Following the Augmented Dickey-Fuller (ADF) test for the initial difference of the logarithm, the p-value now indicates stationarity

#### Forecasting Models: Begin the data modeling process by first assessing the correlogram, and the obtained result is as follows;

![CBN BANK](https://github.com/OlamilekanKolawole/OlamilekanKolawole-Holdings-of-Federal-Government-s-Domestic-Debt-Outstanding-Billion/blob/main/CORRELELOGRAM%20LAG.JPG)

Presently, employing ARIMA with autoregressive (AR) and moving average (MA) parameters set at 2 each,After careful consideration, we arrived at this outcome, utilizing the initial difference of the logarithm as the dependent variable.

![CBN BANK](https://github.com/OlamilekanKolawole/OlamilekanKolawole-Holdings-of-Federal-Government-s-Domestic-Debt-Outstanding-Billion/blob/main/MODEL%20ON%20ARMA%20202.JPG)

The Akaike Information Criterion (AIC) serves as a metric for assessing the goodness of fit in a model, striking a balance between model complexity and its alignment with the data. In model comparisons, a lower AIC signifies a superior trade-off between fit and complexity. Consequently, this model with the lowest AIC is typically favored.

When fitting ARIMA models to time series data, the emphasis is placed on selecting the model with the lowest AIC. This approach ensures the identification of the most parsimonious model, one that effectively captures underlying patterns in the data without unnecessary complexity.

####  Residual plot against CBN domestic Debt 

![CBN BANK](https://github.com/OlamilekanKolawole/OlamilekanKolawole-Holdings-of-Federal-Government-s-Domestic-Debt-Outstanding-Billion/blob/main/GRAPH%20RESIDUAL%20PLOT%20AGAINST%20CBN.JPG)

#### Residual plot against Time
![CBN BANK](https://github.com/OlamilekanKolawole/OlamilekanKolawole-Holdings-of-Federal-Government-s-Domestic-Debt-Outstanding-Billion/blob/main/RESIDUAL%20PLOT%20AGAINST%20TIME.JPG)

###### The conclusive methodology involves a ten-year forecast spanning from 2022 to 2031 for the Central Bank of Nigeria (CBN) Holdings of Federal Government's Domestic Debt Outstanding in billions, with the results outlined below.

![CBN BANK](https://github.com/OlamilekanKolawole/OlamilekanKolawole-Holdings-of-Federal-Government-s-Domestic-Debt-Outstanding-Billion/blob/main/10YEARS%20CBN%20FORECAST%202022%20-%202031.png)















