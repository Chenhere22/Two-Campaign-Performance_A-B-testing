A/B Testing Analysis Project

This project explores the outcomes of two marketing campaigns using data from a website, such as the number of clicks, purchases, and other user interactions.

Dataset

The data used in this project was loaded from Kaggle: A/B Testing Dataset.

Data Overview

The dataset includes data from both control and test campaigns, with the following columns:

Campaign Name: The name of the campaign (Control or Test).

Date: The date of the campaign data.

Spend [USD]: The advertising spend in USD.

# of Impressions: The number of times the advertisement was shown.

Reach: The unique number of users who saw the advertisement.

# of Website Clicks: The number of clicks on the website.

# of Searches: The number of searches conducted by users.

# of View Content: The number of times users viewed specific content.

# of Add to Cart: The number of times users added items to their cart.

# of Purchase: The number of purchases made.

Analysis

The analysis involved comparing the control and test campaigns to evaluate their effectiveness. Various statistical techniques, such as t-tests, were used to determine if there were significant differences in campaign performance metrics like the number of impressions and purchases. Additionally, machine learning models were trained to predict campaign success based on the provided features.

Tools and Techniques

Python: Used for data analysis and machine learning.

Scipy: Conducted statistical t-tests to compare campaign metrics.

XGBoost: Trained a machine learning model to predict campaign group.

Sklearn: Used for model evaluation and splitting the data into training and test sets.
