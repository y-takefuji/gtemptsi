# gtemptsi

gtemptsi is a PyPI application for visualizing four lines of global surface temperature and total solar irradiance, and their linear-regression lines with R-squared, slope and intercept, and p-value.

NOAA started total solar irradiance (TSI) measurement from 1978. 
The global surface temperature and TSI are publicly available at the NOAA sites. gtemptsi download datasets automatically and save them as tsi.csv (TSI dataset) and noaa.csv (global surface temperature dataset).

# How to install gtemptsi

$ pip install gtemptsi

# How to run gtemptsi
<pre>
$ gtemptsi
Enter the beginning year-month (e.g. 1978-11): 1996-06
Enter the end year-month (e.g. 2023-03): 1998-12
</pre>
<img src='https://github.com/y-takefuji/gtemptsi/raw/main/199606_199812.png' width=640 height=480>

