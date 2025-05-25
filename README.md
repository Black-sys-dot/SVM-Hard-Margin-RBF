SVM with RBF Kernel - Dual Optimization 🧿
<br>
<br>
😖 Boring Part (Implementation 🥱)
This project implements a Support Vector Machine (SVM) using the Radial Basis Function (RBF) kernel to classify digits (0 and 1) from the MNIST dataset. The classifier is optimized by solving the dual problem using quadratic programming with cvxopt.
Oh, you don’t know what the dual optimization problem is? You scikit-learn enthusiast 🤡🤡.

<br>
🚀 Features

Dual Optimization: Solves the SVM dual problem via quadratic programming for exact margin maximization. Why are you still reading? Just go and use scikit-learn, you overachiever 🤖.

Efficient Training: Optimized to run on a balanced subset of the MNIST dataset (1000 examples).
Hey, it's okay—I don’t use vectorization that much, so it’s hard to iterate over a large dataset.
Now, you’ll ask, "Why don’t you use vectorization?" Great question. Take that question, roll it up, and place it somewhere safe. Thank you 👍.

Bias Calculation: Includes bias averaging over support vectors. Because... math.

<br>
📁 Dataset
This project uses the MNIST dataset for classifying digits 0 and 1. The dataset is already pre-processed and scaled for SVM training.

Training Set: 500 examples of digit 0 and 500 examples of digit 1

Test Set: Provided separately for evaluating the model.

<br>
🔌 Dataset Instructions
If you're cloning this repository, download the dataset from the MNIST Official Website or from this repo (if available).
Just place it in the same directory as the code for smooth execution.
<br>
<br>
🫶 License
Do whatever you want with this—just don’t blame me if it slows down your computer or makes it sound like a jet engine.
And one last thing: if you're feeling adventurous, try iterating over the entire dataset without optimization—might not burn your house down, but it’ll sure heat things up 🔥.

That’s it. Have fun. Bye 👋
