# Fraud Detection System Using Random Forest

This project is a **machine learning pipeline** to detect fraudulent transactions based on user behavior and transaction patterns. It uses **Python**, **pandas**, and **scikit-learn**, with practical **feature engineering** and a reusable saved model.

---

## Key Features =>

- **Real-world inspired features**
  - Flags for unusually high amounts
  - Checks for transactions at unusual hours
  - Frequency spikes within 24 hours
  - Device, location, and payment method indicators

- **Model**
  - Random Forest Classifier with `class_weight='balanced'` for imbalanced fraud data
  - Evaluated using precision, recall, F1-score, ROC and PR curves

- **Final output**
  - Saved model file (`.joblib`) ready for reuse
  - Visualizations for feature importance and performance

---

## Files Included =>

- `fraud_detection_notebook.ipynb` — Full data prep, feature engineering, training, and evaluation
- `fraud_detection_model.joblib` — Final trained Random Forest model
- `README.md` — Project summary and instructions
- `requirements.txt` — Core dependencies to reproduce results

---
Built with ❤️ using Python and scikit-learn.

Feel free to fork or contribute!
