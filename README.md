# Iris_DS_Analysis

# Iris Dataset Visualization and Analysis 🌸
This project explores the classic Iris dataset using Python libraries Seaborn and Matplotlib. The goal is to perform an exploratory data analysis by creating various visualizations to understand the characteristics and relationships between different iris species based on their sepal and petal measurements.

# Key Insights from Visualizations
The visualizations revealed several key insights about the dataset:

Petal Dimensions are Highly Predictive: The scatter plots and pair plots showed a strong positive correlation between petal length and petal width. More importantly, the three iris species form distinct, non-overlapping clusters when plotted against these two features. This indicates that petal dimensions are the most effective features for classifying the iris species.

Setosa is an Outlier: The visualizations consistently showed that the Setosa species is easily separable from the other two. Its sepal and petal dimensions are significantly smaller and have a much tighter distribution compared to Versicolor and Virginica.

Overlap in Sepal Features: While the violin plot confirmed a difference in the median sepal length between the species, there is considerable overlap in the distributions of both sepal length and sepal width between the Versicolor and Virginica species. This suggests that sepal dimensions are not as reliable as petal dimensions for distinguishing between these two species.

# Visualizations
Here are screenshots of the graphs generated during this analysis:

1. Violin Plot of Sepal Length by Species

This plot shows the distribution of sepal length for each species, highlighting the tighter distribution of Setosa.
<img width="842" height="548" alt="image" src="https://github.com/user-attachments/assets/54c1bc39-26ee-457f-8bd2-c21e89c95e5a" />


2. Scatter Plot of Petal Dimensions by Species

This plot effectively demonstrates the clear separation of the three species into distinct clusters based on their petal dimensions.
<img width="841" height="546" alt="image" src="https://github.com/user-attachments/assets/6fa1d36f-4d22-4c75-94e5-75021e6df837" />


3. Pair Plot of All Features

This comprehensive grid of plots provides a complete overview of all pairwise relationships, confirming that petal dimensions are the strongest features for classification.
<img width="1137" height="1023" alt="image" src="https://github.com/user-attachments/assets/38e5c7e5-1bcf-4cdb-acf0-3883df999363" />
