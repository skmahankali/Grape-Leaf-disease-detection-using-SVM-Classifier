# 🍇 Grape Leaf Disease Detection Using SVM Classifier

## 📌 Project Overview
This project focuses on **early detection of grape leaf diseases** using **image processing and machine learning techniques**. The main goal is to assist farmers in diagnosing grape leaf infections to minimize crop loss and enhance yield.

### 🌱 Why It Matters?
- **India is one of the top grape producers** but loses **10-30% of crops** due to diseases.
- Traditional disease detection is **manual, slow, and error-prone**.
- This system uses **digital image processing** and **machine learning** to **automate detection**, reducing dependency on expert farmers.

---

## 🏗️ Project Workflow
### 🔹 Step 1: Image Acquisition
- Leaf images are **captured** using a camera and stored in **JPEG format**.
- The leaf is placed against a **black background** to improve segmentation.

### 🔹 Step 2: Image Preprocessing
- **Noise removal** using **Gaussian filters**.
- **Color transformation** (RGB → HSV) to enhance diseased regions.
- **Histogram Equalization** for contrast improvement.

### 🔹 Step 3: Image Segmentation
- **K-means Clustering** is used to **identify diseased regions**.
- **Boundary and Spot Detection** techniques extract affected areas.

### 🔹 Step 4: Feature Extraction
- **Color Features** (Hue, Saturation, Value)
- **Texture Features** (Contrast, Entropy, Homogeneity)
- **Shape Features** (Size, Eccentricity)

### 🔹 Step 5: Classification Using SVM
- A **Support Vector Machine (SVM)** classifier is trained to identify diseases like:
  - **Powdery Mildew**
  - **Downy Mildew**
  - **Anthracnose**
- The model predicts the **type and severity** of infection.

---

## 📊 Results & Accuracy
- The system was tested on **256x256 pixel images** using **MATLAB**.
- **Disease Detection Accuracy: 90.96%**.
- **Gaussian Filtering** improved precision by reducing noise.

---

## 💻 Technologies Used
- **Programming Language**: MATLAB
- **Machine Learning Model**: Support Vector Machine (SVM)
- **Image Processing**: OpenCV, MATLAB Image Toolbox
- **Algorithms**: K-means Clustering, Histogram Equalization, Boundary Detection

---

## 📝 How to Use?
1. **Capture an image** of a grape leaf.
2. **Run the preprocessing pipeline** to enhance the image.
3. **Segment the diseased area** using the clustering algorithm.
4. **Extract features** for classification.
5. **SVM Classifier predicts** the type of disease.
6. **Display results**, including severity and suggested actions.

---

## 🎯 Future Enhancements
- **Deploy as a mobile app** for real-time farmer assistance.
- **Train on a larger dataset** to improve accuracy.
- **Automate pesticide recommendations** based on detected disease.

---

## 🏫 About the Project
- **Institution**: Vardhaman College of Engineering
- **Department**: Electronics and Communication Engineering (ECE)
- **Year**: Final Year B.Tech Project

🔗 **For More Information, Refer to the Full Report!** 📄
