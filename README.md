# An-Analysis-of-Financial-Performance-Indicators-in-Bankruptcy-Prediction-with-Machine-Learning
In the first and second quarters of 2023, the banking industry experienced a wave of uncertainty due to the crisis of large banks such as Silicon Valley Bank and Credit Suisse. There is significant systemic risk amongst large banks in the financial sector and consequently, has a domino effect on entities exposed to this risk; in a worst-case scenario, 
this may result in devastating bank runs that could be a severe detriment to the global economy. To mitigate some of this risk, banks are mandated, by the Bassel regulations, to allocate capital proportional to the risk due to their lending activities; this is known as Economic Capital.  When a large company or several smaller companies declares bankruptcy due to solvency issues, this critically impacts a bank's ability to continue its lending activities. 
Thus, an effective predictive model for defaults would allow banks to allocate capital properly for these worst cases events and also make more informed lending decisions. As such, our goal was to produce a model that accurately predicts whether a client defaults based on their financials.   

This analysis was conducted using data from the Taiwan Economic Journal over a period of 20 years (1999 -2009) \cite{Data}. In this data set, bankruptcy was defined according to Taiwan Stock Exchange business regulations. 
The data set includes 220 cases that resulted in company bankruptcies and 6599 non-bankruptcy cases, so a clear class imbalance exists in the dataset. In addition to the bankruptcy indicator, 95 other features were recorded, comprising company financials,

One of the most peculiar insights from this analysis is how certain models are inherently superior performers for a certain set of problems. 
However, it invokes an endeavor to improve the performance of weaker performing models on certain problems.
Here we consider ways of improving predictive performance when a large class imbalance exhists in the data. 
