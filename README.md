# A Network Analysis of Game of Thrones
Overview:
This GitHub project explores the world of "Game of Thrones" using network analysis techniques. The project analyzes the co-occurrence network of characters in the "Game of Thrones" books, examining how characters interact and evolve throughout the series. The project uses Python and various libraries, including pandas, networkx, and matplotlib, to perform the analysis.

Project Structure:
The project consists of several Jupyter Notebook cells, each focusing on a specific aspect of the analysis. Here's an overview of the main sections:

Dataset Loading and Introduction:

The project starts by introducing the dataset, which represents the network of character interactions.
It uses pandas to load the data for the first book, "A Game of Thrones," and provides a brief overview.
Creating the Network:

The project uses the network analysis library networkx to create a graph object representing the character co-occurrence network for the first book.
It demonstrates the process of initializing an empty graph and populating it with edges from the dataset.
Character Importance Metrics:

The project explores different measures of character importance within the network, including degree centrality.
It identifies the top ten important characters in the first and fifth books based on degree centrality.
Character Importance Evolution:

The evolution of character importance throughout the series is examined.
Plots show how the importance of characters like Eddard Stark, Jon Snow, and Tyrion changes over time based on degree centrality.
Betweenness Centrality Analysis:

The project introduces betweenness centrality as another measure of character importance.
It analyzes the evolution of the top characters based on betweenness centrality.
PageRank Analysis:

PageRank, originally used by Google, is discussed as a measure of importance.
The project explores character importance according to PageRank and examines the evolution of the top characters based on this metric.
Correlation Between Measures:

The project investigates the correlation between different importance measures (PageRank, betweenness centrality, and degree centrality) for the fifth book using Pearson correlation.
Conclusion:

The project concludes by summarizing its findings and highlighting the most important characters in the fifth book based on the three different measures.
Key Insights:

The project demonstrates how different metrics can be used to measure character importance in a network.
It visualizes the evolution of character importance across the "Game of Thrones" books.
Correlation analysis suggests a high correlation between different importance measures.
Audience:
This project is aimed at individuals interested in data analysis, network analysis, and "Game of Thrones" fans who want to explore the relationships between characters in the series.

Usage:
To use this project, you can download the Jupyter Notebook and the associated dataset files. You can then run the code cells to reproduce the analysis and gain insights into the character dynamics in the "Game of Thrones" world.

Note:
Make sure to have the necessary Python libraries (e.g., pandas, networkx, matplotlib) installed in your environment before running the code.
