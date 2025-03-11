# **SkinFusionNet: A Hybrid Deep Learning Model for Skin Cancer Detection**

## 📜 **Description**  
SkinFusionNet is a hybrid deep learning model combining Convolutional Neural Networks (CNNs) with Random Forest Classifiers (RFCs) to classify skin cancer lesions effectively. Designed to work with subsets of the ISIC 2024 dataset, it focuses on delivering high accuracy with reduced computational overhead, making it suitable for deployment on moderately powered systems.

---

## 🚀 **Features**  
- **Hybrid Architecture**: Leverages CNN for feature extraction and RFC for classification.  
- **Lightweight and Efficient**: Processes data with only 140 million MACs, ensuring fast inference.  
- **High Performance**: Competes with state-of-the-art models with a fraction of the computational resources.  
- **Robust Design**: Addresses challenges like data imbalance and overfitting through innovative techniques.  

---

## 📊 **Performance**  
- **Dataset**: ISIC 2024 subset  
- **Key Metrics**:  
  - Accuracy: *98.11*  
  - F1 Score: *98.11*  

---

## 📚 **Dataset**  
- **Source**: [ISIC 2024 Dataset](https://www.isic-archive.com/)  
- **Preprocessing Steps**:  
  - Noise removal and ROI extraction  
  - Image resizing to 224x224 pixels  
  - Data augmentation for balancing class distribution  

---

## 🛠️ **Setup and Usage**

### **Prerequisites**  
Ensure you have the following installed:  
- Python >= 3.8  
- TensorFlow >= 2.0  
- Scikit-learn  
- NumPy  
- Matplotlib  
