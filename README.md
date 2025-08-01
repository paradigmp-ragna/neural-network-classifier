# Neural Network from Scratch - Letter Classification (A, B, C)

## 📌 Project Description

This project implements a **two-layer feedforward neural network** using only NumPy to classify binary image patterns representing the capital letters **A**, **B**, and **C**.

Each image is represented as a **5x6 binary pixel grid (30 pixels)**, flattened into a 1D array. The network learns to distinguish between the letters using custom logic for **forward propagation**, **backpropagation**, and **gradient descent**, without any external machine learning libraries like TensorFlow or PyTorch.

The project is structured and tested in a Jupyter Notebook for readability and learning.

---

## 🧠 Neural Network Architecture

- **Input Layer:** 30 neurons (each for one pixel)
- **Hidden Layer:** 10 neurons (sigmoid activation)
- **Output Layer:** 3 neurons (representing A, B, and C)

---

## ⚙️ Technologies Used

- Python 3
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📊 Training

- **Loss Function:** Mean Squared Error (MSE)
- **Optimizer:** Manual gradient descent
- **Activation:** Sigmoid for both layers
- **Epochs:** 1000
- **Learning Rate:** 0.1

---

## 📈 Output

- Loss curve plotted using `matplotlib`
- Prediction results shown alongside the binary image of the letter using `imshow()`

---

## 📁 File Structure (if converted to .py scripts)

