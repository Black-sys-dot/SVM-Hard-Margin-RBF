SVM with RBF Kernel - Dual Optimization🧿<br><br>
Boring part(Implementation part 🤓):<br>
This project implements a Support Vector Machine (SVM) using the Radial Basis Function (RBF) kernel to classify digits (0 and 1) from the MNIST dataset. The classifier is optimized through solving the dual problem using quadratic programming with cvxopt. It’s an efficient and accurate solution for binary classification, leveraging the RBF kernel for non-linear data separation.

🚀 Features
Dual Optimization: Solves the SVM dual problem via quadratic programming for exact margin maximization.
Radial Basis Function (RBF) Kernel: Handles complex, non-linear decision boundaries.
Efficient Training: Optimized to run on a balanced subset of the MNIST dataset (1000 examples).
Bias Calculation: Includes bias averaging over support vectors.
Performance: Achieves strong classification performance, even with hard-margin SVM.<br><br>
📁 Dataset
The project uses the MNIST dataset for classifying digits 0 and 1. The dataset is already pre-processed and scaled for the SVM training.

Training Set: 500 examples of digit 0 and 500 examples of digit 1.
Test Set: Provided separately for evaluating the model.
Dataset Instructions:
If you're cloning this repository, download the dataset from MNIST Official Website or from this repository.
Place the dataset in the same directory as the code for easy access.
​
