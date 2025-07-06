# 🧠 ImagGen – Image Generation using GAN

**ImagGen** is a deep learning project that implements a **Vanilla Generative Adversarial Network (GAN)** to generate handwritten digits that resemble those in the **MNIST dataset**. The project includes training scripts and visual output of generated digits per epoch. It’s designed as a foundational implementation for understanding GANs.

---

## 🔍 Project Overview

This project demonstrates how a simple GAN, composed of a Generator and Discriminator, can learn to produce synthetic handwritten digits. The model is trained on the **MNIST dataset**, which contains 60,000 images of digits (0–9). As training progresses, the generator improves its ability to create realistic-looking digits.

---

## 🖥️ Output Samples

Generated digit images are saved in the `outputs/` directory after specific training epochs. Below is an example of the improvement in quality:

| Epoch  | Sample Output |
|--------|----------------|
| 50     | ![Sample 50](outputs/sample_epoch_50.png) |
| 100    | ![Sample 100](outputs/sample_epoch_100.png) |

---

## 🛠️ Technologies Used

- **Python 3.x**
- **TensorFlow / Keras**
- **MNIST Dataset (via Keras)**
- **NumPy**
- **Matplotlib**
- **Jupyter Notebook**

---

## 🚀 How to Run

### 1. Clone the Repository

git clone https://github.com/nihirborkar17/ImagGen-Using_GAN.git
cd ImagGen-Using_GAN

2. Install Dependencies
Using requirements file (if provided):

pip install -r requirements.txt
Or manually install:

pip install tensorflow numpy matplotlib
3. Train the GAN
Run the training script:

python gan_training.py
This will begin training and periodically save generated digit samples in the outputs/ folder.

📈 Project Highlights
Trains a Vanilla GAN from scratch using Keras

Learns to generate 28x28 grayscale images of digits

Uses Binary Crossentropy loss and Stochastic Gradient Descent

Logs and saves generated samples to track performance

🔮 Future Improvements
Upgrade to DCGAN (Deep Convolutional GAN) for more stable training

Add Tkinter GUI for one-click image generation and saving

Evaluate image quality using FID or Inception Score

Extend model to generate Fashion-MNIST or high-resolution images

🤝 Contribution
Feel free to fork the repo, raise issues, or suggest improvements!

📜 License
This project is licensed under the MIT License.

