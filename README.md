# 🏆 CNN-Based Image Classification  
🚀 **Supervised Learning with Deep Neural Networks using Transfer Learning (InceptionV3)**  

## 📌 Project Overview  
This project focuses on **lung disease classification** using **Convolutional Neural Networks (CNNs)** and **Transfer Learning**.  
It applies **InceptionV3** to classify lung X-ray images into three categories:  
1️⃣ **COVID-19 Affected Lungs**  
2️⃣ **Pneumonia Affected Lungs**  
3️⃣ **Normal Lungs**  

## 📂 Dataset  
- **Total Images:**  
  - **Training Set:** 10,606  
  - **Validation Set:** 3,030  
  - **Test Set:** 1,517  
- **Number of Classes:** 3 (COVID, Pneumonia, Normal)  
- **Image Dimensions:** Varying sizes (e.g., 300×225px)  

## 🛠️ Methodology  
✅ **Preprocessing:** Resizing, Normalisation, Data Augmentation  
✅ **Model Architecture:** InceptionV3 (Pretrained on ImageNet)  
✅ **Fine-Tuning:** Adjusting layers for optimal performance  
✅ **Optimisation:** Adam Optimiser with Categorical Crossentropy Loss  
✅ **Evaluation Metrics:** Accuracy, Confusion Matrix, Classification Report  

## 📊 Results & Performance  
- **Best Accuracy Achieved:** **94%**  
- **Batch Size Tested:** 32, 64, **128 (Best Performance)**  
- **Dropout Rate Tested:** 0.3 – **0.5 (Best Stability)**  

## 🚀 How to Run  
1️⃣ Clone the repository  
   ```bash
   git clone https://github.com/sv3112/CNN-Image-Classification.git
   cd CNN-Image-Classification

2️⃣ Install dependencies

pip install -r requirements.txt

3️⃣ Open the Jupyter Notebook

jupyter notebook Lung_Dataset_Image_Classification.ipynb


📌 Future Improvements

🏆 Try ResNet50 or EfficientNet for comparison
📊 Implement Grad-CAM for Explainability
☁️ Deploy the model using Flask/FastAPI on AWS/GCP


