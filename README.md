# Random-forest-to-predict-the-macroeconomics-scenario-to-buy-stocks-of-retail-sector
A model based in random forest to predict buy and sell stocks of retail sector.

Random forest is a commonly-used machine learning algorithm trademarked by Leo Breiman and Adele Cutler, which combines the output of multiple decision trees to reach a single result. Its ease of use and flexibility have fueled its adoption, as it handles both classification and regression problems.

The retail sector consists of all companies that sell goods and services to consumers and macroeconomic scenarios are multi-year projections of economic variables. The retail sector is sensitive to macroeconomic variations, especially when there are low gross domestic product (GDP) projections, high interest rates and high inflation rates.

Therefore, the aim of this study was to establish a model using random forest to predict the macroeconomics scenario to buy or sell stocks of retail sector.

MACROECONOMIC INDICATORS AND RETAIL STOCKS

Lojas Renner (LREN3) was chosen to be a representative stock of the retail sector of companies traded on B3 (brazilian stock exchange). The indices Broad National Consumer Price Index (IPCA), Special System for Settlement and Custody (selic), Central Bank Economic Activity Index (IBC-Br), Broad Retail Trade Confidence Index (ICOM), Future Expectations Index, Dollar (exchange), Consumer Stock Index (ICON) and Ibovespa Index (IBOV) were initially analysed by correlation. Data from during 10 years were used (2011-2021). 

Dataset Source: https://figshare.com/articles/dataset/Macroeconomic_indices_used_in_predictive_model_for_retail_sector_in_Brazil/22674859 

STOCK TREND

The trend of the stock was considered only bullish or bearish (binary classification). When the trend was sideway and followed by a uptrend, the trend was considered uptrend because it would be a good opportunite to buy. This same reasoning was used when there was a lateralization followed by a bearish trend.

CONCLUSIONS

Three models were generated using different indicators. 

![![Table 1 - random forest metrics](https://user-images.githubusercontent.com/78765404/233862335-76d0d15e-a34b-4dd1-a4e1-60f3454323a7.png)]
