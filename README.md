To perform the data analysis and visualization on the Zomato dataset, three primary Python libraries were used. Each serves a specific purpose in the workflow:

1. Pandas (import pandas as pd)
Pandas is the core library for data manipulation and analysis.

Role in this analysis: It was used to load the CSV file into a "DataFrame," clean the data (like removing the "/5" from ratings), filter the top-rated restaurants, and calculate summary statistics (mean cost, total counts).

2. Matplotlib (import matplotlib.pyplot as plt)
Matplotlib is the foundation for all plotting in Python.

Role in this analysis: It was used to create the figure layouts, handle the axes, set titles, and ultimately save the visualizations as image files (PNGs).

3. Seaborn (import seaborn as sns)
Seaborn is a high-level visualization library built on top of Matplotlib.

Role in this analysis: It was used to generate the aesthetically pleasing and statistically informative charts, such as the distribution (histogram) of ratings, the count plots for order types, and the regression plot for cost vs. rating.

Code Snippet: The Import Block
These are the lines of code that initialize these libraries at the beginning of the analysis:
