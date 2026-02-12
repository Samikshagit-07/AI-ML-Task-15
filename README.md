# AI-ML-Task-15

Project Overview

The objective of this task is to implement an end-to-end Machine Learning pipeline used in real production systems. Using the Breast Cancer Dataset (sklearn), I have built a workflow that automates data preprocessing and model training.

Tools & Technologies

Language: Python Libraries: Pandas, NumPy, Scikit-learn (Pipeline, Column Transformer)

Environment: Google Colab

 Workflow StepsFollowing the provided mini-guide, the following steps were performed:

 Data Loading: Loaded features and target variables from sklearn.
 
 Preprocessing Identification: Identified numerical features for scaling.
 
 Column Transformer: Applied StandardScaler to ensure all features are on a similar scale.
 
 Pipeline Construction: Integrated the preprocessor with a RandomForestClassifier into a single Pipeline object.
 
 Data Splitting: Divided the dataset into training and testing sets.
 
 Training & Prediction: Trained the pipeline on the training set and generated predictions.
 
 Evaluation: Calculated Accuracy, Precision, Recall, and F1-score.
 
 Deliverables notebook.ipynb: The complete Python code and analysis.

 evaluation_metrics.txt: Summary of model performance.

 breast_cancer_pipeline.pkl: The final saved model for deployment.
 
 Key Learnings
 
 Data Leakage: Learned how pipelines prevent information from the test set from "leaking" into the training process.
 
 Production Readiness: Understand why pipelines are superior to manual preprocessing for model deploymen
