### Credit-Card-Fraud-2
This is an introductory project that focuses on detecting fraudulent credit card transactions using machine learning models. This approach attempts to rebalance dataset as well as apply different scaling methods to improve the accuracy of different machine learning models.

#### Data Preprocessing
A general overview of data was attained initially, further broken. Checked for missing values, duplicates, corrected data types and rebalanced the dataset. Rebalancing was done by taking sub-samplign the non-fraudlent data and resampling fraud data into a single dataset. Some consideration was made on whether normalization or standardization would be. In the end, I made use of standard scaling and min-max scaling provided by scikit-learn to determine what would best improve the accuracy of the machine learning models. Data was then broken into a 80/20 training to test data split.

#### Machine Learning Algorithm Selection
Five machine learning algorithms were tested, that being logistic regression, KNNeighbours classifier, random forest, XGBoost and a neural network. Logistic regression, KNNeighbours classifier, random forest and XGboost were all implemented using scikit-learn. The neural network was implemented using a bottleneck architecture through PyTorch.

#### Evaluation
Model performance was determined using accuracy scores from training and test sets. The two best performing models are shown below as well as some insight into best performing neural network I could attain from experimentation.

- KNNeighboursClassifier - Training: 97.59%, Test: 98.98%
- Random Forest - Training: 97.59%, Test: 98.48%
- Neural Network - Training: 99.98%, Test: 94.45%

#### Further Investigation
Especially regarding the repetitive nature of searching for optimal parameters for different models, particularly for the optimal number of neurons and layers within the neural network, a future project. I would also like to use this project to expand further to working with APIs and less "routine" datasets provided on Kaggle.
