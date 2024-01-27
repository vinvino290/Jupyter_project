# Jupyter_project
Data Wrangling:
Imported the pandas library.
Read the video game sales data from the "vgsales.csv" file into a Pandas DataFrame.
Checked the first four rows of the data frame using df.head(4).
Checked the shape of the data frame using df.shape and data types using df.info().
Identified and counted null values in the dataset using df.isnull().sum().
Removed rows with null values using df = df.dropna().
Checked for duplicates using df.duplicated().sum() and found none.
Displayed the last four rows of the cleaned data using df.tail(4).

Exploratory Data Analysis (EDA):
Imported the matplotlib library for data visualization.
Computed descriptive statistics for the dataset using df.describe().
Counted the occurrences of each genre using df['Genre'].value_counts().
Plotted a horizontal bar chart for the count of games by genre.
Counted the occurrences of each publisher using df['Publisher'].value_counts().
Selected the top five publishers and plotted a line graph for the top 5 VG publishers' sales.
Extracted a subset of the data for global sales and year, then displayed the top four rows.
Calculated the average sales in each country (NA, EU, JP, Other) using countries_sales.mean().
Plotted a pie chart to show the distribution of sales by region.

Summary of Analysis:
The action genre is the most popular, with 3251 games.
Electronic Arts is the top publisher, selling the majority of video games.
Video game sales experienced a significant increase in 2006.
The pie chart shows the sales distribution by region, with North America having the highest share.
These steps provide a comprehensive overview of the data cleaning and analysis process for the video game sales dataset.
