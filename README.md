# Income-Prediction
Using Machine Learning

## Introduction
### Objective:  
To construct a predictive model for classifying individuals based on whether their income exceeds $50,000.
### Importance: 
Decision-making in finance, social services, and policy planning.

## Data Overview:
The provided train and test datasets contain various demographic, socio-economic, and employment-related features of individuals. These features include age, gender, education level, marital status, race, employment details, financial information, migration history, family and veteran status, and more. The datasets aim to predict whether an individual's income exceeds a specified threshold based on these attributes.

## Model Building:
1. Utilized Random Forest Classifier for model construction.
2. Preprocessed training data by handling missing values and encoding categorical variables.
3. Trained the classifier using 100 decision trees.
4. Evaluated model performance using accuracy, precision, recall, and F1 score metrics.
5. Made predictions on the test data using the trained model.
6. Saved the predictions for further analysis and evaluation.

## Insights:
1. Males show lower income thresholds below the set limit compared to females.
2. Males surpass females in income thresholds above the established limit.
3. Non-white demographics exhibit higher income thresholds below the set standard compared to white counterparts.
4. Whites demonstrate the lowest income threshold below the established standard.
5. Individuals outside the labor force display the highest income threshold below the designated benchmark.
6. The age range of 40 to 50 shows the highest income thresholds exceeding the specified limit.

## Evaluation metrics:
| Metric             | Value   |
|--------------------|---------|
| Training Accuracy  | 0.99  |
| Training Precision | 0.99  |
| Training Recall    | 1.0     |
| Training F1 Score  | 0.99   |


## Future Scope:
### Finance:-
Personalized financial products, risk assessment, and investment strategies tailored to individuals' income levels.

### Social Services:-
Optimizes resource allocation, targeting aid and support programs effectively to uplift socio-economically disadvantaged populations.

### Policy Planning:-
Informs evidence-based policymaking, facilitating socioeconomic development, poverty alleviation, and equitable resource distribution.




