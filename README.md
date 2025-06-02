# Task 5: Decision Trees & Random Forests

## Objective
Implement tree-based models for heart disease classification.

## Key Steps
1. **Data Preprocessing**:  
   - Handled missing values with median imputation  
   - Converted target to binary classification  

2. **Models Implemented**:  
   - Decision Tree (Base and Pruned)  
   - Random Forest (100 estimators)  

3. **Evaluation**:  
   - Decision Tree Accuracy: 75% → 80% (after pruning)  
   - Random Forest Accuracy: 85% (ROC-AUC: 0.89)  
   - 5-Fold CV Scores: 0.81 ± 0.04  

4. **Visualizations**:  
   - Decision Tree Structure  
   - Feature Importance Plot  
   - Cross-Validation Scores  

## How to Run
```bash
git clone https://github.com/ShubhangGandhi/AI-ML-Internship-Task5.git
cd AI-ML-Internship-Task5
pip install -r requirements.txt
jupyter notebook notebooks/decision_trees.ipynb
