🌾 Crop Recommendation System:
This project uses machine learning to recommend the best crop to grow based on soil and weather conditions like Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, and Rainfall.
📁 Files Included:
Crop_recommendation.csv – Dataset used for model training
crop_recommendation_model.joblib– Trained RandomForest model
label_encoder.joblib – Label encoder used to convert crop names to numeric form
🧠 ML Algorithm:
RandomForestClassifier
Chosen for its high accuracy and performance in this project.
⚙️ Steps Covered:
Data loading and exploration
Data preprocessing
Label encoding of target (crop) column
Train-test split
Model training
Evaluation using classification report
Model saving using joblib
Prediction for unknown input
🧪 Sample Prediction:
sample_input = np.array([[90, 42, 43, 20.5, 80, 6.5, 200]])
prediction = model.predict(sample_input)
print("Recommended Crop:", prediction[0])
📌 Libraries Used:
pandas
numpy
scikit-learn
seaborn
matplotlib
joblib
✅ Accuracy:
Achieved 99% accuracy on test data using RandomForestClassifier.
