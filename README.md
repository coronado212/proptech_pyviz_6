# PropTech - San Francisco Housing Market

![](Images/sf_housing.png)

PropTech is an innovative approach to real estate in which technology optimizes the way people research, rent, buy, sell, and manage a property.

You've recently been hired at a PropTech company, that's seeking to offer an instant, one-click service for people to buy properties and rent them. 
The company would like to start with a trial offering in the San Francisco real-estate market. If the service proves popular, they can then expand to other markets.

Your job is to combine your data aggregation, interactive visualization, and geospatial analysis skills to find properties in the San Francisco market that are viable investment opportunities.


---

## Technologies

This project leverages python 3.7 with the following packages:

* [Pyviz](https://pyviz.org/) - Python visualization package that provides a single platform for accessing multiple visualization libraries. Two of these libraries are Plotly Express and hvPlot, which you’ll use during this module.


* [The Mapbox API](https://account.mapbox.com/auth/signup/) - To use the Mapbox API, you need to register for a public Mapbox API access token.


---

## Installation Guide

To install PyViz and its dependencies in your Conda dev environment, complete the following steps:

From your terminal, log in to your Conda dev environment.

Install the PyViz packages by using the conda install command as follows:
    
	conda install -c plotly plotly=4.13.
    conda install -c pyviz hvplot


---

## Usage


The main challenge here is to visualize and analyze the real-estate data in your Jupyter notebook. Use the san_francisco_housing.ipynb notebook to complete the following tasks:

1) Calculate and plot the housing units per year.

Use numerical and visual aggregation to calculate the number of housing units per year, and then visualize the results as a bar chart.

![](Images/zoomed-housing-units-by-year.png)

2) Calculate and plot the average prices per square foot.

Use numerical and visual aggregation to calculate the average prices per square foot, and then visualize the results. 

![](Images/avg-sale-px-sq-foot-gross-rent.png)

3) Compare the average prices by neighborhood.

Use interactive visualizations and widgets to explore the average sale price per square foot by neighborhood.

![](Images/pricing-info-by-neighborhood.png)

4) Build an interactive neighborhood map.

Explore the geospatial relationships in the data by using interactive visualizations with Plotly and the Mapbox API.

![](Images/mapbox-plot.png)

5) Compose your data story. 

How does the trend in rental income growth compare to the trend in sales prices? Does this same trend hold true for all the neighborhoods across San Francisco?

What insights can you share with your company about the potential one-click, buy-and-rent strategy that they're pursuing? Do neighborhoods exist that you would suggest for investment, and why?

---

## Contributors

Brought to you by Edgar Coronado

---

## License

MIT