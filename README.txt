# CSE6242 Final Project
## Team Members
* Like Deng
* Sahil Dhingra
* Shan Huang
* Shuangke Li

## Descriptions
1. [Choropleth](https://sahil-dhingra.github.io/choropleth/):
This is choropleth visualization script in D3. In this visualization, it shows the ratio of average age group's
overall wealth and health. Ideally, we would like the ratio the larger the better. You can use this visualization to determine
each state's wealth vs health condition. Slider can be used to visualize the ratio by states from age 20s to 90s. 

2. [Barplot](https://sahil-dhingra.github.io/barplot/):
In this visualization, we plot the average medical cost, labor income, stock investment, and accumulative wealth grouped by age and health status. The different financial variables can be selected using the dropdown at the top.

3. [Kmeans clusters](https://sahil-dhingra.github.io/kmeans/):
In this visualization, we initialize 5 clusters for the first cohort (survey wave) and plot distribution of relevant health and wealth attributes over the following 12 surveys. The trend and distribution of different attributes can be seen over 13 waves for the 5 clusters, where each cluster is represented by a bubble and the number of people at the time of the survey represented by its size. Another important aspect of this scatterplot visualization is the ability to do a bivariate analysis between any two of the seven variables incorporated in the plot. To keep a track of each cluster's trends, the cluster also leaves behind a trail, which is of a smaller size to maintain differentiability. The survey wave can be selected using the slider at the top and variables for x and y axes can be selected using the first and second dropdowns at the bottom respectively.

4. [Gridview](https://sahil-dhingra.github.io/gridview/):
This figure shows how is the gender related to health and how does the health condition change over time among female and male – each grid is composed of 100 rectangles and each rectangle represents 1\% of population in a specific gender group. The number of light blue rectangles indicates percentages of unhealthy people. The number of dark blue rectangles indicates percentages of healthy population.  

## Installation
Download CODE Folder and there are four sub-folders in CODE. Here are the steps to set up each of them. 
1. choropleth
	Contents:
	lib: this folder includes all necessary D3 related .js files for D3 visualization. 
	states-10m.json: json file defined U.S. map and states line. 
	group_by_state_age_final.csv: processed data .csv file includes all data needed for visualization. 
	choropleth_by_age.html: this file includes all D3 visualization code implementation in javascript. 
	W_H_Age.gif: this file is provided for quick visualization only, no set up needed. 
	
	Set up:
	a) In command window, change the current directory to choropleth. 
	b) Check python version use python -V
	c) If Python version returned is 3.X, use python3 -m http.server
	   If Python version returned is 2.X, use python -m SimpleHTTPSever
	   
2. Barplot
	Contents:
	lib: this folder includes all necessary D3 related .js files for D3 visualization. 
	CSE6242_finalproject_bar.csv: processed data .csv file includes all data needed for visualization. 
	CSE6242_finalproject_bar.html: this file includes D3 visualization code implementation in javascript for the grouped bar plots with dropdown options. The visualization can be found [here](https://sahil-dhingra.github.io/barplot/).
	
	Set up:
	a) In command window, change the current directory to Barplot.
	b) Check python version use python -V
	c) If Python version returned is 3.X, use python3 -m http.server
           If Python version returned is 2.X, use python -m SimpleHTTPSever
	    
3. Kmeans clusters
	Contents:
	lib: this folder includes all necessary D3 related .js files for D3 visualization. 
	cluster_summary.csv: processed data .csv file includes all data needed for visualization - cluster averages for different variables
	kmeans.html: this file includes D3 visualization code implementation in javascript for the kmeans clusters with 2 dropdown options for x and y axis respectively and slider for selecting the survey wave.
	
	Set up:
	a) In command window, change the current directory to Kmeans clusters.
	b) Check python version use python -V
	c) If Python version returned is 3.X, use python3 -m http.server
           If Python version returned is 2.X, use python -m SimpleHTTPSever
	   
4. GridView
	Contents:
	index.html: this file includes D3 visualization code implementation in javascript for the grid views. The visualization can be found [here](https://sahil-dhingra.github.io/gridview/.
	
	Set up:
	a) In command window, change the current directory to GridView.
	b) Check python version use python -V
	c) If Python version returned is 3.X, use python3 -m http.server
           If Python version returned is 2.X, use python -m SimpleHTTPSever
 

## Execution
1. choropleth
	a) Open a web browser, type following URL: localhost:8000
	b) Select choropleth_by_age.html
	c) Slide bar can be used to change the age group
	
2. Barplot
	a) Open a web browser, type following URL: localhost:8000
	b) Select CSE6242_finalproject_bar.html
	c) Dropdown can be used to change the financial variables
	
3. Kmeans clusters
	a) Open a web browser, type following URL: localhost:8000
	b) Select kmeans.html
	c) Dropdown can be used to change the financial variables
	
4. GridView
	a) Open a web browser, type following URL: localhost:8000
	b) Select index.html
	c) Dropdown can be used to change the year variables 
