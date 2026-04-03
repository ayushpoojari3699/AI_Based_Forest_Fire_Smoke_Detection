# AI-Based Forest Fire & Smoke Detection

## Project Overview

Forest fires cause significant environmental, economic, and human losses every year. Early detection of fire and smoke is essential to prevent large-scale disasters.

This project presents an AI-based Forest Fire and Smoke Detection system using computer vision and deep learning techniques. The model analyzes images to automatically detect the presence of fire or smoke, enabling faster and more reliable early warning systems.

---

## Objectives

* Detect fire and smoke from images using deep learning
* Reduce dependence on manual monitoring
* Improve early detection accuracy
* Demonstrate the application of Convolutional Neural Networks (CNNs) in real-world safety systems

---

## Approach and Methodology

The system uses a Convolutional Neural Network (CNN) to learn visual patterns associated with fire and smoke.

### 1. Data Collection

* Images containing fire/smoke and normal scenes

### 2. Data Preprocessing

* Image resizing
* Normalization
* Label encoding

### 3. Model Architecture

* Convolutional layers for feature extraction
* ReLU activation for non-linearity
* Pooling layers for dimensionality reduction
* Fully connected layers for classification

### 4. Training

* Loss optimization using backpropagation
* Performance evaluation on test data

### 5. Prediction

* Classifies images as Fire/Smoke or No Fire

---

## Key Concepts Used

* Convolutional Neural Networks (CNN)
* Image preprocessing
* Feature extraction
* Backpropagation
* Activation functions (ReLU)
* Model evaluation metrics

---

## Technologies and Libraries

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* OpenCV (if used)
* Jupyter Notebook

---

## Results

* The model successfully learns visual features of fire and smoke
* Achieves reliable classification accuracy on test images
* Demonstrates the effectiveness of CNNs for vision-based fire detection

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/fire-smoke-detection.git
cd fire-smoke-detection
```

### 2. Install Dependencies

```bash
pip install tensorflow numpy matplotlib opencv-python
```

### 3. Run the Notebook

```bash
jupyter notebook
```

### 4. Execute

* Load dataset
* Train the model
* Evaluate performance

---

## Applications

* Forest fire monitoring systems
* Smart surveillance cameras
* Disaster management systems
* Environmental protection
* Early warning systems

---

## Limitations

* Performance depends on dataset quality
* Real-time deployment requires optimization
* Smoke detection may be affected by fog or clouds

---

## Future Enhancements

* Real-time video-based detection
* Integration with drones or CCTV systems
* Use of advanced architectures (ResNet, MobileNet)
* Deployment on edge devices (Raspberry Pi, Jetson)

---

## Conclusion

This project demonstrates how deep learning and computer vision can be effectively used for early forest fire and smoke detection. With further improvements and real-time deployment, such systems can play a crucial role in disaster prevention and environmental safety.

---

## Author

Ayush Poojari
GitHub: https://github.com/ayushpoojari3699
