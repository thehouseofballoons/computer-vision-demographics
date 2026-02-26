# 👁️ Real-Time Demographic Intelligence System

### **Overview**
A high-performance Computer Vision system for real-time gender detection via live webcam feed. This project features a **custom-trained Convolutional Neural Network (CNN)** optimized for accuracy and low-latency inference, distinguishing it from standard implementations using generic pre-trained weights.

### **🚀 Key Technical Specs**
* **Model Accuracy:** ~89% on validation datasets.
* **Inference Type:** Real-time stream processing (Live Webcam).
* **Core Architecture:** Custom CNN trained using TensorFlow/Keras.
* **Vision Engine:** OpenCV with `cvlib` for robust face-bounding box logic.

### **🛠️ Tech Stack**
* **Language:** Python 3.x
* **Deep Learning:** TensorFlow, Keras
* **Computer Vision:** OpenCV (cv2), cvlib
* **Data Science:** NumPy

### **💡 Engineering Highlights**
* **Custom Training:** Developed a custom model to ensure optimized performance for specific demographic features, avoiding the bloat of general-purpose models.
* **Webcam Integration:** Implemented an efficient frame-processing loop that maintains high FPS (Frames Per Second) during live detection.
* **Data Preprocessing:** Standardized input images to 96x96 pixels with float-normalization (1/255.0) for consistent model prediction.

### **📦 Installation & Usage**
1. **Clone the repo:**
   ```bash
   git clone [https://github.com/thehouseofballoons/computer-vision-demographics.git](https://github.com/thehouseofballoons/computer-vision-demographics.git)
