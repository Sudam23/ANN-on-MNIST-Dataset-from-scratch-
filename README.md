# Two-Layer Neural Network on MNIST 🧠📊
## This project uses a **two-layer fully connected neural network** for **handwritten digit classification** with the **MNIST dataset**. The model is developed from scratch in Python without the use of deep learning libraries such as TensorFlow or PyTorch.

## 📂 Project Files
- **`first_nn_exc.py`** – Neural network code.
- **`two_layer_net_mnist_exc.ipynb`** – Jupyter Notebook for training and testing the model.

## 📌 Features
✅ Two-layer neural network (Input → Hidden Layer → Output)
✅ Sigmoid activation function & Softmax for classification
✅ Cross-entropy loss function
✅ Gradient Descent, Momentum, and Nesterov Accelerated Gradient optimizers
✅ Trains and evaluates on the MNIST dataset

## 🧠 Model Architecture 
Input Layer: MNIST images (28x28 pixels → 784 features)
Hidden Layer: M neurons with sigmoid activation
Output Layer: 10 neurons (one per digit 0-9) with softmax activation
Loss Function: Cross-entropy loss
Optimization: Gradient Descent & its variations

## 📊 Results & Accuracy
The model is trained and tested on the MNIST dataset. Expected Train accuracy and Test accuracy are 96.92% and 94.52% respectively.

## 📌 To-Do
1. Add more activation functions (e.g., ReLU)
2. Optimize training using Adam optimizer
3. Try various weight initialization methods.
