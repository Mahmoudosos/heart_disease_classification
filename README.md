# heart_disease_classification
This project explores whether machine learning models can predict the presence of heart disease based on patient health records. The dataset includes features such as age, cholesterol level, blood pressure, chest pain type, and maximum heart rate.

The project covers the full data science workflow: data cleaning, exploratory data analysis, visualization, model training, and evaluation.

## Key Highlights

- Worked with more than 300 patient records from the UCI Heart Disease dataset.

- Explored relationships between risk factors (age, cholesterol, chest pain type) and disease outcome.

- Built and compared several classification models: Logistic Regression, Random Forest, Support Vector Machine (SVM), and K-Nearest Neighbors (KNN).

- Achieved the best performance with KNN, reaching 90% accuracy.

- Produced visualizations that explain patterns and model results clearly.


## Tools and Libraries

- Python (pandas, numpy)

- Data visualization: matplotlib, seaborn

- Machine learning: scikit-learn

## Exploratory Data Analysis

Some key findings from the data:

- Heart disease appeared more frequently in men compared to women in this dataset.

- Patients with higher maximum heart rates were less likely to have the disease.

- Certain types of chest pain were strongly associated with the presence of heart disease.

## Model performance
| Model                | Accuracy | Precision | Recall | F1-score |
| -------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression  | 85%      | 0.84      | 0.87   | 0.85     |
| Random Forest        | 88%      | 0.87      | 0.89   | 0.88     |
| SVM                  | 86%      | 0.85      | 0.86   | 0.85     |
| **KNN (best model)** | **90%**  | 0.89      | 0.91   | 0.90     |


## Conclusion and Next Steps

The KNN model achieved the highest accuracy (90%).

With further tuning and additional data, results may improve.

Next steps could include:

- Hyperparameter optimization

- Feature engineering (e.g., combining or transforming predictors)

- Testing advanced models such as XGBoost or Gradient Boosting

- Building a simple deployment app (Flask/Streamlit)


