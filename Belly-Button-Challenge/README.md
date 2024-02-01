This is an interactive dashboard designed to explore the Belly Button Biodiversity dataset, which contains information about the microorganisms that inhabit human navels. The dataset classifies these microorganisms as operational taxonomic units (OTUs).

Key Features of the Dashboard:

Drop Down Menu: Users can select a Test Subject ID from a dropdown menu to view different visualizations, including bar charts, gauges, and bubble charts.

Demographic Info Panel: This panel displays demographic information related to the chosen test subject. It presents key-value pairs from the metadata JSON object.

Horizontal Bar Graph: When a test subject is selected from the dropdown menu, a bar chart is generated. This chart displays the top 10 OTUs found in that specific test subject. The sample_values are represented as the values on the bar chart, and the otu_ids are used as labels for the bars. Hovering over a bar provides additional information in the form of otu_labels.

Bubble Chart: Selecting a test subject from the dropdown menu generates a bubble chart. Each sample is represented as a bubble, with the size of the bubble indicating the sample's value. The x-axis represents otu_ids, while the y-axis represents sample_values. The colors of the bubbles correspond to the otu_ids, and hovering over a bubble provides otu_labels as additional information.

In summary, this dashboard offers an interactive way to explore the Belly Button Biodiversity dataset, allowing users to visualize and analyze the microbial diversity found in human navels.
