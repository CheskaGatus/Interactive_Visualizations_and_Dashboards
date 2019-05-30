# Interactive_Visualizations_and_Dashboards

## Plotly.js

Used Plotly.js to build interactive dashboard to explore the Belly Button Biodiversity DataSet.

Created a PIE chart that uses data from samples route (/samples/<sample>) to display the top 10 samples.
- Used sample_values as the values for the PIE chart
- Used otu_ids as the labels for the pie chart
- Used otu_labels as the hovertext for the chart

Created a Bubble Chart that uses data from samples route (/samples/<sample>) to display each sample.
- Used otu_ids for the x values and for the marker colors.
- Used sample_values for the y values and for the marker size.
- Used otu_labels for the text values

Adapted the Gauge Chart from https://plot.ly/javascript/gauge-charts/ to plot the Weekly Washing Frequency obtained from the route (/metadata/<sample>), "WFREQ" key.

All charts are automatically updated whenever a new sample is selected.


## Heroku

Deployed this Flask app to Heroku.Please check it out at https://belly-button-diversity-cheska.herokuapp.com/
