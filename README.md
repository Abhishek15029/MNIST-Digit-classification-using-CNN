# 🧠 MNIST Digit Classification using CNN

## 📌 Description

This project implements a Convolutional Neural Network (CNN) to classify handwritten digits (0–9) using the MNIST dataset. The model learns image features automatically and predicts the correct digit.

---

## ⚙️ Steps Involved

* Load MNIST dataset
* Normalize pixel values (0–255 → 0–1)
* Reshape images for CNN input
* Build CNN model (Conv2D + MaxPooling + Dense)
* Train the model
* Evaluate performance
* Plot accuracy graph

---

## 🧠 Model Architecture

Conv2D → MaxPooling → Conv2D → MaxPooling → Flatten → Dense → Output

---

## 📊 Result

* Achieved high accuracy on test dataset
* Model successfully classifies handwritten digits

---

## 🛠️ Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib

---

## 🚀 How to Run

1. Open the notebook `mnist_cnn.ipynb`
2. Run all cells
3. View training, accuracy, and results

---

## 📈 Output

* Accuracy graph (training vs validation)
* Test accuracy printed
* Predictions on test images

---

## 🔮 Future Improvements

* Add image upload for real-time prediction
* Improve model using Dropout
* Deploy as a web app

---

## 📁 Files

* `mnist_cnn.ipynb` → main project notebook
