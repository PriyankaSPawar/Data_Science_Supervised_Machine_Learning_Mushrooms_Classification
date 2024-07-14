# Supervised Machine Learning _Classification of Mushrooms
![Wallpaper-showcasing-charming-mushrooms-in-adorable-tiny-hats-to-inject-cuteness-into-your-screen](https://github.com/user-attachments/assets/fbdd9225-c67f-4d64-a861-188f4f40178b)


## DataScience Bootcamp Project 8 (Phase II) : WBS Coding School
Welcome to my eighth project in bootcamp and my fourth project focusing on Machine Learning using Classification models! In this project, I will be predicting whether mushrooms are poisonous or non-poisonous with the goal of achieving the highest accuracy and ensuring safety.

I will use the Mushroom Classification Dataset, which contains categorical attributes describing physical characteristics of mushrooms. These attributes include features like cap shape, cap color, gill size, etc. The dataset is labeled with 'poisonous' or 'edible' classes.

## Goals:
- Develop machine learning models to classify mushrooms as poisonous or non-poisonous.
- Achieve high accuracy while prioritizing safety, aiming to minimize false negatives (misclassifying poisonous mushrooms as non-poisonous).

## Steps involved:

### Data Exploration: 
Understand the structure of the dataset, visualize key features, and check for any missing or inconsistent data.

### Data Preprocessing: 
Encode categorical variables, handle any missing values or outliers, and prepare the data for modeling.

### Model Selection: 
Evaluate different classification algorithms (e.g., KNN, ExtraTrees, LGBM, XGB, Random Forest, etc.) based on performance metrics such as accuracy, precision, recall, and F1-score.

### Model Training and Evaluation: 
Train the selected models on the training set, tune hyperparameters using techniques like cross-validation, and evaluate their performance on the test set using predict_proba().

### Safety Considerations: 
Prioritize model interpretability and analyze feature importance to understand which characteristics contribute most to mushroom toxicity predictions.

## Skills and Tools :
1. Data Reading & Cleaning
2. Data Splitting
3. Building a Preprocessor
4. LazyPredict & Modelling
5. Error Analysis
6. Thresholds and ROC Curve analysis

## Deliverables :
- A colab notebook contains work data of this project found [here](https://github.com/PriyankaSPawar/Data_Science_Supervised_Machine_Learning_Mushrooms_Classification/blob/main/Mushrooms_ML_Classification_Competition.ipynb)
- A Medium article of this project found [here]()

## Reason behind choosing ExtraTrees Classifier:
- Choosing the ExtraTrees Classifier with LazyPredict is ideal for this project due to its robust predictive accuracy and efficiency. The ExtraTrees Classifier excels in handling complex datasets by building multiple decision trees with randomized features, reducing the risk of overfitting and improving generalization. 
- LazyPredict complements this by offering a quick and comprehensive evaluation of various models, allowing you to swiftly identify the most promising classifier for predicting mushroom toxicity accurately and prioritizing safety.
- This approach not only saves time during model selection but also ensures that the chosen model can reliably distinguish between poisonous and non-poisonous mushrooms, aligning with your project's goals effectively.







