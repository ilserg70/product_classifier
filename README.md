# Product Classifier
Classification of text data using multiple product features.


# Data

## Training data set
File: `training_data.xlsx` comprising 6k records spread across 63 categories (approx. 100 items per category).
Training data includes ASIN, Brand Name, Category Name, Product Title, Image URL.

## Unclassified dataset
File: `data_to_classify.xlsx` comprising 57k records with the relevant data (ASIN, Brand Name, Product Title, Image URL).

## Classification categories
File: `categories.xlsx` contains 63 categories

# Solution
Classification of the data provided in the `data_to_classify.xlsx` file into the categories provided under the `categories.xlsx` file, using the `training_data.xlsx`.