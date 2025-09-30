1. Dataset

The dataset H1.csv contains booking information such as:

• Lead time
• Number of guests
• Special requests
• Deposit type
• Customer type
• And other reservation details

---

2. Preprocessing

• Dropped irrelevant columns (e.g., ReservationStatus)
• Handled missing values
• Encoded categorical features
• Scaled/normalized data (if applicable)
• Models Implement

---

3. classification models were trained and evaluated:

• Logistic Regression
• Baseline model
• Accuracy: ~76.65% (train), 77.24% (test)

• Decision Tree Classifier
• Handles non-linear relationships
• Accuracy: ~80.27% (train), 80.25% (test)

• Random Forest Classifier
• Ensemble method, reduces overfitting
• Accuracy: ~83% (train & test)

---

4. Libraries Used
   • Pandas, NumPy → Data manipulation
   • Matplotlib, Seaborn → Visualization
   • Scikit-learn → ML models and preprocessing

---

5. Summary

Random Forest Classifier performed best, achieving 83% accuracy.
Logistic Regression provided a simple and interpretable baseline.
Decision Tree achieved competitive results but may overfit if not tuned.
The project shows that ensemble models like Random Forests are more reliable in predicting hotel booking cancellations compared to simpler models.
