# Amazon_Sales_MLanalysis
## PCA-KMeans and Random Forest Rating Prediction

### Project Overview

This repository showcases two distinct machine learning approaches applied to e-commerce data. The first section of the project employs Principal Component Analysis (PCA) and K-Means clustering to segment products based on pricing and customer ratings. The second section uses a Random Forest Regressor to predict product ratings, drawing upon features like product descriptions, pricing, and discount strategies.

### Features

- **Data Preprocessing**: Involves cleaning price fields, handling missing values, and normalizing the dataset for analysis.
- **Feature Engineering**: Applies TF-IDF on product descriptions, encodes categorical variables, and compiles relevant features for modeling.
- **PCA**: Implements dimensionality reduction for data visualization and pattern identification.
- **K-Means Clustering**: Segments products into meaningful clusters to extract market insights.
- **Random Forest Regression**: Builds a predictive model for product ratings to gauge the impact of various features.
- **Model Evaluation**: Utilizes Mean Squared Error to validate the accuracy of the predictive model.

### Business Insights

- **Market Segmentation**: Offers an understanding of product grouping by features for targeted marketing and positioning.
- **Pricing Analysis**: Explores the relationship between pricing, discounts, and customer ratings.
- **Content Analysis**: Evaluates the effect of product descriptions on customer perception and ratings.
- **Predictive Modeling**: Provides a predictive framework for customer ratings to support product recommendation systems and inventory planning.

### Installation

```bash
git clone https://github.com/[your-username]/[repository-name].git
cd [repository-name]
pip install -r requirements.txt
