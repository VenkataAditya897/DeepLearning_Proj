
# 🧠 MNIST Handwritten Digit Predictor

This project builds a convolutional neural network (CNN) using TensorFlow to classify handwritten digits from the MNIST dataset with high accuracy. It also includes an interactive Pygame-based drawing board where users can draw digits, and the trained model predicts them in real time.

## 🚀 Features

- Loads and visualizes the MNIST dataset.
- Preprocesses image data and one-hot encodes labels.
- Builds a CNN using TensorFlow/Keras.
- Uses EarlyStopping and ModelCheckpoint callbacks for training optimization.
- Trains to ~99% accuracy on validation set.
- Saves the best model as `amazing.h5`.
- Launches a Pygame window where users can:
  - Draw digits
  - Automatically predict and display the number
  - Reset the canvas with a keypress

---

## 🛠️ Tech Stack

- Python 3.10
- TensorFlow / Keras
- NumPy
- OpenCV
- Pygame
- Matplotlib

---


## 📊 Dataset

- **MNIST Handwritten Digits**  
  60,000 training and 10,000 test grayscale images of handwritten digits (0–9) sized 28x28.

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mnist-digit-predictor.git
   cd mnist-digit-predictor
   ```

2. Install dependencies:
   ```bash
   pip install tensorflow numpy opencv-python pygame matplotlib
   ```

---

## 🧠 Train the Model

1. Run the training script (`model_training.ipynb`) to:
   - Load and preprocess the dataset
   - Train the CNN model
   - Save the best model to `amazing.h5`

---

## ✍️ Run Digit Prediction 

1. Run The ipynb file


2. Instructions:
   - Draw a digit on the black canvas
   - Release the mouse to get prediction
   - Press **`n`** to clear the canvas and try again

---

## 🧪 Model Performance

- Achieves ~99% accuracy on the MNIST validation set
- Fast real-time prediction on hand-drawn digits

---



## 🙋‍♂️ Contact

For questions or improvements, feel free to open an issue or PR.
