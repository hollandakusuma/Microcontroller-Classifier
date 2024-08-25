# Microcontroller-Classifier

This repository contains a machine learning project designed to classify different types of microcontrollers based on their features. The project leverages a deep learning model trained on a dataset of microcontroller images or specifications. The goal is to accurately identify and distinguish between various microcontroller models.

## Key Features:
- **Dataset**: Includes a diverse set of microcontroller images/specifications with varying resolutions.
- **Model Architecture**: Utilizes a Sequential model with Conv2D and Pooling layers.
- **Training and Validation**: Split into 80% training and 20% testing datasets. Achieved over 95% accuracy on both training and validation sets.
- **Deployment**: The trained model is saved in multiple formats, including SavedModel, TF-Lite, and TFJS, allowing for versatile deployment options.
- **Inference**: Provides examples of running inference using the trained model in TF-Lite, TFJS, or using TF Serving.

## How to Use:
1. **Clone the Repository**: `git clone https://github.com/yourusername/Microcontroller-Classifier.git`
2. **Training**: Follow the instructions in the `training` folder to train the model on your dataset.
3. **Inference**: Use the `inference` scripts to classify new microcontroller images or data.

This project is ideal for engineers and hobbyists looking to automate the identification of microcontrollers in their projects.
