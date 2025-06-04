# Titanic_Survival_prediction

##  Decision Tree & Random Forest on Titanic Dataset

**📄 File:** `DT_RF_Titanic.ipynb`

### **Objective**
Predict passenger survival on the Titanic using tree-based classifiers.

### **Dataset**
- Titanic Dataset from Kaggle
- Features used:
  - `Pclass`, `Sex`, `Age`, `Fare`, `Embarked`
- Irrelevant features removed:
  - `Name`, `Cabin`, `Ticket`

### **Workflow**
- Clean missing values in `Age`, `Embarked`
- Encode categorical features
- Train:
  - `DecisionTreeClassifier`
  - `RandomForestClassifier`
- Evaluate with:
  - Accuracy Score
  - Confusion Matrix

### **Comparison**
- Random Forest typically offers higher accuracy and robustness due to ensemble learning.
