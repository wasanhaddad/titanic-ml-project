# Titanic - Machine Learning Project 🚢

This project predicts passenger survival on the Titanic dataset using Machine Learning models.  
It is based on the Kaggle competition **"Titanic: Machine Learning from Disaster"**.

---

##  Dataset

This project uses data from the Kaggle competition:

🔗 https://www.kaggle.com/competitions/titanic

---

##  Project Structure
- `notebook.ipynb` — Main Jupyter notebook with all steps
- `submission.csv` — Final predictions submitted to Kaggle
- `README.md` — Project documentation

---

##  Data Preprocessing
The following steps were applied:
- Dropped irrelevant columns (`Name`, `Ticket`, `Cabin`)
- Extracted `Title` from passenger names
- Created new features:
  - `FamilySize`
  - `IsAlone`
  - `Deck`
  - `AgeGroup`
  - `FareBand`
- Filled missing values
- Categorical encoding using:
  - Label Encoding (binary)
  - One-Hot Encoding (multi-categorical)
- Train/Validation split

---

##  Models Used
Two models were trained and evaluated:
1. **Logistic Regression**
2. **Random Forest Classifier**

The best performing model was used to generate the final predictions.

---

##  Evaluation
Metrics evaluated:
- Accuracy
- Confusion Matrix
- Classification Report

Validation accuracy achieved:
> ~0.84 (Logistic Regression)

---

##  Submission
The final `submission.csv` file was generated using the best model and submitted to Kaggle.

---

##  Technologies Used
- Python
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib / Seaborn

---

##  Future Improvements
- Hyperparameter tuning
- Using Gradient Boosting models
- Cross-validation
- Try more advanced feature engineering

---

##  Author
Wasan 😊
