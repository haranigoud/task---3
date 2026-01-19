 Task Name: Exploratory Data Analysis (EDA)
Dataset: Netflix Movies and TV Shows

Dataset Description :

The dataset contains information about movies and TV shows available on Netflix, including :

Type (Movie / TV Show)
Release Year
Rating
Duration
Genre
Country
Description

Total Records: 8,807
Total Features: 12

 Tools & Libraries Used :

Python
Pandas
Matplotlib
Seaborn

Exploratory Data Analysis Steps
Data Loading & Inspection :

Loaded the dataset using Pandas
Displayed first 5 rows 
Checked dataset structure and data types

Distribution of Numerical Feature :

Plotted a histogram for release_year
Observed that most content was released after 2010

Categorical Feature Analysis :

Used count plots to analyze :

Type (Movie vs TV Show)
Rating distribution

Outlier Detection :

Cleaned the duration column for movies
Used a box plot to identify outliers in movie duration

 Correlation Analysis :

Plotted a correlation heatmap
Observed limited correlation due to few numerical features

Feature Importance Identification :

Important features identified for prediction :

type 
rating
release_year
duration
listed_in

 Key Insights :

Netflix content increased rapidly after 2010
Movies dominate the platform
TV-MA and TV-14 are the most common ratings
Some movies have unusually long durations
Dataset is mostly categorical

Conclusion :

This task helped in understanding Netflix content trends using basic exploratory data analysis techniques. Visualizations made it easier to identify patterns, outliers, and important features for further analysis.