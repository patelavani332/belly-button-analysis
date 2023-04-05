# belly-button-analysis
Analysis using JavaScript
## Background
In this project, an interactive dashboard is built to explore the Belly Button Biodiversity Dataset(http://robdunnlab.com/projects/belly-button-biodiversity/), which catalogs the microbes that colonize human navels.

The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.

D3 library is used to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

## Resources

* Visual Studio Code 

## Dashboard

### Bar Chart
A horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual is created.

Sample_values are used as the values for the bar chart.

otu_ids are used as the labels for the bar chart.

otu_labels are used as the hovertext for the chart.

Following is the bar chart obtained from the data.

![bar](https://user-images.githubusercontent.com/120197958/230148212-7a2ac3f4-6a89-4ad1-8afa-2b0a0466d1cb.png)

### Bubble Chart
A bubble chart that displays each sample is created.

otu_ids are used for the x values.

sample_values are used for the y values.

otu_ids are used for the marker colors.

otu_labels are used for the text values.

Following is the bubble chart obtained from the data.

![bubble](https://user-images.githubusercontent.com/120197958/230149105-6f7524e3-4aec-4150-9ef8-b023fc56ec44.png)

### Display the sample metadata, i.e., an individual's demographic information.

![demo](https://user-images.githubusercontent.com/120197958/230149296-a42e1a49-6cae-430d-8878-c6ed4065509e.png)

### Gauge Chart

Adapted the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.

![gauge](https://user-images.githubusercontent.com/120197958/230149878-f51cf244-08e0-42e1-974f-a982de6c0c9f.png)


### Link to the live site: 
https://patelavani332.github.io/belly-button-analysis/
