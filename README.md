# Belly Button Biodiversity

In this assignment, I built an interactive dashboard to explore the [Belly Button Biodiversity in my Github Pages](https://lintubaby5.github.io/belly-button-challenge/), which catalogs the microbes that colonize human navels.

### Completed the following steps:

* Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

* Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

![Barchart](https://github.com/lintubaby5/belly-button-challenge/blob/main/Images/Barchart.png)


* Use sample_values as the values for the bar chart.

* Use otu_ids as the labels for the bar chart.

* Use otu_labels as the hovertext for the chart.

### Created a bubble chart that displays each sample.

* Use otu_ids for the x values.

* Use sample_values for the y values.

* Use sample_values for the marker size.

* Use otu_ids for the marker colors.

* Use otu_labels for the text values.

![Bubblechart](https://github.com/lintubaby5/belly-button-challenge/blob/main/Images/BubbleGraph.png)


### Displayed the sample metadata, i.e., an individual's demographic information.


### Displayed each key-value pair from the metadata JSON object somewhere on the page.


![MetadataJson](https://github.com/lintubaby5/belly-button-challenge/blob/main/Images/Metadata_json.png)



### Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:


![Dashboard Screenshot](https://github.com/lintubaby5/belly-button-challenge/blob/main/Images/Dashboard_screenshot.png)



### Deployed app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo

## Advanced Challenge Assignment

* Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.

* You will need to modify the example gauge code to account for values ranging from 0 through 9.

* Update the chart whenever a new sample is selected.


![Guage Chart](https://github.com/lintubaby5/belly-button-challenge/blob/main/Images/GuageChart.png)
