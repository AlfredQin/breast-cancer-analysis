![](https://komarev.com/ghpvc/?username=srushtishimpi&label=PAGE+VIEWS&color=FD84BD)

<h1>BREAST CANCER ANALYSIS AND DIGNOSIS</h1>

<p>Machine learning is widely used in bio informatics and particularly in breast cancer diagnosis. In this project, we have used several classification methods to detect breast cancer. Cancer diagnosis is one of the most studied problems in the medical domain. Several researchers have focused in order to improve performance and achieved to obtain satisfactory results. Early detection of cancer is essential for a rapid response and better chances of cure. Unfortunately, early detection of cancer is often difﬁcult because the symptoms of the disease at the beginning are absent. Thus, it is necessary to discover and interpret new knowledge to prevent and minimize the risk adverse consequences.</p>

<p>To understand this problem more precisely, tools are needed to help oncologists to choose the treatment required for healing or prevention of recurrence by reducing the harmful effects of certain treatments and their costs. In artiﬁcial intelligent, machine learning is a discipline which allows the machine to evolve through a process. Wisconsin Diagnostic Breast Cancer (WDBC) dataset obtained by the university of Wisconsin Hospital is used to classify tumors as benign or malignant.</p>

<h2>OBJECTIVE</h2>

* Apply the fundamental concepts of machine learning from an available dataset
* Evaluate and interpret my results and justify my interpretation based on observed data set

<h2>PROCESS</h2>
<p>The analysis is divided into following sections:</p>

* Identifying the problem
* Reading Data 
* Exploratory Data Analysis
* Pre-Processing the Data
* Principle Component Analysis
* Try several models to predict whether breast cell tissue is malignant or Benign
* Calculate accuracy for each model
* Find Model/s with Highest Accuracy

<h2>MACHINE LEARNING CLASSIFICATION MODELS</h2>

<h3>LOGISTIC REGRESSION</h3>

<p>Logistic regression is a supervised machine learning algorithm mainly used for classification tasks where the goal is to predict the probability that an instance of belonging to a given class or not. It is a kind of statistical algorithm, which analyze the relationship between a set of independent variables and the dependent binary variables. It is a powerful tool for decision-making.</p>

<h3>K-NEAREST NEIGHBOUR</h3>
<p>K-Nearest Neighbours is one of the most basic yet essential classification algorithms in Machine Learning. It belongs to the supervised learning domain and finds intense application in pattern recognition, data mining, and intrusion detection. It is widely disposable in real-life scenarios since it is non-parametric, meaning, it does not make any underlying assumptions about the distribution of data (as opposed to other algorithms such as GMM, which assume a Gaussian distribution of the given data). We are given some prior data (also called training data), which classifies coordinates into groups identified by an attribute.</p>

<h3>SUPPORT VECTOR CLASSIFIER (SVC)</h3>
<p>SVM import SVC for fitting a model. SVC, or Support Vector Classifier, is a supervised machine learning algorithm typically used for classification tasks. SVC works by mapping data points to a high-dimensional space and then finding the optimal hyperplane that divides the data into two classes.</p>


<h3>STOCHASTIC GRADIENT DESCENT (SGD) CLASSIFIER</h3>
<p>Stochastic Gradient Descent (SGD) is a simple yet very efficient approach to fitting linear classifiers and regressors under convex loss functions such as (linear) Support Vector Machines and Logistic Regression. Even though SGD has been around in the machine learning community for a long time, it has received a considerable amount of attention just recently in the context of large-scale learning. SGD has been successfully applied to large-scale and sparse machine learning problems often encountered in text classification and natural language processing.</p>

<h3>DECISON TREE CLASSIFIER</h3>
<p>Decision Tree is a Supervised learning technique that can be used for both classification and Regression problems, but mostly it is preferred for solving Classification problems. It is a tree-structured classifier, where internal nodes represent the features of a dataset, branches represent the decision rules and each leaf node represents the outcome. The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features. A tree can be seen as a piecewise constant approximation.</p>


<h3>RANDOM FOREST CLASSIFIER</h3>
<p>A random forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive accuracy and control over-fitting. The sub-sample size is controlled with the max_samples parameter if bootstrap=True (default), otherwise the whole dataset is used to build each tree. </p>


<h3>VOTING CLASSIFIER</h3>
<p>A Voting Classifier is a machine learning model that trains on an ensemble of numerous models and predicts an output (class) based on their highest probability of chosen class as the output. It simply aggregates the findings of each classifier passed into Voting Classifier and predicts the output class based on the highest majority of voting. The idea is instead of creating separate dedicated models and finding the accuracy for each them, we create a single model which trains by these models and predicts output based on their combined majority of voting for each output class.</p>


<h3>ADA BOOST CLASSIFIER</h3>
<p>Ada-boost or Adaptive Boosting is one of ensemble boosting classifier combines multiple classifiers to increase the accuracy of classifiers. AdaBoost is an iterative ensemble method. AdaBoost classifier builds a strong classifier by combining multiple poorly performing classifiers so that you will get high accuracy strong classifier. The basic concept behind Adaboost is to set the weights of classifiers and training the data sample in each iteration such that it ensures the accurate predictions of unusual observations. Any machine learning algorithm can be used as base classifier if it accepts weights on the training set.</p>


<h3>GRADIENT BOOSTING CLASSIFIER</h3>
<p>Gradient Boosting is a powerful boosting algorithm that combines several weak learners into strong learners, in which each new model is trained to minimize the loss function such as mean squared error or cross-entropy of the previous model using gradient descent. In each iteration, the algorithm computes the gradient of the loss function with respect to the predictions of the current ensemble and then trains a new weak model to minimize this gradient. The predictions of the new model are then added to the ensemble, and the process is repeated until a stopping criterion is met.</p>


<h3>STOCHASTIC GRADIENT BOOSTING (SGB) CLASSIFIER</h3>
<p>Gradient boosting is a greedy procedure. New decision trees are added to the model to correct the residual error of the existing model. Each decision tree is created using a greedy search procedure to select split points that best minimize an objective function. This can result in trees that use the same attributes and even the same split points again and again. Bagging is a technique where a collection of decision trees are created, each from a different random subset of rows from the training data. The effect is that better performance is achieved from the ensemble of trees because the randomness in the sample allows slightly different trees to be created, adding variance to the ensembled predictions. Random forest takes this one step further, by allowing the features (columns) to be subsampled when choosing split points, adding further variance to the ensemble of trees. These same techniques can be used in the construction of decision trees in gradient boosting in a variation called stochastic gradient boosting.

</p>


<h3>EXTREAM GRADIENT BOOSTING (XGB) CLASSIFIER</h3>
<p>XGBoost is an optimized distributed gradient boosting library designed for efficient and scalable training of machine learning models. It is an ensemble learning method that combines the predictions of multiple weak models to produce a stronger prediction. XGBoost stands for “Extreme Gradient Boosting” and it has become one of the most popular and widely used machine learning algorithms due to its ability to handle large datasets and its ability to achieve state-of-the-art performance in many machine learning tasks such as classification and regression. One of the key features of XGBoost is its efficient handling of missing values, which allows it to handle real-world data with missing values without requiring significant pre-processing. Additionally, XGBoost has built-in support for parallel processing, making it possible to train models on large datasets in a reasonable amount of time.</p>

<h2>RESULT</h2>

The best models are **Logistic Regression Classifier** and **SGD Classifier** with highest accuracy of **99.41%**.

<h2>SOURCES</h2>

[1] UCI Machine Learning Repository: Center for Machine Learning and Intelligent Systems. Breast cancer wisconsin (diagnostic) data set: wdbc.data. http://archive.ics.uci.edu/ml/ machine-learning-databases/breast-cancer-wisconsin/wpbc.data, 1996.

<BR>



<h2>LICENSE</h2>

You may use this tutorial freely at your own risk. See [**LICENSE**](https://github.com/srushtishimpi/breast_cancer_wisconsin_Analysis/blob/main/LICENSE).

### [**BY SRUSHTI SHIMPI**](https://github.com/srushtishimpi)
