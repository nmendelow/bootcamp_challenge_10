# crypto_investments
This jupyter notebook will use unsupervised machine learning to find novel ways of aggregating cryptocurrencies to achieve better relative performance


---

## Technologies

This program/notebook should be viewed in jupyter lab, and the following libraries were used:
Pandas,
hvplot,
pathlib,
sklearn

---

## Installation Guide

n/a

---

# Usage

This notebook is static from a data input persepctive. All data is read in from archived .csv files located in the "reasources" folder.

------

![toolbar](Images/hvplot_navigator.png?raw=True)

The graphs displayed are dynamic. They utilize hvplot which allows the user to manipulate the disply by accessing the toolbar found on the right side of the graph.

------------

![Bokeh](Images/hvplot_navigator_documentation_link.png?raw=True)

The top button will bring you to the Bokeh Visualization Library homepage.

-----------

![pan](Images/hvplot_navigator_pan.png?raw=True)

The next button will allow you to grab and move the chart if you left click and hold.

--------

![zoom](Images/hvplot_navigator_zoom.png?raw=True)

The magnifying glass allows the user to zoom in to a particular portion of the chart for a closer look by left clicking and draging a box around the relevant data.

--------

![wheel](Images/hvplot_navigator_wheel_zoom.png?raw=True)

The magnifying glass next to the image of the mouse wheel will enable you to zoom in and out with your mouse wheel if selected.

-------

![save](Images/hvplot_navigator_save.png?raw=True)

The disk button will allow you to save a copy of the chart to your computer.

--------

![reset](Images/hvplot_navigator_reset.png?raw=True)

This button will reset the chart to it's default display.

---------

![hover](Images/hvplot_navigator_hover.png?raw=True)

The final button will toggle the hover information on/off. Selecting this will allow you to see more information as you hover your mouse over the chart.

----------

![elbow](Images/elbow.png?raw=True)

This plot is used to determine the "best" value for "k" which is the number of groupings that will be used to run the K-Means analysis. The k value at the bend in the curve represents the optimal balance of reduction in inertia vs. the simplicity in analyzed factors.

----------

![scatter](Images/scatter.png?raw=True)

This plot shows the data for each cryptocurrency plotted against the 1 day and 7 day returns. The colored grouping of the data points is determined using the KMeans algorithm

---------

After performing the analysis on the original data, we use Principal Componant Analysis (PCA) to further group the cryptocurrencies. In this analysis PCA allowed us to keep almost 90% of the explained varience while dropping the factors considered from 7 to a more manageable 3.

![compare](Images/scatter_compare.png?raw=True)

By using the PCA analysis, we get tigher/more defined groupings of our data.




---

## Contributors

Neil Mendelow - https://www.linkedin.com/in/neil-mendelow/

---

## License

This code is covered by the MIT license.

