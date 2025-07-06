# Crop-Disease-Detection


🍂 Crop Disease Classifier: 
---------------------------
A deep learning–based image classifier that detects plant leaf diseases from images of crops. Currently implemented for tomato diseases with multiple classes (e.g., early blight, late blight, leaf mold, healthy). Enables early detection of crop diseases, reducing losses and improving crop health.

🛠 Key Features:

Uses transfer learning with MobileNetV2 for efficient training on small datasets.

Classifies images of tomato leaves into healthy or diseased categories.

Supports fine-tuning for improved accuracy.

Processes unseen images for real-time predictions.

Dataset split script included to automatically create train/test folders.

🔗 Technologies Used:

Python

TensorFlow & Keras

ImageDataGenerator for augmentation

Jupyter Notebook / Colab

🌱 Crop Recommendation System: 
-----------------------------
A machine learning model that recommends the most suitable crop for cultivation based on soil nutrient levels (NPK), temperature, and humidity. Built using a Random Forest classifier trained on agricultural datasets, it helps farmers make data-driven decisions to maximize yield and sustainability.

🛠 Key Features:

Inputs: soil Nitrogen (N), Phosphorus (P), Potassium (K), temperature, humidity.

Predicts the best crop to plant in given soil and weather conditions.

Trained on real-world crop recommendation datasets.

Includes model saving with joblib for easy deployment.

Can be integrated into web or mobile applications.

🔗 Technologies Used:

Python

Pandas & scikit-learn

Random Forest Classifier

Jupyter Notebook / Colab
