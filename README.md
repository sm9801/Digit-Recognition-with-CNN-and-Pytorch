# Digit Recognition Using Convolutional Neural Networks (CNN) and PyTorch

## 📜 **Overview**

This project implements a digit recognition system using PyTorch, Convolutional Neural Networks (CNNs), and Computer Vision techniques. The project is built entirely from scratch, including custom implementations of training, prediction, activation functions, and their derivatives. The best-performing model achieved a validation accuracy of **94%** and excelled on the test dataset.

---

## 🚀 **Features**

- **Custom Train and Predict Functions**: Implemented custom training and prediction pipelines for greater flexibility.
- **ReLU Activation**: Developed a ReLU activation function along with its derivative for backpropagation.
- **Model Testing**: Experimented with multiple neural network architectures to find the most effective setup.
- **Fully Connected Model**: Built a single-layer fully connected neural network using PyTorch's Linear layers.
- **Custom Flatten Function**: Created a function to reshape higher-dimensional tensors into a suitable format for training (N × d).

---

## 📊 Model Performance 

The best-performing CNN model achieved:
- **Validation Accuracy**: 94%
- **Test Accuracy**: Highest among all tested models.

### **Optimal Model Parameters**:
- **Batch Size**: 64
- **Hidden Size**: 10
- **Learning Rate**: 0.1
- **Momentum**: 0
- **Activation Function**: ReLU

---

## 🛠️ Technology Stack

- **Framework**: PyTorch
- **Language**: Python
- **Libraries**: NumPy, Matplotlib (for visualization, if used)

---

## 📈 Future Enhancements

- Experiment with additional activation functions (e.g., sigmoid, tanh).
- Implement dropout for better regularization.
- Explore deeper CNN architectures for improved accuracy.

---

## 🤝 Acknowledgments

Special thanks to PyTorch's documentation and the digit recognition datasets provided by MITx that inspired this project.

