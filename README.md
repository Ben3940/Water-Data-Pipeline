# Water-Data-Pipeline

## Project Description

This project explores a dataset pertaining to _water potability_ from **Kaggle's** dataset repository. The dataset includes water samples and measurements of the water's properties:
ph
Hardness
Solids
Chloramines
Sulfate
Conductivity
Organic Carbon
Trihalomethanes
Turbidity

The project is displayed as a _jupyter notebook_ and creates a small data pipeline to extract insights/trends from the data. The notebook will often present the data in a tabular format, while further down in the notebook, plots will be used to visualize correlations and knowledge extraction using ML models.

## Challenges

1. I initially thought of focusing on one particular property (i.e. ph) and pairing it with each of the other properties listed above. Each water sample would be plotted on a scatter plot, with the color of each sample being denoted by its potability (i.e. 0 or 1). After some testing (i.e. trying different properties to focus on) I began to realize that looking at two properties at a time was not sufficient to show any trends in the dataset. This makes sense as high levels in any of these properties could result in the water being non-drinkable. So while "ph" and "Hardness" levels might seem fine for the water to be potable, the sample could have hazardous amounts of sulfates or organic carbons.

This meant that I needed to find a better way to include more properties at once in the data visualizations. While not focusing on too many properties at once and making my results appear "noisy".
