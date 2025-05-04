# Brain-Tumor-Classification

Brain Tumor Classification Using EfficientNet B3 🧠🔬
This project focuses on detecting and classifying brain tumors using deep learning techniques, specifically leveraging the EfficientNet B3 architecture. The aim is to assist radiologists and medical professionals by automating the tumor detection process from MRI scans, increasing diagnostic speed and accuracy.

📌 Overview
Brain tumors are a critical health concern, and timely detection is essential. This project builds an image classification model using the EfficientNet B3 architecture to classify MRI images into four categories:

Glioma

Meningioma

Pituitary tumor

No tumor (normal)

The model achieves 99% training accuracy and 98% validation accuracy, demonstrating high performance in tumor classification.

🧠 Model Architecture
EfficientNet B3: Chosen for its superior performance and parameter efficiency.

Transfer Learning: Used a pre-trained model fine-tuned on a custom dataset.

Augmentation: Applied techniques such as rotation, flipping, and zooming to prevent overfitting.

Optimizer: Adam

Loss Function: Categorical Crossentropy

🧪 Features
High-accuracy tumor classification from MRI scans

Grad-CAM implementation for model explainability

Clean, modular Python code structure

Streamlit and Flask-based deployment options

🗂 Dataset
The model was trained on a publicly available MRI brain tumor dataset consisting of thousands of labeled images across four categories.

📈 Evaluation
Accuracy: 98% (validation)

Precision, Recall, F1-score: Evaluated using a classification report

Confusion Matrix: Provided for visual interpretation of predictions

🚀 Deployment
The trained model is deployed using:

Flask: Backend service for API-based inference

Streamlit: User-friendly frontend interface for image upload and tumor prediction

🔍 Explainability
To build trust and interpretability, the project includes:

Grad-CAM Heatmaps to highlight image regions influencing model decisions.

🛠️ Tech Stack
Python, TensorFlow, Keras

EfficientNet B3

OpenCV, NumPy, Matplotlib

Streamlit, Flask

📌 Future Work
Real-time inference from webcam feeds

Mobile deployment using TensorFlow Lite

Integration with hospital information systems (HIS)

🙌 Contributors
Jan Saida Shaik – Model development, evaluation, deployment
