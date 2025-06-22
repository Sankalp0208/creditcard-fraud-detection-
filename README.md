# creditcard-fraud-detection

## <h2>🔍 Key Steps</h2><br>

### 1. **Data Preprocessing**<br>
- Handled class imbalance using undersampling or oversampling techniques (e.g., SMOTE).<br>
- Standardized `Amount` and `Time` features.<br>

### 2. **EDA (Exploratory Data Analysis)**<br>
- Visualized fraud vs. genuine transactions.<br>
- Used correlation heatmaps and count plots.<br>

### 3. **Model Building**<br>
- Applied multiple models:<br>
  - Logistic Regression<br>
  - Random Forest Classifier<br>
  - XGBoost<br>
- Evaluated using:<br>
  - Accuracy, Precision, Recall, F1-Score, ROC-AUC<br>

### 4. **Model Deployment**<br>
- Deployed the project using **Streamlit**:<br>
  - Web interface to view data<br>
  - Run predictions on new data<br>
  - Visualize fraud detection results<br>
