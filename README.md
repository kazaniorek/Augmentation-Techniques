
# Augmentation Techniques and Model Performance Analysis

This project investigates the impact of various data augmentation techniques on the performance of machine learning models. Conducted as part of the CS4S773 module (Computational Applications of Artificial Intelligence), the project applies and compares multiple augmentation strategies using visual data.

## Objectives

- Evaluate the effect of image augmentation on classification accuracy
- Compare baseline model with models trained using different augmentation pipelines
- Measure performance improvements using quantitative metrics

## Techniques Explored

- Horizontal and vertical flipping
- Rotation
- Zooming
- Brightness variation
- Random cropping
- Combinations of multiple augmentations

## Workflow

- Load and preprocess image dataset
- Visualise and apply augmentation techniques
- Train multiple CNN models on different augmented datasets
- Evaluate performance using accuracy, loss, and visualisation of results

## Technologies

- Python
- TensorFlow / Keras
- NumPy, Matplotlib
- OpenCV / ImageDataGenerator

## How to Run

1. Install dependencies:
   ```bash
   pip install tensorflow opencv-python matplotlib numpy
   ```

2. Open the notebook `30030295.ipynb` in Jupyter or Google Colab.

3. Run all cells to train and compare models.

## Author

Mariusz Sołtycz

---

This project was submitted as part of the MSc AI coursework and demonstrates practical experimentation with data augmentation in deep learning.
