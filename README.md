# Customer Segmentation Project on a Clothing Company 
Uses unsupervised clustering (K-Means) on a clothing company's customer data to identify distinct segments for targeted marketing strategies. Focuses on data preprocessing, feature analysis, and model implementation.


## Objective & Methodology
To build a robust and accurate recommendation system capable of predicting user ratings for video games and filtering results based on specific game metadata.

#### Methodology
1. **Model Selection:** Employing Collaborative Filtering using the Matrix Factorization technique.
2. **Optimization:** Using an optimization algorithm like Stochastic Gradient Descent (SGD) to train the factorization model.
3. **Recommendation & Filtering:** Generating predictions and allowing users to filter results by Name, Genre, Platform, and Year of Release.

## Dataset Detail
- **Source**: A clothing company's customer transaction and review data
- **Target**: N/A (Unsupervised Learning)

#### types of columns
- **Value/Frequency:** Purchase Amount (USD), Previous Purchases
- **Engagement**: Review Rating
- **Demographics**: Gender

**Preprocessing Notes:**
Numerical features were confirmed to have no significant outliers and showed a normal distribution, making them suitable for distance-based clustering.

## Model and Evaluation
Using unsupervised algorithm (K-Means) with comparing Sillhouette, Elbow, and Davies-Bouldin Score and fine tuning with feature selection using **PCA**

## Feature Importance
In clustering, feature importance is defined by the variables that contribute most to the separation between the final clusters (i.e., those with the largest variance across cluster centroids).
- Features related to expenditure and loyalty, primarily Purchase Amount (USD) and Previous Purchases, are expected to define the segments (e.g., "High Spenders," "Infrequent Buyers").

## Insights
- The customer are segmented through age, engagement, ratings and frequency of purchase
- The segments derived will allow the clothing company to tailor offers, such as offering discounts to price-sensitive segments or presenting loyalty rewards to high-value segments.
- The analysis provides a data-driven structure for developing a Customer Relationship Management (CRM) program with recommendation for each cluster 


###### This project is for educational purposes only.
###### by Calista.L
