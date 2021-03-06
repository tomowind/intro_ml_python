# Introduction to Machine Learning with Python

[Introduction to Machine Learning with Python](https://github.com/amueller/introduction_to_ml_with_python) 을 읽으면서 노트북으로 배운것들을 정리했습니다.
1. [Introduction](notebooks/01-introduction.ipynb): [mglearn](https://github.com/amueller/introduction_to_ml_with_python/tree/master/mglearn) 을 비롯한 각종 라이브러리를 설치하고, iris 데이터셋을 knn 으로 돌려봅니다
2. Supervised Learning
    - [Datasets](notebooks/02-datasets.ipynb): make_forge, make_wave, breast_cancer, boston, make_moons, make_circles, citi_bike 데이터셋
    - [KNN](notebooks/02-knn.ipynb): KNN classification, regression 을 서로 다른 k 에 대해서 돌립니다.
    - [Linear Models](notebooks/02-linear-models.ipynb): LinearRegression, Ridge, Lasso, LogisticRegression, LinearSVC를 다룹니다.
    - [Naive Bayes](notebooks/02-naive-bayes.ipynb): 책에 내용이 부족하여 나중에 더 공부하기로 했습니다. 
    - [Decision Trees](notebooks/02-decision-tree.ipynb): DecisionTree, RandomForest, GradientBoosting.
    - [SVM](notebooks/02-svm.ipynb): RBF kernel classification
    - [Neural Networks](notebooks/02-neural-networks.ipynb): Multi-layer perceptron with solver, optimizer tunings
    - [Uncertainty Estimates](notebooks/02-uncertainty-estimates.ipynb): Decision Function, Prediction Probabilities
3. Unsupervised Learning
    - [Datasets](notebooks/03-datasets.ipynb): lfw_faces, digits, mnist, make_signal 데이터셋
    - [Preprocessing and Scaling](notebooks/03-preprocessing-and-scaling.ipynb): MinMaxScaler, StandardScaler
    - [Dimensionality Reduction, Feature Extraction, Manifold Learning](notebooks/03-dimensionality-reduction.ipynb): PCA, NMF, t-SNE
    - [Clustering](notebooks/03-clustering.ipynb): k-Means, Agglomerative, DBSCAN
4. [Representing Data and Engineering Features](notebooks/04-representing-data-and-engineering-features.ipynb): Categorical Variables (OneHotEncoding), Binning, Polynomials, Feature Selection
5. [Model Evaluation and Improvement](notebooks/05-model-evaluation-and-improvement.ipynb): cross validation, grid search, evaluation metrics
6. [Algorithm Chains and Pipelines](notebooks/06-algorithm-chains-and-pipelines.ipynb): pipeline 사용으로 코드를 간결하고 정확하게 사용하는 방법을 알아봅니다
7. [Working with Text Data](notebooks/07-working-with-text-data.ipynb): Supervised Leaning (Bag of Words, TF-IDF, n-Grams, Lemmatization) and unsupervised learning (Topic Modeling and Document Clustering)