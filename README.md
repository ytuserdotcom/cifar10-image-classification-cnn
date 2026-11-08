# CIFAR-10 Image Classification Using Deep Learning (CNN)

## Project Overview

This project implements an image classification system using **Deep Learning and Convolutional Neural Networks (CNN)**.

The model is trained on the CIFAR-10 dataset and can classify images into 10 different categories. A user-friendly web interface is developed using Gradio, allowing users to upload images and view the predicted class along with confidence scores.

## Objectives

- Load and explore the CIFAR-10 dataset.
- Perform image preprocessing and data augmentation.
- Build and train a CNN model using PyTorch.
- Evaluate model performance using accuracy, loss, confusion matrix, and classification report.
- Save the trained model.
- Develop a web interface using Gradio for image prediction.

## Dataset

The CIFAR-10 dataset contains:

- 60,000 color images.
- 50,000 training images.
- 10,000 testing images.
- Image dimensions: 32 × 32 pixels.
- 10 different classes.

### CIFAR-10 Classes

1. Airplane
2. Automobile
3. Bird
4. Cat
5. Deer
6. Dog
7. Frog
8. Horse
9. Ship
10. Truck

## Technologies Used

- Python
- PyTorch
- Torchvision
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Gradio
- Pillow

## Project Workflow

1. **Data Preparation:** Load and explore CIFAR-10 images.
2. **Preprocessing:** Resize and normalize images.
3. **Data Augmentation:** Apply horizontal flipping, rotation, and shifting.
4. **Model Building:** Create a CNN architecture with convolutional and pooling layers.
5. **Model Training:** Train the CNN using Adam optimizer and Cross-Entropy Loss.
6. **Model Evaluation:** Evaluate performance using accuracy, loss, and classification metrics.
7. **Model Saving:** Save the best trained weights in a `.pth` file.
8. **Deployment:** Create a Gradio web interface for image classification.

## CNN Architecture

The model uses four convolutional blocks with:

- Convolutional Layers
- Batch Normalization
- ReLU Activation
- Max Pooling
- Dropout

The final fully connected layers produce predictions for 10 classes.

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

## How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/cifar10-image-classification-cnn.git
```

### Step 2: Open the Project Folder

```bash
cd cifar10-image-classification-cnn
```

### Step 3: Run the Application

```bash
python app.py
```

### Step 4: Open the Gradio Interface

Open the local URL displayed in the terminal, upload an image, and click the Predict Image button.

## Model Output

The application displays:

- Uploaded image preview.
- Predicted image category.
- Confidence score.
- Confidence scores for all 10 classes.
- Confidence comparison chart.

## Model Performance

Add your actual training and testing results here after running the model.

- Training Accuracy: [Add your result]
- Validation Accuracy: [Add your result]
- Testing Accuracy: [Add your result]

## Project Limitations

The model is trained only on CIFAR-10 categories. It may incorrectly classify images outside these 10 categories because it always selects one of the known classes.

## Future Improvements

- Improve model accuracy.
- Use more advanced CNN architectures.
- Deploy the application online.
- Add support for more image categories.
- Improve prediction reliability for unknown images.

## Author

**Adeel Ahmad**

B.Tech – Computer Science Engineering

## Acknowledgement

This project uses the CIFAR-10 dataset and open-source Python deep learning libraries for educational purposes.
