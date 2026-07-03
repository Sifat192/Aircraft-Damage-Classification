# Aircraft Damage Classification using VGG16 Transfer Learning

A deep learning project that classifies aircraft damage images using **VGG16 Transfer Learning** with **TensorFlow** and **Keras**. The project demonstrates image preprocessing, data augmentation, transfer learning, model training, evaluation, and prediction on aircraft damage images.

---

## Project Overview

Aircraft damage detection is an important task in the aviation industry, helping reduce manual inspection time and improve maintenance efficiency. This project leverages a pretrained VGG16 convolutional neural network to classify aircraft images into damage categories using transfer learning.

The workflow includes:

- Image preprocessing
- Data augmentation
- Transfer Learning with VGG16
- Model training
- Model evaluation
- Prediction on unseen images

---

## Dataset

The dataset consists of aircraft images organized into:

```
Dataset/
│
├── train/
├── validation/
└── test/
```

Images are resized and processed using TensorFlow's `ImageDataGenerator` with data augmentation applied to the training dataset.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab / Jupyter Notebook

---

## Model Architecture

The project uses **VGG16**, a pretrained convolutional neural network trained on the ImageNet dataset.

Transfer learning is employed by:

- Loading pretrained VGG16 weights
- Using VGG16 as a feature extractor
- Adding custom classification layers
- Training the classifier on the aircraft damage dataset

---

## Project Workflow

1. Import required libraries
2. Load and preprocess the dataset
3. Apply image augmentation
4. Build the VGG16 transfer learning model
5. Train the model
6. Evaluate model performance
7. Visualize predictions

---

## Results

The model successfully learns meaningful visual features from aircraft images using transfer learning and demonstrates effective classification performance on the test dataset.

Performance is evaluated using:

- Training Accuracy
- Validation Accuracy
- Loss Curves
- Prediction Visualization

---

## Future Improvements

- Fine-tune deeper VGG16 layers
- Compare with ResNet50 and EfficientNet
- Apply Grad-CAM for model explainability
- Hyperparameter optimization
- Deploy the model using Streamlit

---

## Repository Structure

```
Aircraft-Damage-Classification/
│
├── Aircraft_Damage_Classification_VGG16.ipynb
├── README.md
├── requirements.txt
├── LICENSE
└── images/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/Aircraft-Damage-Classification.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

---

## Skills Demonstrated

- Deep Learning
- Transfer Learning
- Computer Vision
- Image Classification
- TensorFlow
- Keras
- Data Augmentation
- Model Evaluation

---

## License

This project is intended for educational and portfolio purposes.
