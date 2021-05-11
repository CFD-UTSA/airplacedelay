# Final-Project Airplane delay in American
Link for the data set https://www.transtats.bts.gov/OT_Delay/OT_DelayCause1.asp.
However, it need to select period by yourself and decompressing from zip code.
# Data background
This project is trying to using surface station plot, histogram plot and line plot to analysis the airplane delay in American in the past 5 years.

The shape of the data is (87860,22). The column shows the reason of delay, the airport, airline company, and the location of the airport. The row shows the number of each airline company delay at each month and airport for each reason.

A list of python libraries is showing below:
i.	Numpy – This package is using for support large matrices calculation.
ii.	Pandas -This package is using for data analysis in this project.
iii.	Matplotlib – This package is using for line plot, histogram plot, pie plot in this project.
iv.	Metpy -This package is using for surface plot and interpolation plot in this project.



# Goal of the project
The goal of the project is to give a direct viewing of fight delays in American.

# For the python coding:
The first part is import data and extract data from excel and prepare.
The second part is pull out the necessary data and regroup them for plotting
The third part is finding the best way to plot the prepared data.

# The new modules:
The new modules is metpy. Base on the map given by metpy, i make a sufrface station plot base on the location of the airplot.


# Expect from the project
1, Plot each airplort direct on the map.

2, Histograme show the number of delay classify by airplane company.

3, Line plot show the trace of number of delay change by years and month.

4,Have a direct view of airplane delay situation in American.


# Reference
https://unidata.github.io/MetPy/latest/examples/index.html
