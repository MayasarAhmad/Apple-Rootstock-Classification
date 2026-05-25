# 🍎 Apple Rootstock Classification

An advanced Machine Learning and Deep Learning project for Apple Rootstock Classification using traditional ML algorithms, CNN, and Transfer Learning (MobileNetV2).

---

# 📌 Project Overview

This project focuses on automatic classification of apple rootstock images using image processing, machine learning, and deep learning techniques.

The system compares multiple models including:

- Support Vector Machine (SVM)
- Random Forest
- Convolutional Neural Network (CNN)
- MobileNetV2 Transfer Learning

The best-performing model is selected based on classification accuracy and validation performance.

---

# 🚀 Features

✅ Image preprocessing  
✅ Data augmentation  
✅ Feature extraction using GLCM and LBP  
✅ Machine Learning classification  
✅ CNN implementation  
✅ Transfer Learning with MobileNetV2  
✅ Accuracy and loss visualization  
✅ Performance comparison graph  
✅ CSV result generation  
✅ Ready for deployment in mobile/web applications

---

# 🧠 Models Used

| Model | Type |
|------|------|
| SVM | Machine Learning |
| Random Forest | Machine Learning |
| CNN | Deep Learning |
| MobileNetV2 | Transfer Learning |

---

# 📊 Final Results

| Model | Accuracy |
|------|------|
| SVM | ~22% |
| Random Forest | ~35% |
| CNN | ~86% |
| MobileNetV2 | ~88.54% |

🏆 MobileNetV2 achieved the highest accuracy.

---

# 📂 Project Structure

Apple-Rootstock-Classification/
│
├── Rootstock.ipynb
├── final_results.csv
├── cnn_rootstock_model.h5
├── README.md
│
├── dataset/
│   ├── train/
│   ├── validation/
│   └── test/
│
└── outputs/
    ├── accuracy_graph.png
    ├── loss_graph.png
    └── comparison_chart.png
    
 ⚙️ ##############        Technologies Used
 
Python
Google Colab
OpenCV
NumPy
Pandas
Matplotlib
Scikit-learn
TensorFlow
Keras

🔄 Project Workflow

1️⃣ Data Collection
Apple rootstock images were collected and organized into different categories.

2️⃣ Image Preprocessing
The following preprocessing techniques were applied:
Image resizing
Normalization
CLAHE enhancement
Noise removal

3️⃣ Data Augmentation
To improve model generalization:
Rotation
Flipping
Zooming
Shearing

4️⃣ Feature Extraction
Extracted handcrafted features include:
🔹 GLCM Features
Contrast
Correlation
Energy
Homogeneity
🔹 LBP Features
LBP Mean
LBP Standard Deviation

5️⃣ Machine Learning Models
🔹 Support Vector Machine (SVM)
Used for traditional classification based on handcrafted features.
🔹 Random Forest
Used for ensemble-based classification.

6️⃣ Deep Learning Models
🔹 CNN Model
Custom CNN architecture containing:
Convolution layers
MaxPooling layers
Dropout layers
Dense layers
Softmax output layer
🔹 Transfer Learning
MobileNetV2 pretrained architecture was used for improved feature learning and higher accuracy.

📈 Performance Visualization
The project generates:
Training accuracy graph
Validation accuracy graph
Loss graph
Model comparison chart

💡 Future Scope
Future improvements may include:
Real-time mobile application
Web deployment using Flask/Streamlit
Live camera prediction
Cloud deployment
Larger dataset training
Real-time farmer assistance system

📱 Proposed Application
The final goal is to create a mobile application where users can:
Capture an apple rootstock image
Upload the image
Get instant classification results

This can help:
Farmers
Researchers
Agricultural industries

▶️ Installation Guide
Step 1: Clone Repository
git clone https://github.com/MayasarAhmad/Apple-Rootstock-Classification.git
Step 2: Open Project Folder
cd Apple-Rootstock-Classification
Step 3: Install Required Libraries
pip install tensorflow
pip install keras
pip install opencv-python
pip install scikit-learn
pip install matplotlib
pip install pandas
pip install numpy
Or install all together:
pip install tensorflow keras opencv-python scikit-learn matplotlib pandas numpy

▶️ Running the Project
Open Jupyter Notebook----jupyter notebook
open----Rootstock.ipynb

▶️ Running in Google Colab
Upload the notebook to Google Colab
Upload dataset folders
The trained models are saved using:
model.save("cnn_rootstock_model.h5")

📊 Output Files
Generated outputs include:
Trained model files
Accuracy graphs
Comparison charts
CSV results
Run all cells sequentially

🔥 Key Achievements
✅ Successfully implemented ML and DL models
✅ Achieved high classification accuracy
✅ Compared traditional and deep learning approaches
✅ Implemented transfer learning
✅ Generated visual performance analysis

⭐ Conclusion
This project demonstrates the effectiveness of Deep Learning and Transfer Learning techniques for apple rootstock classification.
Among all implemented models, MobileNetV2 achieved the highest performance and proved more effective compared to traditional machine learning methods.
The project can be extended into a real-world agricultural assistance application for farmers and researchers.

👨‍💻 Author
---------------------------------------------------Mayasar Ahmad Ganie-------------------------------------------------------

https://github.com/MayasarAhmad/Apple-Rootstock-Classification
