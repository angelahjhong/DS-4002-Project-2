## **Past Trends and Future Predictions of U.S. Mortgage Rates**
**DS 4002 Project 2 Group 5**

## Software and Platform 
All code used the [Python](https://www.python.org/downloads/) language on a virtual machine in [Google Colab](https://colab.research.google.com/) 

**Packages Used:**
* EDA & Visualization: [pandas](https://pypi.org/project/pandas/), [matplotlib](https://pypi.org/project/matplotlib/), and [seaborn](https://pypi.org/project/seaborn/) 
* Analysis: [SARIMA Model](https://www.geeksforgeeks.org/sarima-seasonal-autoregressive-integrated-moving-average/), [Mean Square Error](https://scikit-learn.org/1.5/modules/generated/sklearn.metrics.mean_squared_error.html), [Exponential Smoothing](https://www.statsmodels.org/dev/generated/statsmodels.tsa.holtwinters.ExponentialSmoothing.html), [numpy](https://numpy.org/doc/stable/user/absolute_beginners.html), [statsmodel](https://www.statsmodels.org/stable/index.html), [pmdarima](https://pypi.org/project/pmdarima/), [Scikit-learn](https://docs.scipy.org/doc/scipy/reference/stats.html), [SciPy](https://docs.scipy.org/doc/scipy/reference/stats.html)
* These links are provided for python package documentations  
  
## Documentation 
Our data was pulled from [Freddie Mac](https://www.freddiemac.com/pmms) in the form of an excel - accessible in our DATA folder
* **SCRIPTS folder:** contains "TimeSeries_CleaningEDA.ipynb" which includes the data cleaning and EDA, as well as "TimeSeries_Analysis.ipynb" which includes the SARIMA forecasting and the statistical tests. 
* **DATA folder:** contains "TimeSeries_CleaningEDA.ipynb" which includes data cleaning and intial EDA, "historicalweeklydata.xlsx" which is the uncleaned excel file, and "cleaned_df.csv" which includes the new transformed cleaned dataset in a cvs format. "DataAppenix.pdf" stores our data, figures, and other descriptive statistics.
* **OUTPUTS folder:** "ResultsAppendix.pdf" which stores the visualized figures and statistical analysis computed from our analysis. 

## How to Reproduce Results 
**To reproduce these results:**
* First follow to instructions to download the data - located in our DATA folder under "TimeSeries_CleaningEDA.ipynb"
* Run the file titled "TimeSeries_CleaningEDA.ipynb" - located in our DATA or SCRIPTS folder, to view how to go from the raw to clean data and view our EDA 
* Run the file titled  "TimeSeries_Analysis.ipynb" - located in our SCRIPTS folder, to view our forecasting and statistical analysis
* The PDF files titled "DataAppendix.pdf" and "ResultsAppendix.pdf" in the DATA and OUTPUTS folder, respectively, containing all figures run from our analysis

## References
[1] Freddie Mac. “Mortgage Rates Tick Up.” Freddie Mac. https://www.freddiemac.com/pmms (accessed October 7, 2024). 

[2] S. Shawl. “Python | ARIMA Model for Time Series Forecasting.” GeekforGeeks. https://www.geeksforgeeks.org/python-arima-model-for-time-series-forecasting/ (accessed October 7, 2024). 

[3] T. Mutha. “Time Series forecasting using SARIMA in Python”. Medium. https://medium.com/@tirthamutha/time-series-forecasting-using-sarima-in-python-8b75cd3366f2 (accessed October 21, 2024)
  
