# Potato-plant-disease-detection
Potato plant disease detection using CNN involves training a deep learning model on leaf images to classify diseases like Early Blight and Late Blight. The CNN extracts features, learns patterns, and predicts disease types with high accuracy, aiding farmers in early diagnosis and crop protection.

CNN-Based Potato Disease Detection
🔍 Objective
To automatically detect and classify potato leaf diseases—primarily Early Blight and Late Blight—using images and Convolutional Neural Networks (CNNs). These diseases are caused by Alternaria solani and Phytophthora infestans, respectively, and can severely impact crop yield if not identified early 3.

🧠 CNN Model Architecture
A typical CNN model for potato disease detection includes:

Input Layer: Accepts leaf images (e.g., 224×224 RGB).
Convolutional Layers: Extract features like texture, color, and lesion patterns.
Pooling Layers: Reduce spatial dimensions and retain key features.
Dropout Layers: Prevent overfitting.
Fully Connected Layers: Interpret features for classification.
Output Layer: Uses Softmax to classify into:
Healthy
Early Blight
Late Blight

 Training & Evaluation
 
Dataset: Uses the PlantVillage dataset, which includes labeled potato leaf images.
Augmentation: Rotation, flipping, zooming to improve generalization.
Optimizer: Adam
Loss Function: Categorical Cross-Entropy
Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix
Deployment
Frameworks: TensorFlow, TensorFlow Lite for mobile optimization 3
Frontend: React Native for user-friendly mobile apps
Functionality:
Upload or capture leaf image
Get disease prediction
Receive control recommendations (e.g., fungicide use, organic treatments)

