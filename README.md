# Driver Behavior Classification and Alert System using Computer Vision

## Overview
This project focuses on detecting distracted driving using **Computer Vision** and **Deep Learning**. The model is trained to classify various driver behaviors using **CNNs**, aiming to enhance road safety by alerting drivers in real-time. The system can be implemented in vehicles to **automate monitoring, reduce accidents, and improve insurance claims processing**.

## Features
- **Deep Learning-Based Driver Classification**: Uses CNNs to classify different driver behaviors.
- **Real-Time Monitoring**: Detects distractions and alerts drivers instantly.
- **Automated Insurance Claims Support**: Helps insurers verify accident causes.
- **Scalability**: Can be extended with additional safety features like **night vision** and **facial recognition**.

## Problem Statement
Distracted driving is one of the **leading causes of road accidents** worldwide. Traditional monitoring methods are manual and prone to errors. This project leverages deep learning techniques to **automate driver behavior detection**, enhancing road safety and reducing accidents.

## Objective
The key objectives of this project include:
- Developing a **CNN model** to classify driver behaviors.
- Training the model on a **diverse dataset** for robustness.
- Implementing a **real-time alert system** for distracted drivers.
- Improving **road safety and reducing accident rates**.

## Dataset
The model is trained on the **State Farm Distracted Driver Dataset**, which includes **22,424 images** categorized into different driver behaviors such as:
- Normal driving
- Texting while driving
- Talking on the phone
- Eating/drinking
- Adjusting the radio

Data **augmentation techniques** (rotation, flipping, scaling) are applied to improve model performance.

## Model Architecture
The system uses a **Convolutional Neural Network (CNN)** with:
- **Convolutional Layers** – Extract local image features.
- **Max Pooling Layers** – Reduce dimensionality and computational load.
- **Dropout Layers** – Prevent overfitting.
- **Fully Connected Layers** – Perform final classification.
- **Softmax Activation** – Outputs class probabilities.

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- Python 3.x
- TensorFlow / Keras
- NumPy
- OpenCV
- Matplotlib

### Installation
Clone the repository:
```bash
git clone https://github.com/your-username/driver-behavior-classification.git
cd driver-behavior-classification
```
Install dependencies:
```bash
pip install -r requirements.txt
```

## Usage
### Training the Model
To train the model, run:
```bash
python train.py
```
### Making Predictions
To classify an image:
```bash
python predict.py --image path/to/image.jpg
```
### Evaluating the Model
Run:
```bash
python evaluate.py
```

## Results & Performance
- Achieved **98% classification accuracy**.
- Successfully detects distracted driving in real-time.
- Validation accuracy closely matches training accuracy, **minimizing overfitting**.

## Future Enhancements
- **Night Vision Capability** – Improve detection in low-light conditions.
- **Facial Recognition Integration** – More precise driver behavior tracking.
- **Dynamic Camera Positioning** – Enhanced detection angles.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository
2. Create a new branch (`feature-branch`)
3. Commit changes
4. Open a Pull Request

## Contact
For any questions, feel free to reach out:
📧 **frhanahmd665@gmail.com**

