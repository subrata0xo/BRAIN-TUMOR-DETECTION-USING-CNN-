# Deep Learning vs Traditional ML: Brain Tumor Detection using CNN & K-NN

## 📌 Project Description
This project focuses on detecting brain tumors from MRI images using two approaches: **Convolutional Neural Networks (CNN)** (Deep Learning) and **K-Nearest Neighbors (K-NN)** (Traditional Machine Learning). The objective is to compare the performance of deep learning and traditional ML methods in medical image classification.

## 📊 Dataset
We used the **Kaggle Brain Tumor MRI Dataset**, which contains MRI images classified into **4 categories**:
- Glioma  
- Meningioma  
- Pituitary  
- No Tumor  

## 🧠 Models Implemented
1. **CNN (Deep Learning)**
   - Framework: TensorFlow/Keras  
   - Preprocessing: Image normalization and augmentation  
   - Accuracy: **97%+**  

2. **K-NN (Traditional ML)**
   - Framework: Scikit-learn  
   - Features extracted and classified using K-Nearest Neighbors  
   - Accuracy: **90%**  

### 🔎 Results Comparison  

| Model | Technique | Accuracy |
|-------|-----------|----------|
| CNN   | Deep Learning (TensorFlow/Keras) | **97%+** |
| K-NN  | Traditional ML (scikit-learn) | 90% |

## ⚙️ Installation & Requirements
Clone the repository and install dependencies:
```bash
git clone https://github.com/yourusername/brain-tumor-detection.git
cd brain-tumor-detection
pip install -r requirements.txt
```

### Requirements
- Python 3.x  
- TensorFlow  
- Keras  
- NumPy  
- Pandas  
- scikit-learn  
- Matplotlib  

## 🚀 Usage
- To run the **CNN model**: open `code(CNN).ipynb` in Jupyter Notebook and execute cells.  
- To run the **K-NN model**: open `code(K-NN).ipynb` in Jupyter Notebook and execute cells.  

## 📂 Project Structure
```
├── code(CNN).ipynb      # Notebook for CNN model
├── code(K-NN).ipynb     # Notebook for K-NN model
├── data/                # Dataset (not included due to size)
├── README.md            # Project documentation
└── requirements.txt     # Dependencies
```

## 👩‍💻 Contributors
- **Subu** – Implemented CNN model  
- **Sumoyee** – Implemented K-NN model  

## 📜 License
This project is licensed under the **MIT License**.
