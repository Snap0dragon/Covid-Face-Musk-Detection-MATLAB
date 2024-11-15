# 😷 Covid Face Mask Detection Using MATLAB
![Mask Detection](https://github.com/Snap0dragon/Covid-Face-Musk-Detection-MATLAB/assets/86599809/309ea928-9caa-4d3a-bfc4-678d74a9a95f)
## 📜 **Project Description**
This project implements a **COVID-19 Face Mask Detection** system using MATLAB. It uses a live webcam feed to detect faces and classify them as either **With Mask** or **Without Mask**. The system employs **AlexNet**, a pre-trained deep learning model, for feature extraction and classification.

---

## ⚙️ **Key Features**
- **Face Detection:** Real-time face detection using the Viola-Jones algorithm.
- **Mask Classification:** Classifies detected faces into two categories: "With Mask" or "Without Mask."
- **Customizable Training:** Allows you to train the model with your own dataset.
- **Live Testing:** Real-time testing of mask detection using a webcam.

---


## 📂 **Code Files**

### 1. **P1_Data_Collection.m**
- Captures and saves 150 face images from a live webcam feed.
- Crops and resizes images to a fixed size of 227x227 pixels.
- Outputs the images in `.bmp` format for training.

### 2. **P1_Training.m**
- Modifies the AlexNet architecture for binary classification.
- Trains the model using labeled images (mask and no mask categories).
- Saves the trained network (`myNet1`) for later use.

### 3. **P1_Testing.m**
- Loads the trained model to classify faces in a live webcam feed.
- Displays "With Mask," "Without Mask," or "No Face Detected" as output.
- Continuously processes live video frames for real-time detection.

---

## 🚀 **Future Enhancements**
- **Expand Dataset:** Include more diverse images for robust classification.
- **Multi-Class Detection:** Add more classes, such as "Improper Mask Usage."
- **Edge Devices:** Deploy the model on low-powered devices like Raspberry Pi.
- **Improved Accuracy:** Fine-tune the model with advanced techniques for better performance.
- **Mask Positioning:** Add functionality to detect improperly worn masks.

---
## 🎥 **Project Demo**


## 🛠️ **How to Use**

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Snap0dragon/Covid-Face-Musk-Detection-MATLAB.git
