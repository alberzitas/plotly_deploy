# Plotly Deploy

## Website

Interactive website for belly button biodiversity can be found here:
https://alberzitas.github.io/plotly_deploy/

## Purpose and Overview

Rosa needs to discover and document bacteria species that can synthesize protein that tastes like beef. Rosa has sampled bacteria from people everywhere by ID. To complete this project, she needs to be able to visualize the data for each volunteer. To accomplish this, we used JavaScript to display the sample data into  interactive bar, bubble, and gauge graphs. To do this, we had to utilize several JavaScript functions such as array.map(), filter(), and slice() to sort through and display the appropriate data. Additionally, because the sample data existed in json format, we had to use the d3.json library to visualize it with plotly.

## Analysis

Getting the page to display each graph correctly involved making sure that every variable was properly defined. Additionally, CORS errors had to be bypassed by running a static server on the terminal. In the end, the resulting graphs were interactive and responded to changes in the dropdown menu accordingly. Hovering the cursor above each bar or bubble brought up further information about the sample from the json file.

A screenshot of the completed page:
![](webpage.png)
