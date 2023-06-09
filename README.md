# Belly-button-challenge

## Introduction
In this assignment, I built an interactive dashboard to explore the Belly Button Biodiversity dataset from the Public Science Lab (http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)), which catalogs the microbes that colonize human navels.
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare , and also reveals that  belly buttons are indeed a jungle of microbial diversity, having detected over 2300 species in a sample of 60 navels.

## Challenge overview
In this challenge I  worked with a `index.html`, `samples.json`, and a static folder that contains the `app.js` with the instructions to use the ´D3´ library to read in  `samples.json` from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json (samples.json). I had to adecuate a little bit the order of the folders because I was strugling wiht a no file found error, so I leave the static folder, the index. html and samples.json in the same folder called data. I faced the error CORS which I solved with the `Live Server` extension.

## Plotly

1. Use the D3 library to read in `samples.json`.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

* Use `sample_values` as the values for the bar chart.

* Use `otu_ids` as the labels for the bar chart.

* Use `otu_labels` as the hovertext for the chart.

CHALLENGE COMPLETE!!

  ![bar Chart](Starter_Code/StarterCode/data/static/Images/hw01.png)

3.Create a bubble chart that displays each sample.

* Use otu_ids for the x values.

* Use sample_values for the y values.

* Use sample_values for the marker size.

* Use otu_ids for the marker colors.

* Use otu_labels for the text values.

 ![buble Chart](Starter_Code/StarterCode/data/static/Images/bubble_chart.png)
 
4.Display the metadata individual's demographic information.

5.Display each key-value pair from the metadata JSON object somewhere on the page.

 ![demo info](Starter_Code/StarterCode/data/static/Images/hw03.png)
 
 6.Gauge Chart
 
* I adapted the Gauge Chart from <https://plot.ly/javascript/gauge-charts/> to plot the weekly washing frequency of the individual.

* Then, I modified the example gauge code to account for values ranging from 0 through 9

 ![Guage Chart](Starter_Code/StarterCode/data/static/Images/gauge.png)

## Final Dashboard 
![Guage Chart](Starter_Code/StarterCode/data/static/Images/Finaldashboard.png)


## Tools and sources

* Plot.ly
* Javascript
* HTML
* D3.js
* JSON
* GitHub 




# References
Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/Links to an external site.
