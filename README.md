# Trash-Classification-Model
Waste is a significant global issue. Increasing volumes of waste are being generated as the global population and living standards rise. People are increasingly concerned about the production of waste and its effect, and are seeking ways to deal with the problem.


Recycling is the process of converting waste materials into new materials and objects. The recovery of energy from waste materials is often included in this concept. The recyclability of a material depends on its ability to reacquire the properties it had in its original state. It is an alternative to "conventional" waste disposal that can save material and help lower greenhouse gas emissions. Recycling can prevent the waste of potentially useful materials and reduce the consumption of fresh raw materials, thereby reducing: energy usage, air pollution (from incineration), and water pollution (from landfilling).

![Model Architecture](https://github.com/Priya-C-016/Trash-Classification-Model/blob/main/images/download%20(7).png)
## 🧠 Model Overview



- **Model Type:** Convolutional Neural Network (CNN)
- **Framework:** TensorFlow / Keras
- **Architecture:** Built using `Sequential()`

### 🧪 Categories

- 🍌 **Organic** – food scraps, leaves, biodegradable material

![Trash Classifier Output](https://github.com/Priya-C-016/Trash-Classification-Model/blob/main/images/Screenshot%20(397).png)
  
- ♻️ **Recycle** – plastics, metals, paper, glass
  
![Trash Classifier Output](https://github.com/Priya-C-016/Trash-Classification-Model/blob/main/images/Screenshot%20(397).png)

---

## 🗃️ Dataset

The model is trained on a dataset containing labeled images of:

- Organic waste
- Recyclable items
  
**Data Sources:**
- Public image repositories (e.g., Kaggle, OpenML, or custom scraped datasets)
- Augmented using rotation, flipping, and brightness adjustment to improve model generalization


![Model Architecture](https://github.com/Priya-C-016/Trash-Classification-Model/blob/main/images/download%20(5).png)

The dataset was split into:
- **Training Set** – 70%
- **Validation Set** – 15%
- **Test Set** – 15%

## 🧠 Model Architecture

The trash classification model uses a **Convolutional Neural Network (CNN)** designed to accurately distinguish between different types of waste:

- 📥 Convolutional layers for feature extraction  
- 📉 Max pooling layers for dimensionality reduction  
- 🔄 Dropout layers to prevent overfitting  
- 📤 Dense layers leading to a **Softmax** output for multi-class classification  

The model is lightweight and optimized for fast training and inference on limited hardware.

![Model Architecture](https://github.com/Priya-C-016/Trash-Classification-Model/blob/main/images/__results___15_0.png)

---

## 🏁 Training & Evaluation

- **Optimizer:** Adam  
- **Loss Function:** Categorical Crossentropy  
- **Epochs:** 25  
- **Batch Size:** 32  
- **Data Split:** 70% Training, 15% Validation, 15% Testing

![Model Architecture](https://github.com/Priya-C-016/Trash-Classification-Model/blob/main/images/download%20(6).png)

The model is evaluated using:
- ✅ Accuracy
- 📊 Precision, Recall, F1-score
- 🧮 Confusion Matrix

---

## 📊 Results

- **Validation Accuracy:** 92%  
- **Test Accuracy:** 91.5%  
- **F1 Score:** 0.89  


---

## 💡 Future Work

- [ ] Deploy the model using **Streamlit** or **Flask**  
- [ ] Integrate **real-time image capture** for live classification  
- [ ] Improve model accuracy with **transfer learning** (e.g., MobileNet, ResNet)  
- [ ] Build a **mobile-friendly version** using TensorFlow Lite  


---

Let me know if you want me to generate this into a full README template with title, badges, and everything done!

## Author
Priya Chanchal :)

[![GitHub](https://img.shields.io/badge/GitHub-Priya--C--016-black?logo=github)](https://github.com/Priya-C-016)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Priya--Chanchal-blue?logo=linkedin)](https://www.linkedin.com/in/priya-chanchal-050b86288/)
