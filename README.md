Lung cancer is one of the most common and deadly cancers worldwide — but catching it early can save lives.
In this project, I built a machine learning model that can predict the likelihood of someone having lung cancer based on their medical history, lifestyle habits, and symptoms.

The idea is simple:
Use data → Find patterns → Help raise awareness & guide people toward timely medical checkups.# lung_cancer_prediction
I wanted to answer one main question:

"Given a person’s health details and symptoms, can we predict if they might have lung cancer?"

This meant working with real-world data, understanding the patterns behind symptoms, and choosing the best model that could make accurate predictions.

About the Dataset
309 records, each representing an individual.

16 features in total — things like:

Gender & Age

Smoking habits

Symptoms like coughing, chest pain, yellow fingers, shortness of breath

Medical history (chronic disease, anxiety, allergies)

Target column: LUNG_CANCER (YES / NO)

How I Built It
Here’s the journey from raw data to a working prediction model:

1. Cleaned the data – handled missing values and turned words into numbers so the model could understand them.

2. Explored the data – made visualizations to see which symptoms were more common in patients with lung cancer.

3. Engineered features – focused on the most important attributes for prediction.

4. Tried multiple models – Logistic Regression, Decision Tree, Random Forest, SVM, KNN, etc.

5. Picked the best one – based on accuracy, precision, recall, and F1-score.

    Tools & Tech Used
   Language: Python
   Libraries:pandas, numpy – for data handling matplotlib, seaborn – for visualizations scikit-learn – for building and          testing ML models.



