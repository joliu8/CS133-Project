# CS133-Project
Project Title: Waddle We Know? (Visualizing Penguin Dataset)

Authors: Joyce Liu and Gigi Zhang   

Project Description: 
- For this project, we will be using a [Penguin Dataset](https://www.kaggle.com/code/tirendazacademy/penguin-dataset-data-visualization-with-seaborn/notebook). We plan to clean the data by dropping categorical data and using imputation methods for numerical data. We plan to create static visualizations/graphs to better understand the dataset characteristics. We will also perform statistical tests to compare groups and test hypotheses. Finally, we will create an interactive dashboard so users can explore the data on their own.  

Project Outline/Plan:
- Interface Plan:   
    - Page for the static visualizations
    - Page for the interactive dashboard 

- Data Collection and Storage Plan:  
    - Load and store csv file from Kaggle

- Data Analysis and Visualization Plan:  
    - Data Analysis:
        - Two-sample t-test or ANOVA: To compare body mass or flipper length across different species or sexes
        - Chi-Square Test of Independence: To see if species distribution depends on the island they live on
    - Static Visualizations:
        1. Bar chart by species
        2. Scatter plot of culmen length vs culmen depth
        3. Histogram of body mass
        4. Box Plot of flipper length by sex and penguin species
        5. Heatmap of the correlations between numerical variables
    - Interactive Dashboard:
        - User can: select variables/type of graph/color palette and hover over data points
