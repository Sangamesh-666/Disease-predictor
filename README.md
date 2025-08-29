# Heart Disease Prediction

## Project Goal

Predict if a person has heart disease using health data and machine learning.

## Dataset

* Source: Kaggle (Heart Disease dataset)
* Rows: \~300 patients
* Features include:

  * Age
  * Sex
  * Chest pain type
  * Resting blood pressure
  * Cholesterol
  * Fasting blood sugar
  * Resting ECG results
  * Maximum heart rate
  * Exercise induced angina
  * Oldpeak (ST depression)
  * Slope of ST segment
  * Number of major vessels
  * Thalassemia
* Target:

  * 0 = No heart disease
  * 1 = Heart disease present

## Project Steps

1. **Setup**

   * Upload `kaggle.json` to access the dataset.
   * Install required Python libraries.

2. **Load Data**

   * Import dataset from Kaggle.
   * Check missing values.
   * Explore data with charts and statistics.

3. **Preprocessing**

   * Encode categorical features.
   * Normalize/scale numerical data.
   * Split into train and test sets.

4. **Model Training**

   * Logistic Regression
   * Decision Tree
   * Random Forest
   * Support Vector Machine (SVM)
   * Compare model performance.

5. **Evaluation**

   * Accuracy
   * Precision
   * Recall
   * F1-score
   * Confusion matrix

6. **Prediction**

   * Input new patient data.
   * Model predicts if heart disease is present.

## Requirements

Install Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn kaggle
```

## Usage

1. Clone or download this project.
2. Add your `kaggle.json` in the working folder.
3. Run the notebook `DISEASE_PREDICTOR_BOOT_CAMP.ipynb` step by step.
4. Compare results of models.
5. Use the prediction function to test custom patient data.

## Output Examples

* Correlation heatmap of health features.
* Accuracy scores of different ML models.
* Confusion matrices to check classification quality.
* Final prediction:

  ```
  Input: [Age=52, Cholesterol=220, MaxHR=160, ...]
  Output: Heart Disease = Yes
  ```

---

Do you want me to also **add a sample section with exact Python code snippets** (like how to run prediction with a new patient’s data), or keep it only as text instructions?
