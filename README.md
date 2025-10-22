# SVM with RBF Kernel - Dual Optimization 🧿

![Python](https://img.shields.io/badge/python-3.11-blue)
![NumPy](https://img.shields.io/badge/numpy-1.25-orange)
![CVXOPT](https://img.shields.io/badge/cvxopt-1.3.0-green)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

😖 **Boring Part (Implementation 🥱)**  
This project implements a Support Vector Machine (SVM) using the Radial Basis Function (RBF) kernel to classify digits (0 and 1) from the MNIST dataset. The classifier is optimized by solving the dual problem using quadratic programming with `cvxopt`.

(●'◡'●)  **Quick update:** When I was making this, I didn't know about vectorization. That’s why you’ll see too many loops here with numbers in output (iteration step). I wasn’t using GPU, so loops are slow. I had to print each epoch, and honestly, I was too bored to rewrite it with vectorization. Brain-burning SVM torture complete. Leaving it as-is.  

---

🚀 **Features**  

- **Dual Optimization:** Solves the SVM dual problem via quadratic programming for exact margin maximization. Why are you still reading? Just go and use `scikit-learn`, you overachiever 🤖.  
- **Efficient Training:** Optimized to run on a balanced subset of the MNIST dataset (1000 examples).  
  - Hey, it’s okay—I didn’t use vectorization that much, so iteration is slow.  
  - If you ask “Why not vectorize?” — take that question, roll it up, and place it somewhere safe. Thank you 👍.  
- **Bias Calculation:** Includes bias averaging over support vectors. Because… math.  

---

📁 **Dataset**  

This project uses the MNIST dataset for classifying digits 0 and 1. The dataset is already pre-processed and scaled for SVM training.  

- **Training Set:** 500 examples of digit 0 and 500 examples of digit 1  
- **Test Set:** Provided separately for evaluating the model  

---

🔌 **Dataset Instructions**  

If you’re cloning this repository, download the dataset from the MNIST official website (or from this repo if available).  
Place it in the same directory as the code for smooth execution.  

---

That’s it. Have fun. Bye 👋