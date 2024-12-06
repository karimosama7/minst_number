# Handwritten Digit Recognition using ANN  

This project focuses on recognizing handwritten digits (0-9) from the **MNIST dataset** using an **Artificial Neural Network (ANN)** built with TensorFlow/Keras. The model was trained and evaluated for its accuracy on unseen data.  

## 🚀 Features  
- Implements a simple yet effective ANN architecture.  
- Preprocesses the MNIST dataset to normalize and prepare it for training.  
- Achieves high accuracy in classifying handwritten digits.  

## 🛠️ Technologies Used  
- **Programming Language:** Python  
- **Framework:** TensorFlow/Keras  
- **Dataset:** MNIST  

## 📁 File Structure  
- `number_minsty.ipynb`: Jupyter Notebook containing the full implementation of the project.  

## 📊 Model Overview  
The ANN architecture includes:  
- Input Layer: Accepts 28x28 pixel images, flattened into 784 features.  
- Hidden Layers: Dense layers with ReLU activation for feature extraction.  
- Output Layer: 10 neurons with Softmax activation for digit classification.  

## 🧪 Steps to Run  
1. Clone this repository:  
   ```bash  
   git clone <repository-url>  
   ```  
2. Install dependencies:  
   ```bash  
   pip install tensorflow numpy matplotlib  
   ```  
3. Open the Jupyter Notebook (`number_minsty.ipynb`) and run all cells to train and evaluate the model.  

## 🖼️ Results  
- **Training Accuracy:** 97%  
- **Test Accuracy:** 95%  

The trained model is capable of accurately predicting digits from the MNIST dataset.  

## 🌟 Future Improvements  
- Enhance the architecture to improve accuracy.  
- Experiment with other datasets to generalize the model further.  
- Add deployment features for real-world applications.  

## 🤝 Contributing  
Feel free to fork this repository, raise issues, or submit pull requests for suggestions and improvements!  
