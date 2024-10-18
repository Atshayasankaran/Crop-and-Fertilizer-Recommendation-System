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
 
