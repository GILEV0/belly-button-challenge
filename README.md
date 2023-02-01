# belly-button-challenge
Module 14 Challenge

# Belly Button Biodiversity Dashboard

![microbes-sem (1)](https://user-images.githubusercontent.com/112173540/216019398-148d9b0e-9ae9-4aee-b994-630685bc7c96.jpg)

### Deployed website:
https://gilev0.github.io/belly-button-challenge

In this project we built an interactive dashboard to explore the [Belly Button Biodiversity dataset](http://robdunnlab.com/projects/belly-button-biodiversity/). 

## Overview

I used the D3 library to read in `samples.json` then created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual. Then used sample_values` as the values for the bar chart.  Next I used `otu_ids` as the labels for the bar chart and `otu_labels` as the hovertext for the chart. 

`![bar](images/bar.png)

I then created a bubble chart displaying each sample, using `otu_ids` for the x values, `sample_values` for the y values, `sample_values` for the marker size, `otu_ids` for the marker colors, and `otu_labels` for the text values.

![bubble](images/bubble.png)

I displayed the sample metadata (an individual's demographic information), then displayed each key-value pair from the metadata JSON object.

![demoinfo](images/demoinfo.png)

The final result:  

![dashboard](images/dashboard.png)

## Resources used
- Data Source: <a href="https://github.com/GILEV0/belly-button-challenge/samples.json" target="_blank">Bellybutton Samples</a>
- Software: Visual Studio 
- HTML code: <a href="https://github.com/GILEV0/belly-button-challenge/index.html" target="_blank">index.html</a>
- JavaScript code:  <a href="https://github.com/GILEV0/belly-button-challenge/static/js/app.js" target="_blank">app.js</a>
