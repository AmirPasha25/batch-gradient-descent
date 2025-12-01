# Batch Gradient Descent

![Parabola Shape](3D%20Convex%20Bowl.png)
![Parabola Shape](Parabola%20Shape%201.png)

## 📌 Overview
This project is a simple, beginner-friendly implementation of **Batch Gradient Descent** using just Python and NumPy.

The goal is to clearly show *how gradient descent actually works under the hood*:

- How a model learns using the **average gradient** of the full dataset  
- How parameters move step-by-step toward the minimum  
- What the loss surface looks like (a smooth convex “bowl”)  
- How the values of `m` and `b` gradually converge

If you’ve ever felt gradient descent was confusing or “too math heavy”, this project breaks it down in the simplest way possible.

---

## 🚀 What is Batch Gradient Descent?
Batch Gradient Descent updates model parameters by looking at **all training samples at once**.  
It is the most stable version of gradient descent because it uses the complete dataset to compute direction of  movement.
  
---

## 🧠 In Simple Words  
Think of the loss function like a **bowl**.

Batch Gradient Descent looks at the *entire shape of the bowl* before taking every step.  
This makes the movement smoother and less noisy, compared to SGD which takes steps based on just one data point.

---
