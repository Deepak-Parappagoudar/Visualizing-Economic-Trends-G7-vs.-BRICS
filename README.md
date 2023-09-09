# Visualizing-Economic-Trends-G7-vs.-BRICS

# Introduction

This Jupyter Notebook analyzes economic data for the G7 (Group of Seven) and BRICS (Brazil, Russia, India, China, South Africa) countries. The data includes various economic indicators such as nominal GDP, nominal GDP per capita, population, PPP (Purchasing Power Parity) GDP, PPP GDP per capita, and total exports.


# Installation

Before running the notebook, make sure to install the required Python packages. You can do this by running the following command:

!pip install wbgapi squarify
Additionally, to save Plotly charts as image files, you need to install Kaleido:

!pip install -U kaleido

# Data Collection

Data for the G7 and BRICS countries is collected using the World Bank API. The following economic indicators are collected:

Total Population
Nominal GDP
PPP GDP
Nominal GDP Per Capita
PPP GDP Per Capita
Total Exports

# Pre-processing and Formatting

The collected data is preprocessed and formatted to improve readability and consistency. Column names are renamed, and the data is sorted by country and time.


# Visualizing the Comparison

The notebook includes visualizations to compare economic indicators between the G7 and BRICS countries over time. The following comparisons are made:

Nominal GDP Comparison
Nominal GDP Per Capita Comparison
Population Comparison
PPP GDP Comparison
PPP GDP Per Capita Comparison
Total Exports Comparison
These comparisons are visualized using line charts to highlight the differences and trends over the years.


# Visualizing the Comparison Amongst Countries

In addition to comparing G7 and BRICS as groups, the notebook also visualizes the economic distribution among individual countries within these groups. The following visualizations are included:

Treemap visualizations to show GDP distribution in G7 and BRICS countries in 2022.
Line charts showing the trend of Nominal GDP over time for individual G7 and BRICS countries.
Bar charts displaying Purchasing Power Parity GDP (PPP GDP) over time for individual G7 and BRICS countries.
Animated bar charts illustrating Purchasing Power Parity GDP Per Capita over time for individual G7 and BRICS countries.
Animated bar charts showcasing Total Exports over time for individual G7 and BRICS countries.
These visualizations provide insights into the economic performance of individual countries within the G7 and BRICS groups.

Feel free to explore the notebook for a detailed analysis of economic data and visualizations for the G7 and BRICS countries. You can run the code and generate your own visualizations based on the collected data.
