# Heart Disease Prediction using Random Forest

This project predicts the likelihood of heart disease based on patient health parameters using a **Random Forest Classifier**.

## 📌 About the Project
Heart disease is one of the leading causes of death worldwide. Early detection can save lives. 
This notebook uses the `heart.csv` dataset to build a machine learning model that classifies whether a person is at risk of heart disease or not.

## 📊 Dataset
The dataset `heart.csv` contains patient records with the following columns:
- **Age**: Age of the patient
- **Sex**: M = Male, F = Female
- **ChestPainType**: ATA, NAP, ASY, TA
- **RestingBP**: Resting blood pressure
- **Cholesterol**: Serum cholesterol level
- **FastingBS**: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- **RestingECG**: Resting electrocardiogram results
- **MaxHR**: Maximum heart rate achieved
- **... and other features**

## 🛠️ Technologies Used
- **Python 3**
- **Libraries**: 
    - `numpy`, `pandas` - Data handling
    - `seaborn`, `matplotlib` - Data visualization
    - `scikit-learn` - ML model, preprocessing, evaluation
        - `RandomForestClassifier`
        - `LabelEncoder`
        - `train_test_split`
        - `confusion_matrix`, `accuracy_score`, `classification_report`

## ⚙️ How to Run
1. Clone this repository
   ```bash
   git clone <your-repo-link>
