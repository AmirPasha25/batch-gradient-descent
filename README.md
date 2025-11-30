# Batch Gradient Descent — Simple & Clear Implementation

![Gradient Descent Bowl](https://raw.githubusercontent.com/your-username/your-repo/main/assets/gradient_bowl.png)

## 📌 Overview
This project demonstrates **Batch Gradient Descent** from scratch using Python and NumPy.  
The goal is to show **how the algorithm updates parameters using the average gradient** across the full dataset.

It includes:
- A simple linear regression example  
- Batch gradient update formula  
- Visualization of the convex loss surface  
- Parameter convergence tracking  

---

## 🚀 What is Batch Gradient Descent?
Batch Gradient Descent computes the gradient of the loss **using the entire dataset** at every step.

### Formula
For parameters \( m \) and \( b \):

\[
m = m - \alpha \cdot \frac{1}{N} \sum_{i=1}^{N} \frac{\partial J}{\partial m}
\]

\[
b = b - \alpha \cdot \frac{1}{N} \sum_{i=1}^{N} \frac{\partial J}{\partial b}
\]

Where:
- \( \alpha \) = learning rate  
- \( N \) = number of samples  

This produces a **smooth, stable descent** toward the global minimum when the function is convex (like linear regression).

---

## 📂 Project Structure
