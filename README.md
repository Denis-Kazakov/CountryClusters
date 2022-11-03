# Study project. Clustering world nations by a set of different features

This is a continuation of another project that compared religiousness of population to other factors. All data were taken from Wikipedia, collected in a single file (Raw_data.xlsx) and then prepared and saved in individual csv files (folder raw_data).

I also removed and renamed some columns for this project (folder prepared_csvs).

Data were merged into a single data frame and prepared for further analysis: removed rows (countries) with missing data and scaled all variables.

I considered two options: with and without the size of population.

PCA was performed for both options, showing several variables with almost equal contribution to the first principal component.

This was followed by KMeans clustering with silhouette scores used to select the best clustering approach.

Notebooks:

- data_preparation_analysis.ipynb – data preparation and PCA

- country_clusters_with_population.ipynb – clustering with data on population

- country_clusters_without_population.ipynb – clustering without data on population

