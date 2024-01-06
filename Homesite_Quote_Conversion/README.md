# Homesite Quote Conversion
Predict the likelihood of a customer purchasing an insurance plan in this Kaggle competition. Explore innovative techniques such as SMOTE for imbalanced data and ensemble predictions through stacking to refine your 
machine learning skills and boost predictive modeling expertise.

# Introduction
In this advanced machine learning assignment, we delve into innovative techniques for addressing real-world challenges. Emphasis is placed on handling imbalanced data using SMOTE and implementing ensemble predictions 
through stacking. As we immerse ourselves in a Kaggle competition focused on Homesite Quote Conversion, the exploration includes harnessing the power of various classification methods and navigating preprocessed 
datasets. Join us on this journey to refine your machine learning skills and elevate your expertise in predictive modeling.

# Objective
1. Apply the Synthetic Minority Over-sampling Technique (SMOTE) and variations to handle imbalanced data, boosting accuracy in predicting the minority class.
2. Utilize stacking techniques to combine predictions from diverse classifiers, including Decision Trees, Random Forest, Support Vector Machines, Multilayer Perceptron, and K-Nearest Neighbors, aiming for an enhanced
overall predictive model.
3. Engage in the Homesite Quote Conversion Kaggle competition, using preprocessed datasets and Scikit Learn classification methods to predict the probability of customer insurance plan purchases.
4. Experiment with varying percentages of SMOTE to improve accuracy in predicting the minority class, focusing on effective handling of imbalanced datasets.
5. Execute one-layer stacking by combining predictions from Decision Trees, Random Forest, Support Vector Machines, Multilayer Perceptron, and K-Nearest Neighbors, exploring different combinations for optimal performance.
6. Optionally conduct hyperparameter tuning for the stacked model, optimizing parameters for enhanced overall performance.

# Python Packages Used
1. vecstack
2. pandas
3. numpy
4. plotly.express
5. accuracy_score, classification_report, confusion_matrix, roc_auc_score from sklearn.metrics
6. train_test_split, GridSearchCV, RandomizedSearchCV, cross_val_score from sklearn.model_selection
7. RandomForestClassifier, GradientBoostingClassifier from sklearn.ensemble
8. DecisionTreeClassifier from sklearn.tree
9. MLPClassifier from sklearn.neural_network
10. SMOTE from imblearn.over_sampling
11. OneHotEncoder from sklearn.preprocessing

# Dataset
The dataset for this project revolves around the Homesite Quote Conversion Kaggle competition. It is a binary classification challenge focused on predicting the probability of a customer purchasing a quoted 
insurance plan. The competition, which concluded seven years ago, offers a comprehensive set of preprocessed datasets. These datasets have undergone necessary treatments such as the removal of columns with 
abundant missing values and imputation for select missing values. To access and explore the dataset, you can visit [the Homesite Quote Conversion Kaggle competition](https://drive.google.com/drive/folders/10b00DLBT8pxkQIdOi9xch42KwEySoszQ?usp=sharing). The provided preprocessed datasets include 
training and testing sets in CSV format, offering a foundation for implementing advanced machine learning techniques.

# Result
The project's outcome encompasses refined predictive models, leveraging advanced techniques like SMOTE for imbalanced data and ensemble predictions through stacking. Achieve enhanced accuracy and effectiveness 
in predicting insurance plan purchases, demonstrated by comprehensive metrics, including classification reports, confusion matrices, and ROC-AUC scores. The refined models, validated through cross-validation, 
showcase improved performance in the Kaggle competition, with submission-ready predictions that contribute to a nuanced understanding of the Homesite Quote Conversion challenge.

![Screenshot 2024-01-06 123904](https://github.com/harshalgajera043/Machine-Learning/assets/83157209/2b837dba-c457-4f27-b829-c049f58c9418)

