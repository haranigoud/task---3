Dataset Description :

The Iris dataset is a classic dataset used in machine learning and data analysis.
It contains measurements of iris flowers belonging to three different species.

Features:

SepalLengthCm
SepalWidthCm
PetalLengthCm
PetalWidthCm
Species

Total Samples: 150
Total Species: 3

Tools & Libraries Used :

Python
Pandas
Matplotlib
Seaborn

Exploratory Data Analysis Steps :

Data Loading & Inspection :

Loaded dataset using Pandas
Checked dataset structure and data types
Verified absence of missing values

Statistical Summary :

Used .describe() to understand mean, standard deviation, min, and max values

 Distribution of Numerical Features :

Plotted histograms for all numerical columns
Observed clear distribution differences among features

 Categorical Feature Analysis :

Used count plot to visualize the number of samples in each species

Outlier Detection :

Used box plots to detect outliers in numerical features

Minor outliers observed in SepalWidthCm

 Correlation Analysis :

Used correlation heatmap to understand feature relationships
Strong correlation observed between petal length and petal width

Key Insights :

Dataset is clean with no missing values
All three species are evenly distributed
Petal features show strong correlation and are important for classification
Sepal width contains minor outliers

Conclusion :

This task demonstrates how Exploratory Data Analysis helps in understanding data patterns, detecting outliers, and selecting important features before applying machine learning models.