## 📸 **Image Classification Using CNN**

### 🔍 **Objective**
This project aims to classify images into three categories: **Buildings**, **Forest**, and **Sea** using a **Convolutional Neural Network (CNN)**. The model is built with **TensorFlow** and **Keras** and deployed using **Gradio** for real-time image classification.

---

### 📂 **Project Structure**
```
├── data/                         # Dataset folder (train/test images)
├── notebooks/
│   └── Image_Classification.ipynb # Jupyter/Colab notebook with full code
├── app.py                        # Gradio app for real-time predictions
├── requirements.txt              # List of required libraries
├── README.md                     # Project documentation
└── model/                        # Folder to store trained models
```

---

### 🚀 **Features**
- Classifies images into **Buildings**, **Forest**, and **Sea**.
- **CNN architecture** with convolution, pooling, and dense layers.
- **Gradio** interface for real-time image upload and prediction.
- Training and validation accuracy/loss visualization.
- Data augmentation techniques to improve model performance.

---

### ⚡ **Technologies Used**
- **Python**
- **TensorFlow / Keras** for building and training the CNN.
- **Gradio** for deploying a simple web interface.
- **Matplotlib** for plotting model performance.
- **NumPy** and **Pandas** for data manipulation.
- **OpenCV** for image preprocessing.

---

### 📊 **Dataset**
- Images categorized into **Buildings**, **Forest**, and **Sea**.
- Split into **training**, **validation**, and **test** sets.
- Image augmentation techniques applied to improve model generalization.

---

### 🛠 **How to Run the Project**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/Rashu0304/Image-Classification-CNN.git
   cd Image-Classification-CNN
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Train the model:**  
   Run the notebook in **Google Colab** or **Jupyter Notebook** to train the CNN.

4. **Launch the Gradio app:**  
   After training, run the following command to start the web app:
   ```bash
   python app.py
   ```

5. **Test the model:**  
   Open the **Gradio** link in your browser, upload an image, and see the classification result in real time!

---

### 📈 **Results**
Add sample results here with screenshots or tables:  
| Image | Predicted Class | Confidence |
|-------|-----------------|------------|
| 🏙️ Building | Building | 95% |
| 🌲 Forest   | Forest   | 92% |
| 🌊 Sea      | Sea      | 98% |

---

### 📘 **Future Improvements**
- Experiment with deeper architectures like **ResNet** or **VGG**.
- Add more categories to enhance classification capability.
- Deploy the app using **Streamlit** or **Flask** for more customization.
- Improve the dataset with more diverse images for better generalization.

---

### 👩‍💻 **Contributors**
- **Rashmita Gauda** – [GitHub](https://github.com/Rashu0304) | [LinkedIn](your-linkedin-profile)

---
---

### **Badges **

- **Python Version:** ![Python](https://img.shields.io/badge/Python-3.x-blue)
- **TensorFlow Version:** ![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
- **License:** ![License](https://img.shields.io/badge/License-MIT-green)


