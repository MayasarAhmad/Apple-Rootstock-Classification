# Apple-Rootstock-Classification
Apple-Rootstock-Classification using Machine Learning, CNN and Transfer Learning
📌 Project Overview

This project focuses on the classification of apple rootstock images using different Machine Learning and Deep Learning techniques. The system compares traditional machine learning algorithms with deep learning approaches to identify the best-performing model for apple rootstock classification.

The project includes:

Image preprocessing
Data augmentation
Feature extraction
Machine Learning models
CNN model
Transfer Learning using MobileNetV2
Performance comparison
🎯 Objectives
To classify apple rootstock images accurately.
To compare traditional machine learning models with deep learning models.
To improve classification performance using transfer learning.
To develop a foundation for a real-time mobile/web application.
🛠️ Technologies Used
Python
Google Colab
OpenCV
NumPy
Pandas
Matplotlib
Scikit-learn
TensorFlow
Keras
📂 Dataset

The dataset contains apple rootstock images divided into multiple classes.

Dataset structure:

dataset/
 ├── train/
 ├── test/
 └── validation/
🔄 Project Workflow
1. Data Collection

Apple rootstock images were collected and organized into different classes.

2. Image Preprocessing

The following preprocessing techniques were applied:

Image resizing
Normalization
CLAHE enhancement
Noise removal
3. Data Augmentation

To increase dataset diversity:

Rotation
Flipping
Zooming
Shearing
4. Feature Extraction

Handcrafted features extracted include:

Contrast
Correlation
Energy
Homogeneity
LBP Mean
LBP Standard Deviation
5. Machine Learning Models

The following models were implemented:

Support Vector Machine (SVM)
Random Forest
6. Deep Learning Models

Implemented models:

Convolutional Neural Network (CNN)
MobileNetV2 Transfer Learning
🧠 CNN Architecture

The CNN model contains:

Convolution layers
MaxPooling layers
Dropout layers
Dense layers
Softmax output layer

🚀 Transfer Learning
MobileNetV2 pretrained architecture was used for transfer learning to improve classification accuracy and reduce training time.

| Model         | Accuracy |
| ------------- | -------- |
| SVM           | ~22%     |
| Random Forest | ~35%     |
| CNN           | ~86%     |
| MobileNetV2   | ~88%     |

📈 Performance Comparison

The project includes graphical comparison of:

Accuracy
Loss
Validation accuracy
Model comparison charts

▶️ How to Run
Clone Repository
git clone https://github.com/MayasarAhmad/Apple-Rootstock-Classification.git
Install Dependencies
pip install -r requirements.txt
Run Notebook

Open:

Rootstock.ipynb

in Google Colab or Jupyter Notebook.

📌 Author

Mayasar Ahmad
Postgraduate in Artificial Intelligence
⭐ Conclusion

This project successfully demonstrates the effectiveness of deep learning and transfer learning techniques for apple rootstock classification. MobileNetV2 achieved the highest accuracy and proved more efficient compared to traditional machine learning models.
