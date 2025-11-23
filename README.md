

\---

\#\# 🧪 Features & Methods

\#\#\# ✔ 1\. Exploratory Data Analysis (EDA)

\- Dataset summary  

\- Class imbalance visualization  

\- Key feature distributions (planet radius, period, temperature)  

\- Correlation heatmaps


\---

\#\#\# ✔ 2\. Preprocessing

\- Dropping non-useful columns (IDs, names)

\- Encoding \`koi\_disposition\`

\- Handling missing values (median imputation)

\- Train-test split (80/20)

\---

\#\#\# ✔ 3\. Model: XGBoost Classifier

Achieved \*\*93% accuracy\*\* with:

\- confusion matrix  

\- classification report  

\- feature importance ranking


XGBoost handles noisy, complex astronomical features extremely well.

\---

\#\#\# ✔ 4\. Anomaly Detection (Isolation Forest)

Isolation Forest was used to detect unusual KOIs.

Outputs include:

\- anomaly labels (\`-1\` \= anomaly)

\- PCA visualization of anomalies vs normal points

\- anomaly distribution count

This helps highlight \*\*rare\*\* or \*\*suspicious\*\* observational data.

\---

\#\# 📊 Results

\- \*\*XGBoost Accuracy:\*\* \~93%

\- Clear distinction between confirmed planets and false positives

\- PCA shows meaningful 2D clusters

\- Isolation Forest flags a small percentage of KOIs as anomalies  

  (potential instrument noise or rare planetary systems)

\---

\#\# 🛠 Technologies Used

\- Python  

\- Pandas / NumPy  

\- Scikit-Learn  

\- XGBoost  

\- Matplotlib / Seaborn


\---

\#\#  Future Improvements

\- Add t-SNE visualization for better cluster separation  

\- Hyperparameter tuning for 95–97% accuracy  

\- Add SHAP values for explainability  

\- Try LightGBM or CatBoost for performance comparison


\---

\#\#  Acknowledgements

Dataset from \*\*NASA Exoplanet Archive (Kepler Mission)\*\*  

https://exoplanetarchive.ipac.caltech.edu/

\---

\#\# ⭐ If You Like This Project

Give the repo a \*\*star\*\* 🌟 on GitHub — it helps a lot\!

