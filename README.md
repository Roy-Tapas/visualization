# Visual analysis of evolution of real estate markets of San Francisco from 2010 to 2016
---

This repository contains iplementation of both basic and advanced interactive visulations of historical prices of house units, sale price per square foot and gross rents in Sanfrancisco, California from 2010 to 2016. 

Above implementation is done through two python notebooks:
* rental_analysis.ipynb - implements number of static and interactive graphs, presenting the trend and evolution of real estate market of San Francisco. 
* dashboard.ipynb - arranges and consolidates the visual analysis in a dashboard with 4 tabs - with each tab holding similar visuals presenting part of the visual story.  


Following visualization libs/packages have been used: <br>
* Pandas visualization
* Matplotlib
* Panel
* Panel interact 
* plotly
* hvplot
* MAPBOX API is used to draw the scatter plot on the San Francisco map

## How to run the script <br>
Clone the entire "visualization" repository into a local folder by issuing the following command from gitbash <br>
```
$git clone https://github.com/Roy-Tapas/visualization.git
```
Stay in the same gitbash directory and open Jupyter lab by issuing the following command from gitbash: <br>
```
$Jupyter lab
```
Create a .env file and enter your API keys for the following:
* MAPBOX_API_KEY = "enter your key here"
* In case you don't have MAPBOX_API_KEY, you need to signup to MAPBOX to get the API key.

open rental_analysis.ipynb and dashboard.ipynb in jupyter notebook and run each cells one after another.


## Important points to note 
Retain the folder structure as cloned from github.  
Hierarchy inside financial-planner should look like the following:
```
visualization 
        |---------------> README.md 
        |---------------> rental_analysis.ipynb 
        |---------------> dashboard.ipynb 
        |---------------> .env
        |---------------> Data
                            |---------> sfo_neighborhoods_census_data.csv
                            |---------> neighborhoods_coordinates.csv
```



<hr style="border:2px solid blue"> </hr>

## Tapas Roy

**Email:** rtapask@gmail.com