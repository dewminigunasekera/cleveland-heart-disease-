# Cleveland Heart Disease Classifier

This notebook uses the Cleveland heart disease dataset to predict the presence of heart disease using a Random Forest classifier with correlation-informed feature selection.

## 🔍 Key Results
- **Recall**: 0.97
- **Accuracy**: 0.87

## 📊 Methodology
- Selected features based on correlation threshold (`|corr| > 0.22`)
- Random Forest classification with 80/20 stratified split
- Custom threshold tuning (`threshold = 0.53`) to optimize recall
- No unnecessary plotting — clean, execution-focused style

## 📁 Files
- `heart_disease_rf_classifier_git_ready.ipynb` – main notebook (cleaned for GitHub)

## ▶️ How to Run
1. Clone this repo
2. Place `heart.csv` in the same directory
3. Open the notebook and run all cells

## 🧠 Notes
- High recall is critical for medical diagnostics — this model prioritizes minimizing false negatives
- Code repeats by design for readability and modular debugging
