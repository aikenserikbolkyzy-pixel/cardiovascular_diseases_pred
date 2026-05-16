# CardioPredict AI 🫀

CardioPredict AI is a full-stack web application designed to analyze cardiovascular health data and predict heart disease risk using state-of-the-art ensemble learning techniques. This project bridges rigorous medical research with an interactive web interface for both patients and clinicians.

## 🔬 Research & Analysis
The core logic of this application is based on an extensive analysis of a dataset containing 70,000 patient records. The research explored multiple machine learning architectures, including:
- **Linear Models**: Logistic Regression
- **Instance-based**: K-Nearest Neighbors (KNN)
- **Ensemble Methods**: Random Forest, AdaBoost, Gradient Boosting
- **High-Performance GBDT**: XGBoost, LightGBM, and **CatBoost** (Best Performer)

### Key Research Findings
- **Dominant Predictors**: Age, Systolic Blood Pressure (`ap_hi`), and BMI were identified as the strongest indicators of cardiovascular risk.
- **Model Performance**: CatBoost achieved the highest ROC-AUC of **0.804** and accuracy of **~73.6%**, demonstrating superior handling of categorical medical variables like cholesterol and glucose levels.
- **Data Insights**: Clear correlations were observed between physical inactivity, high cholesterol, and increased disease prevalence.

## 🚀 Features
- **Interactive EDA Dashboard**: Visualized datasets showing distributions, correlations, and feature importance.
- **Risk Predictor Interface**: Users can input health metrics (BP, weight, lifestyle) to get a real-time risk assessment.
- **AI Health Insights**: Powered by **Gemini AI**, providing personalized explanations and health tips based on prediction results.
- **Modern UI/UX**: Built with React, Tailwind CSS, and Framer Motion for a fluid, accessible experience.
*Disclaimer: This tool is for educational and research purposes only. Always consult a medical professional for health-related decisions.*
