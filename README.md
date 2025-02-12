STEPS IN EXPLORATORY DATA ANALYSIS USING MATPLOTLIB AND SEABORN

1. Importing Necessary Libraries
-pandas → Handles data loading and manipulation.
-numpy → Supports numerical operations.
-seaborn & matplotlib.pyplot → Used for visualization.

2. Loading the Dataset
-The dataset is read into a Pandas DataFrame.
-The dataset contains football player attributes like:
Dribbling skills
Ball control ability
Position of the player on the field

3. Displaying the Dataset
-The entire dataset is displayed, likely using the dataset.head() function.
-This provides an overview of the columns and values present.

4. Creating a Scatter Plot for Analysis
-A scatter plot is created using Seaborn (sns.scatterplot()).
-The x-axis represents "Dribbling" and the y-axis represents "Ball Control".
-The color of each point is determined by the player’s position on the field.
-This visualization helps to understand the relationship between dribbling and ball control among players of different positions.

5. Adding Labels and Legends
-The x-axis is labeled as "Dribbling".
-The y-axis is labeled as "Ball Control".
-A legend is placed outside the plot to identify player positions.

6. Displaying the Scatter Plot
-The plot is displayed using plt.show(), allowing us to analyze how dribbling and ball control vary by position.

||Understanding "FutureWarning" in Python||

What is a FutureWarning?
A FutureWarning is not an error but a notice that some functionality will change in future versions of the library.
It is used to inform users in advance that certain functions may be deprecated or work differently in newer versions.

|Why Does FutureWarning Appear?|

Seaborn Updates → Some arguments in sns.scatterplot() may have changed.
Matplotlib Updates → Label or legend handling might be modified in newer versions.
Pandas/Numpy Updates → Certain functions used in the dataset might be deprecated.
