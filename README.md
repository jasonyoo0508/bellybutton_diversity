## bellybutton_diversity

# Create a Horizontal Bar Chart, Bubble Chart

1. Use the D3 library to read in samples.json.

2. Localhost:8000 to read the whole file in webpage. index.html won't work directly. 

Created a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.
The "Top 10 Bacteria Cultures Found" with 10 OTU, the base test subject ID No. is 940.

* Code is written in order to create the arrays when samples are selected from the dropdown menu to the left. 

Code is written to create the trace object in the buildCharts() function, and it contains the following:
The y values are the otu_ids in descending order
The x values are the sample_values in descending order
The hover text is the otu_labels in descending order.
Code is written to create the layout array in the buildCharts() function that creates a title for the chart


![bar chart](https://user-images.githubusercontent.com/89154507/140617502-4da432e9-f5ff-4142-99a7-bc37a2ad1bea.jpg)


Each sample(s) are displayed as below as a bubble chart

The otu_ids as the x-axis values.
The sample_values as the y-axis values.
The sample_values as the marker size.
The otu_ids as the marker colors.
The otu_labels as the hover-text values.

![BUBBLE](https://user-images.githubusercontent.com/89154507/140617523-afe4bbdc-da75-4e83-90fd-7f19dcb1e051.jpg)


The webpage has three customizations;
When the dashboard is first opened in a browser, ID 940’s data should be displayed in the dashboard, and all three charts should be working according to the requirements when a sample is selected from the dropdown menu.

Gauge
![Gauge colorful](https://user-images.githubusercontent.com/89154507/140617696-60006f17-dcad-4ad1-b5c9-2487f73ac4a0.jpg)



The base page below shows ID 940 with 3 customized category:
![Overvieww](https://user-images.githubusercontent.com/89154507/140617695-5e773d0b-32d1-4290-886d-d9fe7600bd94.png)

