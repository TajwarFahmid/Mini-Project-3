1. Car Acceptability Classification
Overview: An evaluation project using a hierarchical decision model to classify car acceptability based on price, technical specifications, and safety features.

Exploratory Data Analysis (EDA): Conducted a deep dive into the structural information of the dataset, analyzing the distribution of features like buying price, maintenance costs, and safety ratings.

Feature Encoding: Transformed ordinal categorical variables (e.g., "vhigh", "high", "med", "low") into numerical formats suitable for machine learning algorithms.

Decision Tree Implementation: Developed multiple classification models using DecisionTreeClassifier, comparing the effectiveness of Gini Impurity versus Information Gain (Entropy).

Hyperparameter Tuning & Evaluation: Controlled model complexity using max_depth to prevent overfitting, validating performance through confusion matrices and a comparative analysis of training vs. testing accuracy.

Model Visualization: Leveraged Graphviz to export and visualize the decision-making logic of the tree, providing a clear "white-box" view of how the model prioritizes safety and capacity in its predictions.

Tech Stack: Python, Scikit-learn, Pandas, Graphviz.
