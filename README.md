# World Bank Data Visualization Tutorial
by Sino Oulad Daoud
Created as a synthesis of the data science topics and methods covered in COGS 108 @ UCSD

### A data science tutoral dealing with country fertility rate and male/female literacy rate data

This notebook will go over using Python data science/visualization libraries like pandas and folium to work with and visualize indicator data from <a href='https://www.kaggle.com/worldbank/world-development-indicators'>this</a> collection of <a href = 'https://data.worldbank.org/'>World Bank</a> data on Kaggle.

<a href='https://medium.com/datadriveninvestor/visualising-geospatial-data-with-python-d3b1c519f31'>This</a> article inspired my own notebook, uses the same dataset, and goes over using folium nicely, though the folium library has since changed. In particular, one now needs to implement the Choropleth folium map layer object differently--the current correct implementation is used in this notebook. I also go over ways to visualize the data apart from using folium's map.

### Prerequisites for this notebook
Basic Python knowledge, with the required modules (see below) and Python 3.6+ installed. Ideally, some experience with pandas and matplotlib, since I won't be going over the mechanics of working with pandas DataFrames or the pyplots, and these structures can be finicky if one is unfamiliar with these libraries; but the data in this tutorial is relatively tidy and easy to work with, so extensive knowledge on these topics is not necessary.


The following modules/libraries are needed for working with the Indicators dataset as shown in this notebook:

Numpy

Pandas

Matplotlib

Folium
