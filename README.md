
# NYTimes Network Analysis

This repository contains the project "Visualising and Interpreting Networks," where network analysis techniques are applied to data collected from the New York Times Article Search API. The project involves searching for specific terms, analyzing co-occurrence networks, and visualizing network metrics such as centrality and clustering.

## Project Overview

The main goal of this project is to visualize and interpret networks of terms related to cars, AI, machine learning, and road safety. By searching for relevant articles in the New York Times and creating networks from the data, we aim to analyze term co-occurrences and derive insights about their relationships.

### Key Objectives
1. Collect data from the New York Times API using a list of search terms.
2. Analyze the network of terms using descriptive network statistics.
3. Visualize the network with different layouts and perform community detection.
4. Calculate various centrality metrics (degree, betweenness, closeness, eigenvector).
5. Assess whether the network exhibits characteristics of power law and small-world properties.

## Files Included
- `Webscraping.Rmd`: R Markdown file used for collecting data, performing analysis, and generating visualizations.
- `Terms.txt`: Text file containing the list of search terms used for querying the New York Times API.
- `Final.RData`: R data file containing the final processed outputs and results.
- `cars.RData`: R data file containing data related to car terms and the network graph. - 

## Prerequisites
- R (version 3.5 or higher)
- R packages: `magrittr`, `httr`, `data.table`, `igraph`, `dplyr`, `xml2`

## Getting Started

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/NYTimes-Network-Analysis.git
   cd NYTimes-Network-Analysis
   ```

2. **Set Up the Environment**
   - Make sure R and the necessary packages are installed.
   - Obtain an API key from [New York Times API](https://developer.nytimes.com/signup) and replace the placeholder in the R scripts.

3. **Run the Analysis**
   - Open `Webscraping.Rmd` in RStudio.
   - Execute the code chunks sequentially to collect data, process the network, and generate visualizations.

## Results
The analysis provides insights into term co-occurrences within the context of cars, AI, machine learning, and road safety. It evaluates different network properties and visualizes the connections between search terms.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments
- [New York Times Article Search API](https://developer.nytimes.com/docs/articlesearch-product/1/overview) for providing the data.
- R packages used for data processing and visualization.
