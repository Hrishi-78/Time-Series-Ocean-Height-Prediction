# Time-Series-Ocean-Height-Prediction

The problem statement for the ML competition is to develop a model that can accurately predict
significant wave height using oceanographic data collected by the National Data Buoy Center
(NDBC). The participants will be provided with a dataset containing various oceanographic
variables. Their task is to build a machine learning algorithm to predict the significant wave
height based on these variables. The goal is to create a model that accurately predicts
significant wave height, an essential parameter for marine safety and ocean engineering
applications.

1. Files
train.csv - the training set
test.csv - the test set
sample.csv - a sample submission file in the correct format

2. Columns
ID - Unique timestamp recorded by Buoy
#YY - Year
MM - Month
DD - Date
hh - Hour
mm - Minutes
WDIR(degT) - Wind Direction
WSPD(m/s) - Wind Speed
GST(m/s) - Gust speed
DPD(sec) - Dominant Wave period
APD(sec) - Average Wave period
MWD(degT) - Mean Wind Direction
PRES(hPa) - Pressure
ATMP(degC) - Atmosphere temperature
WTMP(degC) - Water temperature
DEWP(degC) - Dew Point
WVHT(m) - Significant Wave Height
