# decision-trees-and-random-forests

🔍 Steps Performed

1. Data Preprocessing
Loaded the dataset using pandas.read_csv()

Handled missing values (if any)

Split data into features X and label y

Encoded categorical features if present

Split dataset into training and test sets (70/30 split)

2. Decision Tree Classifier
Trained a DecisionTreeClassifier on the training data.

Visualized the tree using plot_tree() with node information.

Evaluated accuracy on both train and test sets.

Checked for overfitting and controlled tree depth using max_depth.

3. Random Forest Classifier
Trained a RandomForestClassifier with 100 trees.

Compared accuracy with Decision Tree results.

Analyzed feature importance to interpret which features impact prediction most.

4. Cross-Validation
Applied 5-fold cross-validation to the Random Forest model.

Measured and printed the mean accuracy to assess performance consistency.

📊 Outputs
Accuracy scores for both Decision Tree and Random Forest

Decision Tree visualization

Feature Importance plot

Cross-validation scores

✅ Outcome
You will understand:

How to build and tune Decision Trees and Random Forests

When overfitting occurs and how to handle it

How ensemble models like Random Forest improve accuracy

How to interpret which features matter the most

