# Netflix Movies and TV Shows Clustering

## Project Type

Unsupervised Machine Learning

## Contribution

Individual Project

## Project Summary

This project applies unsupervised learning techniques to cluster Netflix movies and TV shows into meaningful groups based on their attributes. The aim is to uncover hidden patterns in the content catalog, which could be leveraged to enhance content recommendations and improve the user experience. By clustering content based on features such as genre, duration, ratings, and cast, the project identifies similarities and differences in Netflix's catalog without requiring labeled data.

## Dataset

- **Source:** The dataset was collected from publicly available sources such as Kaggle.
- **Attributes:** The dataset includes features like title, genre, release year, duration, ratings, cast, and type (movie or TV show).

## Data Preprocessing

- Handled missing values by imputing or removing incomplete records.
- Encoded categorical features such as genres and ratings.
- Standardized numerical attributes to ensure uniformity in clustering.
- Applied feature selection techniques to retain only relevant data.

## Clustering Approach

- Used **K-Means Clustering** to group similar movies and TV shows.
- Determined the optimal number of clusters using the **Elbow Method**.
- Applied **Principal Component Analysis (PCA)** for dimensionality reduction and visualization.
- Experimented with alternative clustering methods like **Hierarchical Clustering** and **DBSCAN**.

## Key Findings

- Content was successfully grouped into distinct clusters based on genre and popularity.
- PCA visualization provided insights into how movies and TV shows are distributed across feature space.
- The clustering model highlighted trends such as genre-based groupings and differences between movies and TV shows.

## Libraries Used

- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical operations
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Machine learning algorithms (K-Means, PCA, etc.)

## Conclusion
This project successfully demonstrates how unsupervised learning techniques can be used to uncover hidden patterns in Netflix’s content catalog. The clustering results provide meaningful insights that can enhance recommendations and content discovery. By improving feature selection and incorporating additional data sources, the project can be further refined for more accurate and valuable results.


