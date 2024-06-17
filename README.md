# Classification notebook

Classification ActivityActivity developed in the Intelligent Systems course during the Master's Degree in Computer Science

## Proposed Activity

The proposed activity is the analysis and classification of web pages for phishing and malicious activity detection. For this purpose, public datasets available [here](https://www.kaggle.com/datasets/danielfernandon/web-page-phishing-dataset/data) were used

### In the main notebook:

* Comparison with scikit-learn Classifiers

    We will compare the performance of our custom KNN model with four other pre-built classifiers available in the scikit-learn library. This will help us evaluate the effectiveness of our implementation.

*  K-Fold Cross-Validation and Evaluation Metrics

    We will employ the K-fold cross-validation technique to assess the robustness and generalizability of our models. Additionally, we will define appropriate metrics to quantify the performance of each classifier.

### In the clustering notebook:
* Clustering

    We have implemented the "kmeans" clustering algorithm from scratch (without using any libraries) on the same dataset mentioned above (this time without labels).

* Classification

    Following clustering, we performed classification on the test samples, using the clusters generated in the previous step as a basis.

