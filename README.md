# Crop-and-Fertilizer-Recommendation-System
Agriculture is essential for human survival, and soil nutrients play a critical role in crop growth. Key nutrients such as Potassium (K), Phosphorus (P), and Nitrogen (N) are crucial in determining soil quality. The yield of specific crops is higher when the soil contains the right balance of these nutrients. However, the optimal crop-to-soil nutrient relationship is often unknown. Machine learning can be applied to identify which crops thrive best in given soil conditions based on soil parameters. Additionally, this model will recommend organic fertilizers to enhance soil quality. By providing recommendations for suitable crops and fertilizers, farmers can improve crop yield effectively.

# Datasets
Two datasets are used in this work.
1) Crop_recommendation.csv - This dataset includes values for Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH and rainfall along with the corresponding crop.
2) Fertilizer.csv - This dataset contains various organic fertilizers and their associated N, P, and K values.

# Crop Recommendation-System
In the crop recommendation system, the user provides inputs such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, and rainfall. Based on these inputs, the system recommends the most suitable crop. Several machine learning algorithms are employed for this system, including Support Vector Machine (SVM), Decision Tree, Random Forest, Naïve Bayes, and k-Nearest Neighbor (KNN). The table below shows the accuracy of each algorithm. For this particular work, the KNN algorithm is used.

| Algorithm                 | Accuracy    |
|---------------------------|-------------|
| Support Vector Machine    | 98%         |
| Decision tree	            | 95%         |
| Random forest             | 95%         |
| naïve bayes               | 95%         |
| k-Nearest Neighbor        | 98%         |

# Fertilizer Recommendation-System
In the fertilizer recommendation system, inputs such as Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity, pH, rainfall, and the crop to be cultivated are provided. The model first determines the optimal N, P, K values based on the input parameters using the KNN algorithm. Next, our soil's N, P, K values are subtracted from the required values to identify the nutrient deficiencies in the soil. These deficient nutrient values (N, P, K) are then fed into another KNN model. This model searches for an organic fertilizer whose nutrient composition is closest to the input values and provides it as a recommendation. The KNN algorithm gives the accuracy of 95% for this system.
 
