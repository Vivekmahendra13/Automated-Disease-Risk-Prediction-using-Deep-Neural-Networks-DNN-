# Automated-Disease-Risk-Prediction-using-Deep-Neural-Networks-DNN-

1. Objective
	•	Predict the risk of diseases such as Heart Disease, Kidney Disease, and Diabetes.
	•	Enable early detection and preventive care using automated predictions.

 2. Model Type
	•	Uses Deep Neural Networks (DNN) for learning complex relationships in medical data.
	•	Multilayered architecture with input, hidden, and output layers.

3. Input Features
	•	Heart Disease: age, cholesterol, blood pressure, chest pain type, ECG, heart rate, etc.
	•	Kidney Disease: blood urea, serum creatinine, sodium, potassium, RBC count, etc.
	•	Diabetes: glucose level, BMI, insulin, age, blood pressure, skin thickness, etc.

 4. Preprocessing
	•	Handling missing data and outliers.
	•	Scaling features using MinMaxScaler or StandardScaler.
	•	Encoding categorical variables if present.

 5. Training and Validation
	•	Train/test split for model evaluation.
	•	Use of binary cross-entropy loss for classification.
	•	ReLU activation in hidden layers and sigmoid in the output layer.

 6. Output
	•	Disease risk percentage (0–100%).
	•	Binary prediction: “At Risk” vs “Healthy”.

7. Explainability
	•	Integrated SHAP plots to explain model decisions and feature importance.

8. Evaluation Metrics
	•	Accuracy, Precision, Recall, F1-Score, AUC-ROC for robust evaluation.

9. Deployment
	•	Deployed using Streamlit for real-time predictions.
	•	User-friendly UI with medical feature explanations.

10. Recommendations
	•	Preventive care tips if moderate or high risk.
	•	Lifestyle and treatment suggestions if diagnosed.
