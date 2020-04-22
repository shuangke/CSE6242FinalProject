# CSE6242FinalProject
## Team Member
* Like Deng
* Sahil Dhingra
* Shan Huang
* Shuangke Li
## Description
Choropleth: this is choropleth visualization script in D3. In this visualization, it shows the ratio of average age group's
overall wealth and health. Ideally, we would like the ratio the larger the better. You can use this visualization to determine
each state's wealth vs health condition. Slider can be used to visualize the ratio by states from age 20s to 90s. 
## Installation
Download CODE Folder and there are sub-folders in CODE, here are the steps to set up each of them. 
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
 

## Execution
1. choropleth
	a) Open a web browser, type following URL: localhost:8000
	b) Select choropleth_by_age.html
	c) Slide bar can be used to change the age group
