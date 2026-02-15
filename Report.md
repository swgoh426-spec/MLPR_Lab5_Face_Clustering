Q) What are the common distance metrics used in distance-based classification algorithms?

A) Common distance metrics used in distance-based classification algorithms:

* Euclidean distance
* Manhattan distance
* Minkowski distance
* Cosine distance / Cosine similarity
* Hamming distance
* Mahalanobis distance



Q) What are some real-world applications of distance-based classification algorithms?

A) Real-world applications of distance-based classification algorithms:

* Distance-based classification algorithms are widely used in several real-world domains where similarity between data points is important.
* Face recognition and biometric authentication – used in surveillance systems, smartphone unlocking, and attendance systems by comparing feature distances between faces.
* Medical diagnosis and healthcare analytics – Mahalanobis distance is used for detecting abnormal patient patterns, disease classification, and identifying outliers in multivariate clinical data.
* Recommendation systems – products, movies, or songs are suggested based on similarity between user preference vectors.
* Document and text classification – cosine distance is commonly used to measure similarity between TF-IDF feature vectors in NLP tasks such as spam detection and news categorisation.
* Anomaly and fraud detection – distance measures help identify unusual transactions in banking and digital payment systems.



Q) Explain various distance metrics

A) Various distance metrics:

* Distance metrics measure the similarity or dissimilarity between data points in feature space.
* Euclidean distance computes the straight-line distance between two points and is suitable for continuous, uncorrelated, and equally scaled features.
* Manhattan distance calculates the sum of absolute differences and is more robust to outliers and high-dimensional data.
* Minkowski distance is a generalised form that includes Euclidean and Manhattan distances as special cases depending on the order parameter.
* Cosine distance measures the angular difference between vectors and is widely used in text and high-dimensional data where magnitude is less important than direction.
* Hamming distance counts the number of differing positions between two binary or categorical vectors.
* Mahalanobis distance considers the covariance between features and is scale-invariant, making it effective for correlated multivariate data and outlier detection.



Q) What is the role of cross validation in model performance?

A) Cross-validation is used to evaluate how well a model generalises to unseen data by dividing the dataset into multiple training and validation subsets. It provides a more reliable estimate of model performance than a single train–test split and helps in selecting optimal model parameters. By ensuring that every data point is used for both training and validation, it reduces the chances of overfitting and improves the robustness of the model. It is also commonly used for model comparison and hyperparameter tuning.



Q) Explain variance and bias in terms of KNN?
A) In KNN, the bias and variance depend on the value of K. A small value of K makes the model very flexible, which results in low bias but high variance because it becomes sensitive to noise and may overfit the training data. A large value of K makes the decision boundary smoother, which leads to high bias but low variance and can cause underfitting. Therefore, choosing an optimal value of K helps in balancing bias and variance and improves the model’s ability to generalise to unseen data.

