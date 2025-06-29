
---

##  Dataset

- **Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
- **Target**: Outcome (0 = Non-diabetic, 1 = Diabetic)
- **Shape**: 768 rows × 9 columns

---

##  Steps Performed

1. **Data Loading** using pandas
2. **Basic EDA**: 
   - `.head()`, `.shape`, `.describe()`, `.value_counts()`
3. **Group analysis** with `.groupby('Outcome').mean()`
4. **Feature and label separation**
5. **Feature scaling** using `StandardScaler`
6. **Train-Test split** using `train_test_split()` with stratification
7. **Model Training**:
   - SVM Classifier (`sklearn.svm.SVC` with `kernel='linear'`)
8. **Evaluation**:
   - Accuracy on training and test sets
   - Test Accuracy: ~77.2%
9. **Prediction system**:
   - Accepts user input and predicts diabetes outcome

---

##  Model Performance

- **Training Accuracy**: 78.6%
- **Test Accuracy**: 77.2%
- The model performs binary classification reliably with scaled data and SVM.

---
##  How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/PragnyasuSethi/Diabetes_Prediction.git
   cd DiabetesPredicti
