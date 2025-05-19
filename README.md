# 🌙 Make Moons Classification with High Accuracy (98%)

This project demonstrates a classification model built using the synthetic **`make_moons`** dataset from `sklearn.datasets`. The goal is to distinguish between two interleaving half circles (a common toy dataset for binary classification tasks).

> ✅ Achieved **98% accuracy** on the test set using a well-tuned neural network model.

---

## 📌 Dataset

The **`make_moons`** dataset is a synthetic binary classification dataset with a non-linear decision boundary. It is commonly used to demonstrate the capability of machine learning algorithms to handle complex decision surfaces.

- **Number of samples**: 1000 
- **Features**: 2 (x, y coordinates)
- **Classes**: 2 (binary classification)
- **Noise**: Optional Gaussian noise (to increase difficulty)

---

## 🧠 Model Overview

- **Model type**: Neural Network  
- **Framework**: TensorFlow / Keras  
- **Architecture**: Feedforward network with hidden layers  
- **Activation**: ReLU, Sigmoid  
- **Optimizer**: Adam  
- **Loss function**: Binary Crossentropy  
- **Accuracy achieved**: **98%**

---

## 📊 Visualizations

- Dataset plot with class labels and metrics
- Learning rate visualization  
- Accuracy and loss curves over epochs  

---

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/Bibliophiles/make-moons-classification.git
   cd make-moons-classification

2. Open the notebook in Jupyter or Google Colab:

   -  Make_Moon.ipynb
     
3. Install required dependencies (if running locally): 
```bash
pip install -r requirements.txt
```

4. Run all cells to train and evaluate the model.


##  ✅ Results
Accuracy: 98% on test data

Key Insight: Even a simple neural network can learn complex, non-linear decision boundaries with good generalization, especially on clean, well-structured synthetic datasets.

##  📚 Requirements
numpy
matplotlib
scikit-learn
tensorflow

##  📬 Contact
For questions or suggestions, feel free to reach out via dennisamematekpor@gmail.com or open an issue.



