# Neural Network from Scratch for Fake Job Postings Dataset

This repository contains the Jupyter notebook where I developed and trained a custom neural network to detect fake job postings using only **pandas** and **numpy** - no advanced deep learning frameworks!

## 📓 Viewing the Notebook

GitHub's rendering of Jupyter notebooks can sometimes be inconsistent or fail to load properly. For the best viewing experience, please use **NBViewer**:

**🔗 [View Notebook on NBViewer](https://nbviewer.org/github/jcb03/Neural-Network-from-scratch-for-Fake-Job-Postings-dataset/blob/main/neuralnetworkjobposting.ipynb)**

*If the notebook has been recently updated, you may need to add `?flush_cache=true` to the NBViewer URL to see the latest version.*

## 🧠 Building a Neural Network from Scratch

This project demonstrates how to create a fully functional neural network using only basic Python libraries:

### **What I Built:**
- **Custom Neural Network Architecture**: Input layer → Hidden layers (128, 64 neurons) → Output layer
- **Activation Functions**: Implemented Leaky ReLU and Sigmoid from scratch
- **Backpropagation Algorithm**: Manual gradient computation and weight updates
- **Loss Function**: Custom binary cross-entropy implementation
- **Optimization**: Gradient descent with learning rate scheduling
- **Regularization**: Dropout and L2 regularization implemented manually

### **Libraries Used:**
- **pandas**: For data manipulation and preprocessing
- **numpy**: For mathematical operations and matrix computations
- **No TensorFlow, PyTorch, or Keras** - everything built from mathematical foundations!

### **Why From Scratch?**
Building neural networks from scratch helped me understand:
- How gradients flow through the network
- The mathematics behind backpropagation
- How different activation functions affect learning
- The impact of regularization techniques
- Memory and computational efficiency considerations

## 🎯 Project Highlights

- **Dataset**: Real-world fake job postings dataset from Kaggle
- **Performance**: Achieved 91.15% accuracy and 95.12% recall
- **Feature Engineering**: Advanced text processing with TF-IDF vectorization
- **Class Imbalance**: Handled using SMOTE oversampling techniques
- **Production Ready**: Successfully deployed as a live web application

## 📁 Repository Contents

- `neuralnetworkjobposting.ipynb`: Complete notebook with neural network implementation and training

## 🔗 Related Links

- **🚀 Live Demo**: [JobDetective AI](https://job-detective-ai.streamlit.app/)
- **📦 Deployment Code**: [Full Application Repository](https://github.com/jcb03/Fake-Job-Posting-Neural-Network-fast-api-with-deployment)

## 🎓 Learning Outcomes

This project demonstrates:
- Deep understanding of neural network fundamentals
- Ability to implement complex algorithms from scratch
- Strong mathematical foundation in machine learning
- Practical application of theoretical concepts

---

⭐ **Star this repository if you found it educational!**

*Built with passion for understanding the fundamentals of machine learning.*
